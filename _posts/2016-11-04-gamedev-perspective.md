---
layout: post
title:  "Gamedev Perspective"
date:   2016-11-04 16:50:00 -0800
categories: programming unity3d gamedev
---

>"[I]t’s a waste of your time and energy.
>Your engine won’t be as efficient or compatible as the preexisting engines.
>Engine development isn’t game development, so you don’t need to, but never let
>that stop you from experimenting." - Garry Newman on making your own game engine

## Rock Bottom ##
{: title="or close to it..."}
For the last year or so, I've been obsessing over making an RPG engine for a game
project I've undertaken with a few friends. Through arduous experimentation, I've
managed to cobble together a dialogue system, an inventory system, a rudimentary
party system, and even a convoluted event-based visual scripting system which I
ended up replacing with Behaviour Machine from the Unity Asset Store. I had
a problem, though: My codebase was a mess.

While I tried my best to follow "good" OOP practices, some things never really
fit together the way I had hoped. Somewhere between player controls and dialogue,
I became obsessed with encapsulation, interfaces, data packages, and events.
After a while, my code was a series of semi-independent systems resembling
large, unmanageable heaps... but at least they were independent heaps.

The heaps I'd produced had plugs and sockets thrown about, just waiting to be
adapted to Behaviour Machine's blackboard. I probably could have hooked it all
up, too, except that I ran into one fatal question: How do I save my data for
when I inevitably need to close and relaunch my game?

To answer that question, I had to begin to rethink how I was currently doing things.
At the time, I had proudly set up my systems so that things like stats and HP
could be changed on the fly; simply drop an item into a character's inventory and
you could change their strength, vitality, or any number of numbers found in the
ActorStats component, but how do I go about saving that? The naive approach would
be to use Mono's object serialization, but then what happens when I need to update
the serialized object and one of its fields changes? The next best solution would be
to create a custom serialization system based on something intelligent like
protobufs. At this rate, I would have to redo my party system, my stats system, and
my inventory system. Everything thus far had been built independently with no ability
to actually set its state (by design.) Every part of every system I had designed
assumed that at the moment of its creation, it was new and every state change
within these systems affected the state of something else. Because the state of
other objects was dependent on the state of the object itself, there was no room
to allow another object to completely set its state. If an item was to be added to
an inventory, there would be no way to add that item to the inventory without
firing off some event somewhere. The defensive programming patterns I had been
using up to this point had not allowed it.

## Another Framework ##
So, where do I currently stand? Well, I could spend another month or two refactoring
and eventually building a serialization compatible, but still idiot-proof RPG
framework, or I could take the advice of better devs than myself and use
somebody else's engine. So far, I'm liking the ORK Framework.

The ORK Framework appears to be feature-rich, including all of the features I want.
It supports parties, dialogues, menus, stats, battles (turn-based and active), but
yields to the developer when necessary. At first glance, it appears to rub
against Unity's workflow, but in reality, it's mostly just filling the gaps. When I
first stumbled upon ORK, I thought the $100/seat price-tag was a bit steep, but the
limited version seems to have all the features necessary for a good prototype.

I'll stick to ORK for now, learning how it works and building on its existing tools.
I should have known better than to try to build my own framework from scratch my
first go-around, but hindsight is 20/20 and <span title="&quot;Experience is what you get when you didn't get what you wanted.&quot; - Randy Pausch">I've learned from this experience.</span>
If this doesn't work out, I'm sure I could grab some other tools from the asset
store, but not having to build an entire RPG framework is a welcomed change and
a huge weight off my shoulders. Now I just have to figure out how to use the damn
thing.

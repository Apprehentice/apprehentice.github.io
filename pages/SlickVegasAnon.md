---
layout: page
title: SlickVegas Anon Module
permalink: /SlickVegas/AnonModule
---

If you've not met him, SlickVegas is my Discord bot. He has many features from a dice roller to gallery channel enforcement. One of these features is an anonymous message relay. This relay is meant to work as a sort of anonymous confessions provider, but can also relay media for anonymous photography and videography.

Due to the personal nature of content likely to be sent through this system, I felt it necessary to be completely transparent about how it all works.

## Logging ##
Messages sent through this module are not logged, but SlickVegas will log events related to your DMs with him. That's not part of the module, it's just how he works. That means he will record the time he received your message, your typing indicators, reactions, and the like, **but he will _not_ save the content of your messages**. Your message contents are something I do not wish to store on my hard disk.

Although SlickVegas isn't logging anything, Discord is, so don't share anything you wouldn't share in court.

## The Rules ##
1. The poster must be able to read messages in the target channel<span title="1b. SlickVegas must have permission to post in the target channel">.</span>
2. Angle brackets will be removed from messages to prevent mentions
3. Messages sent before your cooldown runs out will be ignored

## How it works ##
1. Send a message to SlickVegas starting with <span title="ghost">👻</span> followed by the target channel's Discord snowflake ID and your message
2. If your message is valid, you have permission to view the target channel, and you don't have a cooldown on that channel, your message will be relayed
3. SlickVegas will confirm whether or not your message was sent

## Moderation ##
Things like this are hard to moderate. The cooldown feature is meant to prevent flooding and I advise not turning it off. For more control, you can set up a moderator only channel as the target and have a mod manually relay anonymous messages on behalf of SlickVegas. This is probably the most secure option.

## Commands ##
### In Channel ###
`enable/disable anonymous messages here`

**Required Permissions**: Manage Channels

**Description**: Enables/disables anonymous text messages in the channel

---

`set anonymous cooldown to <seconds>`

**Required Permissions**: Manage Channels

**Description**: Sets the anonymous message cooldown rate to the specified number of seconds

## Extra Data ##
SlickVegas will post extra data to the channel with the message. This includes a timestamp and the source message ID. These are needed in case Discord staff needs to get involved. Nobody but Discord can trace a DM back to its ID.
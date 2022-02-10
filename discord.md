---
title: Discord
layout: default
toc:
    - "Where's the Discord Server?": wheres-the-discord-server
    - "Introducing Matrix": introducing-matrix
    - "How do I Join Matrix?": how-do-i-join-matrix
---

**tl;dr** Discord is insecure, so I'm using Matrix for this community. Join [#apprehentice:matrix.clubvt.xyz](https://matrix.to/#/#apprehentice:matrix.clubvt.xyz) to join us. It's free and you can chat in your browser if you like.

## Where's the Discord Server? ##

My Discord server is closed at the moment because I believe Discord to be an insecure, dangerous, and anti-consumer platform. This is mostly due to the recent rise in [various](https://blog.malwarebytes.com/scams/2021/10/discord-scammers-lure-victims-with-promise-of-free-nitro-subscriptions/) [scams](https://www.reddit.com/r/discordapp/comments/s1f1vs/the_recent_try_my_game_discord_scam_explained/). Until Discord bolsters security sufficiently enough that these attacks are difficult to impossible, I will be using another platform.

## Introducing Matrix ##

Instead of Discord, I'm using [Matrix](https://matrix.org/). I have created my own Matrix homeserver at matrix.clubvt.xyz so that I may have spaces for the various topics that a Discord server can accomodate, keeping the community together and giving you yet another place to share photos of your pets.

Already have a Matrix account? Just look up the room directory for matrix.clubvt.xyz and join the channels you're interested in. For those who don't, I'll go over that later in this article.

### Why Matrix? ###

Matrix is a decentralized and federated chat service that supports modern chat features such as VoIP, reactions, embeds, and end-to-end encryption (which Discord doesn't have). It exists somewhere between Discord and IRC. Just like IRC, each Matrix server may contain hundreds of channels belonging to dozens of communities, but like Discord, these channels can be grouped together.

### How is it more secure? ###

Discord has a few flaws. At the time of writing, accessing somebody's auth token, email address, password, and 2FA tokens is a trivial endeavor thanks to modern malware and phishing techniques. The most egregious of these flaws is the ability for accounts to review their 2FA backup codes after 2FA has been applied. This should **never** happen and results in attackers being able to get a user's 2FA backup codes, remove 2FA, and set up their own 2FA. Discord support has proven to be useless in the recovery of accounts stolen in this way.

Matrix, on the other hand, handles 2FA properly, has actual per-device session management, and end-to-end encryption with device verification.

## How do I Join Matrix? ##

Joining is easy. If you don't have a Matrix account, you can get one for free with any Matrix client. If you follow along, you'll have a fresh account with Matrix.org as your homeserver, using the Element Matrix client.

1. Visit [https://app.element.io/](https://app.element.io/)
2. Click "Create Account"
    * Create an account with one of the shown providers
    * -OR- Complete the form to use a username and password
    * You should now be in the Element Matrix client.
3. Join [#apprehentice:matrix.clubvt.xyz](https://matrix.to/#/#apprehentice:matrix.clubvt.xyz) either by clicking the link, by searching for it, or by typing `/join #apprehentice:matrix.clubvt.xyz`
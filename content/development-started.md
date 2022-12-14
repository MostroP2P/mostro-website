+++
title = "Development started"
description = "Working on a proof-of-concept on Nostr0"
date = 2022-11-09
+++

Due to the growing need to be able to operate with Bitcoin without giving up personal data, last year I started a project to allows people to buy and sell Bitcoin through Lightning Network without funds custody and of course without KYC, this project is a telegram bot called [@lnp2pbot](https://lnp2pbot.com/).

@lnp2pBot is growing steadily and organically, it's being use in the whole world but is having a bigger impact in Latin-America, a place where there is no need to explain to people that money is broken, it's being used more and more in dictatorial regimes like Cuba and Venezuela, where people keep resisting tyranny and protesting using less the local currency and more Bitcoin.

Although the bot works excellent, it's running on top of Telegram, a great platform but we do not know if one day it will be reached by the tentacles of a powerful government asking for political dissidents or simply awkward public person.

This is where enter [nostr](https://github.com/nostr-protocol/nips) as a platform where the bot can live without the possibility of being censored by a powerful entity, a month ago I started to research about nostr to see if we can create a new bot version, a censorship resistant version that makes it unstoppable, a new **Monster** version.

Recently I started a [first version](https://github.com/mostro-bot/bot) that runs a nostr bot and only returns a lightning invoice when a user send a event kind 1, this is coded on Rust and will be developed in the next weeks.

If you are a Rust developer and want to participate on this project let me know, we are just starting and you can be since the beginning. happy hacking!

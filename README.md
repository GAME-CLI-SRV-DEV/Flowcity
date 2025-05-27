Flowcity(TM)
=========

Flowcity is Waterfall with Velocity. Waterfall is a fork of the well-known [BungeeCord](https://github.com/SpigotMC/BungeeCord) server teleportation suite.

Waterfall was discontinued on 2024, and it is recommended to switch to velocity.\
However there was no better alternative for ViaProxyConnect Original Plugin, Available for Velocity, and we had no choice but to use Travertine as template.

## Why fork Waterfall, and Why you dont use velocity and Shared Hosting?

Well, shared hosting makes minecraft servers cramped in one server, result? server will not boot due to a Out of memory(aka OOMKiller). so many of you guys, suggesting me to Buy more server, i would say one thing. Financial Problem. you see, we need to feed all the servers for more performance. of course, we need to pay electricity and server bills. if approximaster purchased more server, it would cost quadrillion dollars. we cannot afford that.
so we had no choice but to make this thing instead.


## How to (Server Admins)

You Need To Build it yourself.

To compile flowcity, you need git, gradle, and an internet connection.

Clone this repo, run `./patch` from *bash*, run `./gradlew build` and get jar from `Flowcity-Proxy/bootstrap/target`

## ViaProxy/VIAaaS Usage

to use ViaProxy, you need to set `ViaNetwork:` settings.

on flowcity.yml:
```
ViaNetwork:
# configure the Integration ViaVersion Network.
# 
# ViaProxy: if it's enabled, connecting to .viaproxy.hostname:<bungeeport> will be deemed as Forced Host.
# ViaProxyPort: set it to connect to viaproxy if it runs on specified port.
# Viaaspirin: if it's enabled, connecting to viaaas hostname will be deemed as a forced host.
# aspirinprefix: setting it will redirect to desired viaaas prefix.
# aspirinport: set it to connect to viaaas if it runs on specified port.
# WARNING! You will be granting access to all servers!
ViaProxy: enabled
ViaProxyPort: 25565
```

## PR
We Accept contributions.\
Copyright (C) 2025 Approximaster Studios 2004, All Rights Reversed, Under GNU GPL 3.0.

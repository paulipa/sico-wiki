---
title: Discord
description: 
published: true
date: 2020-10-12T08:07:29.805Z
tags: 
editor: markdown
dateCreated: 2020-07-06T16:13:01.899Z
---

# What is Discord?
Discord is a free to use team communication program. Unlike the in-game chat that you use to stay in touch with your friends you do not need to launch your client or even be at your PC to chat with the other members or to get in touch with the staff!

Discord works both as a web browser based program as well as a installable program that works with most mobile operating systems! This means that you can always carry us with you and receive the most important news right at your phone. It also allows you to contact our leadership or the players that you need to get in touch any time and anywhere.

Discord can be used both as a public group chat as well as to have private conversations with all the players that have registered on the program. This way you can leave a message on the chats and unlike the in-game chat people will see your messages after they log in the next time! It also comes with a integrated voice chat for those who don’t mind the low quality of the voice!

> Discord is our primary communication channel outside of the game! It is important for you to register and activate the services to gain access to the coalition channels.
{.is-success}

## Joining and authenticating
Joining and authenticating on our discord is super easy. Like with all of our services you will get started from the [AUTH](/tools/auth) system page. Once you have registered and selected a main character you will be able to activate services from the services section.

### Step 1
First you will need to register on AUTH at https://auth.eve-linknet.com/. Guide for this can be found in [here](/tools/auth).

> Before you can register on AUTH you must join one of our coalition corporations ingame. How to [join us](/joining-us/)
{.is-warning}

### Step 2
After you have registered on AUTH you will need to go to the services section on AUTH https://auth.eve-linknet.com/services/ and activate the discod service by pressing the yellow button next to it.

### Step 3
After you click on the activation button the program will direct you to the discord login page. `Log in with the discord user you normally use as your main discord account.` **If you are using the discord desktop client make sure that you are using the same account!**

### Step 4
Allow the bot to invite you to the server.

### Step 5
You have now linked your discord account with your AUTH account and the system will update your roles and your nick name on the server after a while.

## Nice to know

**Tip 1**
It may take a long time for your nick to update. You can try to deactivate and activate the service again to force the nick check.

**Tip2**
If you have just joined the corporation the ESI might not have updated yet. If you get the guest role after activating discord service you have done it correctly and all you need to do is wait for the change to apply on ESI side.

# Discord Ping rules
Since we do not want to spam people with too many pings on discord which may cause them simply to mute all pings there are some rules and restrictions for pings

Our ping rules are located in here: https://wiki.eve-linknet.com/en/tools/auth#discord-fleet-pings

# Troubleshooting
Most common fix for discord not linking your roles

## Case 1: Wrong account
**Problem**: `Most common problem for not getting your roles to sync` after you have activated the discord service is that you have activated the service with a wrong discord account. This happens when you are logged in on the web browser version discord with a different account that you use with your client. This causes you to authenticate on the web browser account allowing you to get roles on that account while leaving your primary account that you use on the client unauthenticated.

**Fix**: To fix this first log out from the discord web browser app at discord.com/app. Additionally also log out or close the discord client on your PC. Deactivate the discord service on the AUTH service page by pressing the big red X. Now activate the service again and make sure that when asked to log in on the web browser discord (if you are not asked to log in you didnt log out your client) you log in with the account that you use on your discord client.

## Case 2: API Cache
**Problem**: If you just joined the corporation and activated the discord service your API cache may have not been updated yet. If you got a guest role on discord it means that your account is synced correctly.

**Fix**: Wait a while. API is cached up to 30 minutes and our AUTH checks your roles every 4 hours. To not wait 4 hours you can try to reactivate the discord service when you see that you corporation status has changed on the dashboard page of AUTH.

## Case 3: Wrong name on discord
**Problem**: After activating the discord service on AUTH and after gaining your member roles your name might still be your default name. The bot tries to rename you when you activate the discord service, but often fails if you already have joined the server before you activated the service on auth.

**Fix**: Either reactivate the service or wait around 4 to 8 hours. The bot renames all players on the discord service but might hit the API limit with the amount of players we have on the server.

## Error 500 on activation
**Problem**: When trying to activate the service on AUTH you receive an error 500. While this is a general server error in this case it most often means that the service fails to add you to the server because you have already joined the server.

**Fix**: Leave our discord server by opening our discord server and right click the server and press leave server. After leaving the server try activating the service again.

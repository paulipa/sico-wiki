---
title: Mumble
description: 
published: true
date: 2020-07-07T05:36:52.887Z
tags: 
editor: undefined
---

# What is Mumble?
Mumble is a third party VoIP program that allows large amount of players to chat in an organized way. While setting it up and using it is a bit more difficult than using Discord voice chat, it comes with many perks that Discord can’t deliver.

The crucial functions that are missing from Discord voice chat and can be achieved on Mumble are: 
- Ability for commanders to chat on back channel during multi fleet operations.
- More stable on larger user counts than Discord

> For the reasons mentioned above Mumble is used for all important large scale operations within SiCO. This is why you should have it set up sooner than the beginning of the event or fleets.
{.is-info}

# Setting up the Mumble program
This section will cover you the basic setup of the Mumble program.

1. Go to the official Mumble page and download the client https://www.mumble.com/mumble-download.php

2. Install the program

3. Run the audio wizzaard to setup your microphone and output device. In most situations the default settings will be fine.

4. Open the mumble settings and put the settings mode to advanced
![mumnle1.jpg](/mumnle1.jpg)
![mumble2.jpg](/mumble2.jpg =300x)

5. Go to the Messages section. In here you will determine what messages are shown/played out for you. On default there are three different notification types:
	`Console` – Shown up as text on the console area of the mumble client
	`Notifications` – Pop-up alert box with text
	`Text-to-speach` – Plays out the message as a sound file

	> This step will disable some of the anoying text-to-speach notifications
{.is-success}

	We highly recommend that you disable at least the other user related  text-to-speach notifications (user has joined or left your channel)as they will anoy the hell out of you when a lot of playeres are on comms at the same time
  ![mumble_voice_settings.jpg](/mumble_voice_settings.jpg =400x)

6. Go to the overlay tab. If you are using EVE in full screen mode (lol?) then this option will show up the members of your channel inside a box. While it might be cool when its just you and few of your friends, it will be anoying if there are 100 other players on the channel. You can disable this if you prefer not to use it on this section.
![mumble_overlay-592x400.jpg](/mumble_overlay-592x400.jpg =400x)

7. Go to User Interface and select the expand channels to all. This makes it easier for you to see the whole structure of the Mumble server. On extreme large servers you do not want to use this setting.
![mumble_expand_channels.jpg](/mumble_expand_channels.jpg =500x)

8. Go to the Audio settings tab. You want to disable the highlighted audio setting as this may lowers your other system sounds when someone is talking. This may cause problems with losing audio on programs if you alt-tab 
![mumble_mute_setting-563x400.jpg](/mumble_mute_setting-563x400.jpg =500x)
9. Go to audio input settings and set the Transmit type to push to talk
![push_to_talk.jpg](/push_to_talk.jpg =500x)

## Activating Mumble on AUTH
After you have set up your Mumble client you can link your AUTH account to your Mumble user. To do this:

> You will get your username and password from AUTH after activating the service.
{.is-info}


1. Go to AUTH service section in here https://auth.silentcoalition.com/services/

2. Click on the actication button for Mumble
![activate_mumnle.jpg](/activate_mumnle.jpg =300x)
3. Open your Mumble client -> Click on connect -> click on add new. Fill in the following information:
	
  Address: silentcoalition.com
	Port: 64738
	Username: **COPY THIS FROM AUTH!**

4. Click on Connect

5. You will be asked a password. Copy this from AUTH. See following gif: [mumble credentials](/mumble_auth_activation-722x400.gif)

## Line member keybinds
As a line member your key binding setup is very simple. Go to the shortcut options. Click on add -> Select type Push to Talk -> Assign a key for it.

See the following gif: [line members keybinds](/mumble_keybind-577x400.gif)

## Fleet commander keybinds
Fleet commanders and fleet commander trainees will need to add 2 more keybinds. These are self command channel only and all command channel keys.

### Command Channel
`Command Channel` – Will talk to all fleet commander in the other command channels and not talk to line members in the fleet channels

To do this go to the shortcuts options. Click on Add -> Select type Whisper/Shout -> Set data to shout to channel, select the parrent channel and select shout to subchannels.

See the following gif: [command channel keybinds](/mumble_command_sewhisper-577x400.gif)

### Self command channel
`Self Command channel` – Will talk only inside your own command channel and not broadcast to any other command channels or to your fleet.

To do this go to the shortcuts options. Click on Add -> Select type Whisper/Shout -> Set data to shout to channel, select the current. Do not select subchannels or linked channels.

See the following gif: [self command channel keybind](/mumble_self_whisper-577x400.gif)

# Using Mumble during fleet operations

Multiple fleets are supported during large fleet operations. Each Fleet channel has a command channel linked to it.

Fleet commanders will be located inside the linked command channel and fleet members will be located inside the fleet channels.

When fleet members use push to talk key both the other fleet members and the fleet commander in the command channel are able to hear them.

`When a fleet commander uses push to talk` both the fleet members in their fleet channel and any possible other fleet commanders in the same command channel are able to hear them.

`When a fleet commander uses Command Channel (whisper/shout to parrent + subbchannels)` all the other fleet commanders in the other command channels are able to hear them but fleet members can’t. This is used to cross fleet fleet commander chattering.

`When a fleet commader uses Self Command Channel` (whisper/shout to current) only the other players inside the same command channel are able to hear the fleet commander.

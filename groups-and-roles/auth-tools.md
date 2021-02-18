---
title: AUTH tools for FCs and Leadership
description: 
published: true
date: 2021-02-18T16:46:42.779Z
tags: 
editor: markdown
dateCreated: 2021-02-18T16:45:56.710Z
---

# AUTH tools for roles and groups
AUTH has several functions for leadership and Fleet Commanders usage. These includes things such as FAT link generation and corporation member tracking. 

> This section is only for players with FC roles or above in the coalition. Normal members are unable to access the management side of these tools.
{.is-info}

## Group management
If you belong to a group that is a manager group for a lower class group you will be able to accept and decline applications from other members to that group.

- Navigate to https://auth.eve-linknet.com/group/management/
- See if there are any applications to any groups.
- If you know the applicant you may accept the application as per your own group rules.
- If you do not know if you should accept the player to the group, then you most likely should not.

## Corporation stats
> This tool is only for CEOs and Directors
{.is-warning}

You can track your corporation member AUTH status and their alts at https://auth.eve-linknet.com/corpstat/

In order to gain access to the tracking you will need to add a director level token to the tool by pressing on the add token.

On corporation status page you can:
- See who is registered on AUTH
- See main char and alt relations
- See service statuses of your members

## Generating FATs
If you are a coalition Fleet Commander, Fleet Commander Trainee, CEO or a Director you are able to create FAT links for your fleets. Fat links are used to track member participation in your fleet.

### What fleets qualify for a FAT
Only "proper" fleets qualify for FATs.

Scheduled fleets on AUTH such as: MQP, Roams, War Fleets or PvE fleets inc. incursions qualify for a fat.

Proper flash form fleets as: SLTRN Defence fleet or PvP Roams that you ping on discord with > 5 members in it qualify for a FAT

Mining fleets or small duo pvp fleets do not qualify for FATS.

Only one fat per fleet is allowed

With FAT 2.0 you have a few ways to create links:

> Fats over ESI is your primary method for FAT generation
{.is-info}

### Fats over ESI
1. Have a toon as a fleet boss in your fleet
2. Go to the FAT page: https://auth.eve-linknet.com/imicusfat/
3. Click on Add FAT Link https://auth.eve-linknet.com/imicusfat/links/add/
4. Add a name for your fleet. Remember to use proper tags like MQP for tracking.
5. Click on Add ESI link
6. Log in with the fleet boss toon and press the green arrow to register the scope
7. All members will be pulled over ESI after a short while. If you get a success message the members will be pulled over ESI once the current task que is processed. This may take a long time.

> ESI links will keep on tracking people who join your fleet when the ESI link has been tracked. This means that if you FAT your fleet in the start of your fleet then each player who joins and leaves the fleet during the fleet will be registered.
{.is-info}

> If you do not get any errors it means the FAT over ESI worked. It may take some time for the players to show up. **Do not create a new fat if there was no errors.**
{.is-warning}

## Scheduling fleets
You are able to pre schedule fleets and add them to our fleet board. The fleet board is found on AUTH at https://auth.eve-linknet.com/opcalendar/. Please create a fleet in here whenever you plan to do a planned fleet in the future. You can always cancel the fleet in case you are unable to do it or if no one shows up.

### To create a fleet operation:
1. Go to https://auth.eve-linknet.com/opcalendar/
1. Check that there are no fleets scheduled to the time you are going to schedule
1. Click on the + New Event button
1. Fill in all needed information

Notifications will automatically go out on discord `#operations-tracker` channel for new, deleted and edited operations.

## Discord Fleet Pings
In order to send out a fleet ping on discord please use the ping formatter found on Auth https://auth.eve-linknet.com/discordpingformatter/

Coalition aims to keep pings to a minimum so that in case we have an actually important operation people will pay attention to the pings.

> Please stick to the ping rules as below:
{.is-warning}

### Ping rules
1. Schedule fleets via https://auth.eve-linknet.com/optimer/. All fleets scheduled in here will automatically be posted in the `#operations` channel on discord. 
1. When your fleet goes up ping it at the `#fleet-pings` channel with the formatter.
	1. For stratop and CTA fleets use `@here` or `@everyone` pings. We want to keep these to minimum
  	2. For every other fleet **please pick the correct SIG group** from the drop down window on the formatter.
    
If you need to hype or rage ping a non CTA fleet more or extend the ping to multiple SIGS you can ping `@here` inside the SIG channels.

### Pre Pings
You can create pre notifications about your fleet if you want to hype it up. To do so:
1. Open the Discord Ping Formatter
1. Tick the Pre-Ping box
1. Ping target: 
	1. For stratop and CTA fleets use `@here` pings.
  	1. For every other fleet **please pick the correct SIG group** from the drop down window on the formatter.
    1. You can also send out the pre notification without a ping. Use the NO PING option.
1. Select ping target to `PRE pings (#operations)`
1. Fill in rest of the information

If you need to hype or rage ping a non CTA fleet more or extend the ping to multiple SIGS you can ping `@here` inside the SIG channels.

## Member Audit
You are able to audit the details of each character in your corporation with the member audit tool. This requires that your members have [added an tracking token](https://wiki.eve-linknet.com/en/tools/auth#my-characters-member-audit) for their characters.

> You can only see details for characters that are in your own corporation or from characters who have enabled the sharing.
{.is-info}

### Auditing

To display details:
- Go to the character finder tab https://auth.eve-linknet.com/member-audit/character_finder
- Click on the character you want to view

### Reports
Reports will display if a character matches predetermined filters with skills. This can be used to determine if a character can fly certain doctrines or meet the requirements for joining your corporation.

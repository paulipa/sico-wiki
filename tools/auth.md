---
title: AUTH
description: Central access management program
published: true
date: 2020-07-21T13:36:10.631Z
tags: 
editor: markdown
---

# What is AUTH
SiCO AUTH is a central management system that links your EVE online character by taking advantage of the EVE SSO system to all of our third party services. This way we can identify your ingame character in our systems and restrict any non members out from the system.

You can read more about EVE SSO in here https://support.eveonline.com/hc/en-us/articles/205381192-Single-Sign-On-SSO

We are currently using a modified version of https://gitlab.com/allianceauth/allianceauth

> Using SSO login is perfectly safe. You will be logging in on an official EVE Online page and the page will then let our system know that you are who you claim to be. No account information is shared to us.
{.is-success}

> Our AUTH only requires a public scope that provides us the same information as viewing your profile ingame does. We can't see any of your personal information.
{.is-info}

# Registering On AUTH
1. Navigate to https://auth.silentcoalition.com
1. Click on the log in with EVE Online. This is the SSO Login form to a official EVE Online site. 
![auth1.jpg](/auth1.jpg =300x)
1.  Log in with the EVE Online account, that holds your main character. The name of this character will be used on all of our services and be the name you will be identified with. 
![auth2.jpg](/auth2.jpg =300x)
> If you are playing with Steam make sure you log in with the small log in with steam buttom located on the bottom right corner!
{.is-warning}
4. Select your main character
![auth3.jpg](/auth3.jpg =300x)
4. Enter a valid email address. This email will be used with external services that require an email.
![auth4.jpg](/auth4.jpg =300x)
> There is no confirmation mail. Simply log in after creating your account.
{.is-success}
6. Log in with the same account you just registered with

## Adding alts
> Do not create new accounts for alt characters. All alts are added under your main account.
{.is-warning}
1. To add alts under your main so that their activity are counted as activity for your main press the [add character](https://auth.silentcoalition.com/account/characters/add/) button on AUTH dashboard. This will link your alts to your main character.

## Joining Groups
The coalition has a lot of different types of players with different goals in EVE. Since we do not want to spam you with any content you are not interested in we have created special interest groups, SIGs
![auth6-1400x429.jpg](/auth6-1400x429.jpg =300x)

### Special Interest Groups
By joining the special interest groups you will gain access to the respective discord rooms. In these rooms you will receive notifications about the content related to your interests.

There are a great number of things you might want to focus on in EVE. Amongst other things we have groups created for PvP, Capital ships, incursions, triglavian invasions, mining, pve, wormhole space, hauling, planetary interactions, faction warfare and many other things.

To add yourself to the special interest group simply go to https://auth.silentcoalition.com/groups/ and add yourself to the groups that start with Special Interest by pressing the request button. You will automatically be approved to the group and gain access to the discord channels related to these groups. 

You can also leave any SIGs from the groups page by pressing the leave button. This way you will no longer receive notifications for this type of content.

### Normal groups
Normal groups are groups for people that want to take up special roles in the coalition. These roles most often requires some skills or higher understanding about the game and each applicant will be approached individually via discord before their application is accepted.

> See the description of the roles before applying to them.
{.is-info}

## Services
Services are third party programs that are linked to your EVE character by AUTH. AUTH will migrate your roles, name and corporation information over to the different services so that you can access the right channels and do not gain access to any channels you do not belong to.

> Our most imporant service is the discord service. For activation guide see [Discord activation guide](/tools/communication/discord)
{.is-warning}

Please activate any services you feel like using.

# Troubleshooting

## No activation mail
There is no longer activation mails sent. Simply log in after creating your first account.

## I can't see groups
Certain groups are only visible for coalition members. It may take up to a few hours for your corporation change status to take effect on the API

## I can't see services
Certain services are only visible for coalition members. It may take up to a few hours for your corporation change status to take effect on the API

# AUTH tools for FCs and Leadership
AUTH has several functions for leadership and Fleet Commanders usage. These includes things such as FAT link generation and corporation member tracking. 

> This section is only for players with FC roles or above in the coalition. Normal members are unable to access the management side of these tools.
{.is-info}

## Group management
If you belong to a group that is a manager group for a lower class group you will be able to accept and decline applications from other members to that group.

- Navigate to https://auth.silentcoalition.com/group/management/
- See if there are any applications to any groups.
- If you know the applicant you may accept the application as per your own group rules.
- If you do not know if you should accept the player to the group, then you most likely should not.

## Corporation stats
> This tool is only for CEOs and Directors
{.is-warning}

You can track your corporation member AUTH status and their alts at https://auth.silentcoalition.com/corpstat/

In order to gain access to the tracking you will need to add a director level token to the tool by pressing on the add token.

On corporation status page you can:
- See who is registered on AUTH
- See main char and alt relations
- See service statuses of your members

## Managing fittings and doctrines
All coalition doctrines are located on AUTH in the doctrines section https://auth.silentcoalition.com/fittings/

> CEOs, directors and doctrine managers are able to modify doctrines
{.is-success}

### To add a new doctrine
Click on the add doctrine button. This will create a completely new doctrine.

### To add new fittings
Click on the add fitting button. Copy paste the fitting from ingame in EFT format.

Name the doctrine as `<role> - <usage> - <class>` such as `DPS - Fleet PVP - Omega`

### To modify doctrines
Open a doctrine and click on the yellow edit button. In here you can:

- Add fittings to the doctrine
- Remove fittings from the doctrine
- Edit the doctrine description

### To modify fittings
In order to modfy a fitting inside a doctrine you will need to delete the old fitting and make a new fitting.

> Currently it is not possible to update old fittings. This will be added in the next release of the module.
{.is-warning}

## Generating FATs
If you are a coalition Fleet Commander, Fleet Commander Trainee, CEO or a Director you are able to create FAT links for your fleets. Fat links are used to track member participation in your fleet.

### What fleets qualify for a FAT
Only "proper" fleets qualify for FATs.

Scheduled fleets on AUTH such as: MQP, Roams, War Fleets or PvE fleets inc. incursions qualify for a fat.

Proper flash form fleets as: SLTRN Defence fleet or PvP Roams that you ping on discord with > 5 members in it qualify for a FAT

Mining fleets or small duo pvp fleets do not qualify for FATS.

Only one fat per fleet is allowed

With FAT 2.0 you have a few ways to create links:

> Fats over ESI is your primary method for FAR generation
{.is-info}

### Fats over ESI
1. Have a toon as a fleet boss in your fleet
2. Go to the FAT page: https://auth.silentcoalition.com/bfat/
3. Click on Add FATLink https://auth.silentcoalition.com/bfat/links/add/
4. Click on Add FatLink from ESI
5. Log in with the fleet commander toon and press the green arrow to register the scope
6. Set a name for your fleet! Otherwise it will have a random generated name. All members will be pulled over ESI after a short while.

> If you do not get any errors it means the FAT over ESI worked. It may take some time for the players to show up. Do not create a new fat if there was no errors.
{.is-warning}

### Fat links (not recommended)
1. Go to the FAT page: https://auth.silentcoalition.com/bfat/
2. Click on Add FATLink https://auth.silentcoalition.com/bfat/links/add/
3. Set a name for the fleet and duration time and press Add clickable FATlink
4. Provide the FAT link in fleet

### ESI fat during ESI failures
1. Try create ESI fat, you will get an error!
2. Set a name for the fleet as normally.
3. Open the tab called flat list
4. Go to fleet window ingame and press one of the portraits on the right side of the fleet
5. Press ctrl + a followed by ctrl + c to copy all players in fleet
6. Paste the clipboard to the flat list form and submit it
7. Players in fleet will pop up shortly on the fat!

## Scheduling fleets
You are able to pre schedule fleets and add them to our fleet board. The fleet board is found on AUTH at https://auth.silentcoalition.com/optimer/. Please create a fleet in here whenever you plan to do a planned fleet in the future. You can always cancell the fleet in case you are unable to do it or if no one shows up.

### To create a fleet operation:
1. Go to https://auth.silentcoalition.com/optimer/
1. Check that there are no fleets scheduled to the time you are going to schedule
1. Click on the create fleet button
1. Fill in all needed information

## Discord Fleet Pings
In order to send out a fleet ping on discord please use the ping formatter found on auth https://auth.silentcoalition.com/discordpingformatter/

Coalition aims to keep pings to minimum so that in case we have an actual imporant operation people will pay attention to the pings.

> Please stick to the ping rules as bellow
{.is-warning}

### Ping rules
1. Schedule fleets via https://auth.silentcoalition.com/optimer/. All fleets scheduled in here will automatically be posted in the `#operations` channel on discord. 
1. 30 minutes prior to the fleet timer there will be an automatic notification again on the `#operations` channel
1. When your fleet goes up ping it at the `#fleet-pings` channel with the formatter.
	1. For stratop and CTA fleets use `@here` pings. We want to keep these to minimum
  	2. For every other fleet please pick the correct SIG group from the drop down window on the formatter.

### Pre Pings
For imporant operations you can create a pre ping by ticking the pre ping box on the formatter and selecting the channel to be PRE pings channel `#operations`. In here you can include more details about your fleet.

Do not create any pings and use the `no ping` option for pre fleets unles it is a CTA fleet!











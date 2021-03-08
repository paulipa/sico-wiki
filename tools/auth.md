---
title: AUTH
description: Central access management program
published: true
date: 2021-03-08T06:02:50.256Z
tags: 
editor: markdown
dateCreated: 2020-07-05T17:33:02.063Z
---

# What is AUTH
EVE LinkNet AUTH is a central management system that links your EVE online character by taking advantage of the EVE SSO system to all of our third party services. This way we can identify your ingame character in our systems and restrict any non members out from the system.

You can read more about EVE SSO in here https://support.eveonline.com/hc/en-us/articles/205381192-Single-Sign-On-SSO

We are currently using a modified version of https://gitlab.com/allianceauth/allianceauth

> Using SSO login is perfectly safe. You will be logging in on an official EVE Online page and the page will then let our system know that you are who you claim to be. No account information is shared to us.
{.is-success}

> Our AUTH only requires a public scope that provides us the same information as viewing your profile ingame does. We can't see any of your personal information.
{.is-info}

# Quick setup
1. Register on https://auth.eve-linknet.com
1. Join groups on https://wiki.eve-linknet.com/community/groups
1. Authenticate on discord https://auth.eve-linknet.com/discord/activate/

# Step by step registration
1. Navigate to https://auth.eve-linknet.com
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
1. To add alts under your main so that their activity are counted as activity for your main press the [add character](https://auth.eve-linknet.com/account/characters/add/) button on AUTH dashboard. This will link your alts to your main character.

## Joining Groups
The community has a lot of different types of players with different goals in EVE. Since we do not want to spam you with any content you are not interested in we have created special interest groups, SIGs
![auth6-1400x429.jpg](/auth6-1400x429.jpg =300x)
You can find descriptions of different groups from here: [groups](/en/groups-and-roles/groups)

### Special Interest Groups
By joining the special interest groups you will gain access to the respective discord rooms. In these rooms you will receive notifications about the content related to your interests.

There are a great number of things you might want to focus on in EVE. Amongst other things we have groups created for PvP, Capital ships, incursions, triglavian invasions, mining, pve, wormhole space, hauling, planetary interactions, faction warfare and many other things.

To add yourself to the special interest group simply go to https://auth.eve-linknet.com/groups/ and add yourself to the groups that start with Special Interest by pressing the request button. You will automatically be approved to the group and gain access to the discord channels related to these groups. 

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

## My Characters (Member Audit)
Our AUTH base registration only asks for a public token which doesn't allow us to see any details of your characters. With the Member Audit tool you are able to track your character details outside of the game client and share them with your CEO or corporation recruiters.

> On default your character details are only visible for you, your own corporation CEO and directors.
{.is-info}

To add a detailed tracking token:
- Go to https://auth.eve-linknet.com/member-audit/launcher
- Here you will see a list of all of the characters that you have added when [adding alts](https://wiki.eve-linknet.com/e/en/tools/auth##adding-alts)
- Click on the register button to track a new character
- Log in with SSO and select the correct character
- Click on the green select button to add the token on your account
- After a while AUTH will fetch your character information and you can display it via AUTH by pressing on the green view character button.

### Sharing your details

You are able to share your character details for other CEOs, directors and recruiters who have the roles to see shared member details. This is helpful when you are seeking to join a new corporation that requires an API check for your characters.

> When you share your character details it will be visible for all community CEOs and directors and corporation recruiters with the required role.
{.is-warning}

To start and stop sharing your details:
- Go to the My Characters page https://auth.eve-linknet.com/member-audit/launcher
- Click on the yellow `Enable access to recruiters` button.
- To stop sharing your details click the button again.


# Troubleshooting

## No activation mail
There is no longer activation mails sent. Simply log in after creating your first account.

## I can't see groups
Certain groups are only visible for community members. It may take up to a few hours for your corporation change status to take effect on the API

## I can't see services
Certain services are only visible for community members. It may take up to a few hours for your corporation change status to take effect on the API




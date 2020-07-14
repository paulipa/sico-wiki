---
title: Editing Wiki
description: 
published: true
date: 2020-07-14T18:01:09.190Z
tags: 
editor: markdown
---

# Who can edit the wiki
Only certain people are able to edit the wiki. In order to be able to edit the wiki you will need one of the following roles in the coalition:
- CEO
- Director
- Chief Editor
- Editor

# How to create new pages
You are able to interact, edit and create pages under the path /services which includes stuff like guides, flight manuals and general setting up things that may change over time.

> Complete guide for editing wiki.js is located in here https://docs.requarks.io/guide/pages
{.is-info}

1. Activate the wiki service on AUTH at the services section.
1. Log in to the wiki with your email and the password you got from AUTH
1. To add a new page click on the `add new page` icon on the top right corner
1. Select the `services` folder or type in a path starting with `services`

> You can only add and edit pages starting with /services/
{.is-warning}

5. Type in a path for the page without any special characters or spaces. Replace all spaces with dashes `-`. Such as: `/services/guides/how-to-write-guides`. Please use a proper path such as guides for guides and flight manuals for general content guides.
6. Click on select to select the page
7. Select the `Markdown` text format for all pages you create
8. Give a title for your page
9. Add content and press on the green publish button

> If you are unfamiliar with markdown click on the `?` on the toolbar to get a cheat sheet
{.is-success}

## Adding your page on the navigation site
If you want people to find your page easier you can add it to the navigation menu by:
1. Opening the navigation page such as the guides page
1. Editing the page
2. Adding your page as a link to the page

## Adding spoilers / editing doctrines
To add spoilers for stuff like fittings please add use the following code:
```
<details> 
  <summary>Ferox, DPS - Fleet - Starter</summary>
  [Ferox, DPS - Fleet - Starter]

  Damage Control II
  Magnetic Field Stabilizer II
  Magnetic Field Stabilizer II
  Magnetic Field Stabilizer II

  Large F-S9 Regolith Compact Shield Extender
  Large F-S9 Regolith Compact Shield Extender
  Compact Adaptive Invulnerability Shield Hardener
  Compact Adaptive Invulnerability Shield Hardener
  Small F-RX Compact Capacitor Booster
  50MN Cold-Gas Enduring Microwarpdrive

  250mm Railgun I
  250mm Railgun I
  250mm Railgun I
  250mm Railgun I
  250mm Railgun I
  250mm Railgun I

  Medium Ancillary Current Router I
  Medium Anti-EM Screen Reinforcer I
  Medium Core Defense Field Extender I

  Acolyte I x5
  Caldari Navy Antimatter Charge M x1000
  Cap Booster 200 x25
  Antimatter Charge M x3000
  Caldari Navy Tungsten Charge M x1000
</details>

```

It will look like this
<details> 
	<summary>Ferox, DPS - Fleet - Starter</summary>
[Ferox, DPS - Fleet - Starter]

Damage Control II
Magnetic Field Stabilizer II
Magnetic Field Stabilizer II
Magnetic Field Stabilizer II

Large F-S9 Regolith Compact Shield Extender
Large F-S9 Regolith Compact Shield Extender
Compact Adaptive Invulnerability Shield Hardener
Compact Adaptive Invulnerability Shield Hardener
Small F-RX Compact Capacitor Booster
50MN Cold-Gas Enduring Microwarpdrive

250mm Railgun I
250mm Railgun I
250mm Railgun I
250mm Railgun I
250mm Railgun I
250mm Railgun I

Medium Ancillary Current Router I
Medium Anti-EM Screen Reinforcer I
Medium Core Defense Field Extender I

Acolyte I x5
Caldari Navy Antimatter Charge M x1000
Cap Booster 200 x25
Antimatter Charge M x3000
Caldari Navy Tungsten Charge M x1000
</details>

You can add [doctrines](/community/doctrines) by editing the doctrine page directly. See the curent doctrines for how to structure the fittings.

# How to edit pages
You can edit all pages under the `/services` path by pressing on the big blue edit button.

# Tracking changes
All changes will be stored on git as a backup and posted on the wiki-editors-tracker channel on discord.

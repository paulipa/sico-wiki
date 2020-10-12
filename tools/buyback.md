---
title: Buyback Program
description: How to sell your items to the coalition
published: true
date: 2020-10-12T07:58:08.274Z
tags: 
editor: markdown
dateCreated: 2020-07-06T10:10:46.659Z
---

# Buyback Program
When you join a corporation that is part of the LinkNet community you will get the permission to use our buyback system. This means that you will always be paid according to the current market prices for the items that you are selling to us. 

> You can sell all types of items not just ore at almost all valid buyback locations.
{.is-success}

While random items have a higher tax rate it is most often more time efficient to sell them to buyback compared to spending the time to haul them to the market yourself.

## Why to use the buyback and why is there a tax?
There are several benefits that you will receive by using the LINE buyback system. Not only will it make sure that you are paid enough for your items, it also saves you a huge amount of valuable time as you do not need to move your assets to any hubs to be sold. All the prices we use are coming right from the largest trade hub in EVE: Jita 4-4, which means when you sell items via the system it is like selling your items in Jita. The system is designed to:

- Allow us to buy ore and ice from you based on compressed ore prices instead of raw ore prices. This way you do not have to compress your ore and you still get paid as it would be compressed!
- Save you from training for refining skills or setting up compression arrays as we do this on your behalf!
- Save you a lot of valuable time as all you need to do is drop the items or ores at a station that accepts buyback for your items. These locations are usually also the ones where we provide our other services.
- To get rid of that low value loot that you get from asteroid rats and from missions that is just making your hangars messy while getting paid for them.
- Save you from paying market taxes yourself.

The tax in the buyback is what covers most of the community activities. As we have very little taxation on our community we heavily rely on the tax from buyback to support our activities and to expand our services.

## How does it work
The buyback system is coded on Symfony and it pulls it price data currently from Jita buy orders. 

Price data is updated most often once a day to ensure that the prices you get are as close to the real prices as possible. When calculating prices we will show you how the price is built and what the sell price in Jita would be if you would sell the items yourself. Note that the sell price we show does not include the market taxes you have to pay when selling items in the stations.

The program is privately hosted under our own server and maintained by the Silent Coalition.

# Using the system
The system works by using Contracts. To create a contract you can either select all your items in your hangar and right click and press Create Contract. 

The other way to create contracts is to press the E on your `Neocom -> Business -> Contracts -> Create a contract`. Once you have opened a contract it is time to fill in the right settings.

> The buyback program can be found at: buyback.eve-linknet-com
{.is-info}

## Valid buyback locations and prices
1. We are only buying items at certain core locations to make it easier to haul them. To find out what stations or structures are valid for buyback open the Prices, Taxes & Locations page on the buyback system at https://buyback.eve-linknet.com/prices. You can see all of the valid structures in the Accepted Buyback Locations table. These same locations are also found on the buyback generator location dropdown selection.

> Contracts are only accepted at the exact stations listed as valid buyback locations.
{.is-warning}

![buyback-1-519x400.png](/buyback-1-519x400.png =500x)

2. Items are divided into different categories. You can find the different categories and taxes per the buyback locations from the Taxes and Locations table.

3. Stack all the items that you plan to sell to us. You can stack all items in your inventory by right clicking the inventory and selecting stack all. This will make the output cleaner for you. Note that only repackaged items can be stacked.
![buyback-4-800x280.jpg](/buyback-4-800x280.jpg =500x)

4. Highlight all the items you want to sell to use and press Ctrl – C (it will copy all the ores on your clipboard).
![buyback-5-513x400.jpg](/buyback-5-513x400.jpg =500x)

5. Open our Buyback Center and activate the generator by pressing the calculate prices button. Paste the items to the Item injector text area area by pressing Ctrl – V. Select if you want to donate a portion of the contract value to the corporation and select the location where you are selling yours items at.

6. Press Calculate to calculate the prices for your items.

7. Once calculated you will be able to see the details for each item you are selling. Some items may get their prices calculated based on some refining rules and the best price is selected based on the rules applied at your current location. The price used for each row is highlighted. If there are any errors or items without prices they will show up with red and the explanation for the row can be found down bellow.
![buyback-8-450x400.jpg](/buyback-8-450x400.jpg =500x)

## Creating the buyback contract
Once you have calculated the price for your items you can make a contract to the player mentioned in the Contract Settings box in the previous step.
![buyback-10-507x400.jpg](/buyback-10-507x400.jpg =500x)

1. You still should have all the items highlighted from the previous section but if you do not then make sure you select the same items you used when you calculated the price.

2. Right click on a highlighted items and press create contract.

### Contract settings
The next section will explain to you what you should put in each of the contract fields ingame.

#### Page 1/4
Contract type: will be as default: `Item Exchange`
Availability: will be as `Private`
Name: will be the `Assign to name` (from the calculator)
![buyback-11-558x400.jpg](/buyback-11-558x400.jpg =300x)

#### Page 2/4
Here you will see all the items you have in the current station. The items you selected earlier are checked in this window and there is `no need to do anything on this window`.

#### Page 3/4
I will pay: will be set at `0` (you are not giving us money)
I will receive: Paste the `contract net value` here that you got from the buyback program (Ctrl + V)
Expiration: Set to `2 Weeks`. A longer duration does’t cost you anything extra
Description: Paste the description that has been given to you in the buyback program
![buyback-12-558x400.jpg](/buyback-12-558x400.jpg =300x)

> Description field is mandatory. Without it your contract may be rejected.
{.is-danger}

#### Page 4/4
This page shows you the summary of the contract and the price to create it. All contracts will cost 10 000 isk to set up in EVE. After you are pleased with the confirm page press 'Finish' and your contract will be created.

## After making the contract
Once the contract has been created all you need to do is wait for the money to pop in your wallet. Contracts will be accepted as soon as possible.

If there are any errors in your contract or the price does not match up then the contract will be rejected. To get your items back from a rejected contract open your contract window and look for contracts requiring actions. Then you can re-create the contract with the correct settings.



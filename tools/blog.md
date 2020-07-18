---
title: Blog & Store
description: 
published: true
date: 2020-07-18T05:27:58.440Z
tags: 
editor: markdown
---

# Store vendors
As a vendor you can manage orders via the SiCO web shop just like any normal orders. The homepage shop is running on woocommerce which is one of the most popular shop platforms out there. Combined with a multiseller addon there can be multiple sellers on the platform.

You can only process your own orders and manage the products that have been either created by your or are managed by you. Any orders that have products from multiple vendors will be split up so that you can only see your own products.

# Managing coalition BP orders
The following guide is for the coalition blueprint store managers. You can also refer to it for managing your own items as the process is exactly the same.

## Processing pending orders
In order for you to process orders you will need the vendor role on the homepage. You will get this
from Ikarus Cesaille

1. Navigate to the homepage and log in at www.silentcoalition.com
1. After you have logged in you will see the admin dashboard menu. Hower over the menu and open the dashboard
![store-dashboard.jpg](/store-dashboard.jpg =600x)
1. On the dashboard the only menu you need is the products menu for managing your own products and the orders menu for managing your own orders. If you are managing products that are managed by the coalition you only need to interact with filling up orders and delivering items
![store-dashboard-orders.jpg](/store-dashboard-orders.jpg =400x)
1. When you get a new order you will both receive an email notification and see a new order pop up with a pending status. If your product requires payments then the status will be waiting for payment until the payment has been sent. Once the order status says processing you can start working on delivering the items
![store-processing-order.jpg](/store-processing-order.jpg =400x)
1. You can click on the order title to show the full details of the order or click on the small eye icon to show a summary. Most often all you need is the summary view
![store-show-order-details.jpg](/store-show-order-details.jpg =400x)
1. When you open the summary view you will see the item that has been ordered, the quantity of the items and possibly back order count. If the products you are selling does not track quantities over ESI then there will be no quantities shown. In this case we are managing coalition BPC service so the quantities are always tracked
![store-order-detail-fast-view.jpg](/store-order-detail-fast-view.jpg =400x)
	- If backorders are allowed it means that someone is able to order more items than there is available in stock. This means that the items needs to be built.
1. Once all of the items have been delivered to the client you can click on the complete button.

## Delivering BPC orders
1. Coalition BPC orders track quantities. Each unit equals to one run on the copy. This means that when a player orders 10 quantities you can deliver either 2 x 5 run copies or if no such copies are available you can deliver the next smallest quanity BPC located in hangar, lets say 1 x 20 run copy
1. Open a pending order and view the items
1. If an item doesn’t have a back-ordered number it means that we most likely have enough BPC runs on the storage to cover the order.
![store-order-item.jpg](/store-order-item.jpg =400x)
1. Go to the Industry Tower where the copies are located and open your industry window
![store-industry-window.jpg](/store-industry-window.jpg =400x)
1. Drag and drop the item into your inventory. As you can see in this example we only have 1 x 200 run copy and the client has ordered 1 units. If the BPC is fast to copy like the one in this case we can simply deliver the 200 run copy
1. IF THERE ARE ANY BACK ORDERS ON THE ORDER you want to make copies of those items first and deliver all items in a single contract. As in our case there is back orders for the items we will need to setup a copying order for the printer group
![store-back-order-item.jpg](/store-back-order-item.jpg =400x)
1. Go to the discord printers channel and check the pinned messages. In here you will find the google sheet that we use for printer orders
1. For items that are in back-order simply copy paste the name of the item into the item name field
1. Add quantities in a form of runs x copies. Always order extra runs for blueprints so that you have them ready for the new order. I tend to order 10 x for fast copies and 5 x for slower ones. In our example cases 70 x 100MN Afterburner I Blueprint are missing so i am ordering 5 x 50 runs
1. Ping everyone in the printer channel for a new order
1. If old orders have been completed you can delete them from the sheet. Pretty much all orders that have a vendor marked are good to be deleted.
1. Once the copies have been created you can fulfill the order by finding all needed copies and contracting them over to the client whos name you can see on the order
![store-order-billing.jpg](/store-order-billing.jpg =400x)
1. Once done click on completed to mark the order as completed.
---
title: Discount, gift wrap and shipping estimate
parent: Cart
grand_parent: Customizing
nav_order: 6
permalink: /customizing/cart/extras/
summary: "Discount codes, gift wrap with a message, and a shipping estimate."
thumb: cart/extras.png
thumb_pos: right bottom
---

# Discount, gift wrap and shipping estimate
{: .no_toc }

{% include where.html path="Cart template → Cart section → Add block" %}

Three optional blocks for the cart. Add each one from the **Cart** section:

1. In the page picker, choose **Cart**, then open the **Cart** section.
2. Click **Add block** and choose the block.
3. Drag it to where you want it, for example just above the checkout button.
4. Click **Save**.

1. TOC
{:toc}

![The cart drawer with Discount code, a gift wrap checkbox and Estimate shipping above the subtotal]({{ '/assets/images/cart/extras.png' | relative_url }})

## Discount code

A field where shoppers enter a discount code before checkout. Applied codes are listed, each with a remove button, and the savings show in the subtotal. Codes that don't apply to the cart are rejected with a message.

No settings. Create codes in **Discounts** in your Shopify admin.

## Gift wrap

A **Gift wrap** checkbox. Ticking it adds your gift wrap product to the cart, and an optional field lets the shopper write a gift message.

| Setting | What it does |
|---|---|
| **Gift wrap product** | The product added to the cart. Its title and price appear next to the checkbox |
| **Show gift message field** | Shows a message box once gift wrap is ticked |

Set up a product first, for example "Gift wrap" at $5, and leave **Online Store** as a sales channel. The block stays hidden until you choose a product that's in stock. The gift message is saved on the order and shows in your admin under **Additional details**.

## Shipping estimate

Shoppers choose a country, region and postal code to see your real shipping rates for the items in their cart. Only countries you ship to are listed.

No settings. Rates come from **Settings → Shipping and delivery**.

{: .note }
The shipping estimate needs JavaScript and is hidden for the very few shoppers who have it turned off. The discount code and gift wrap blocks work without it.

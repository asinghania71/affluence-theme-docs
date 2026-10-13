---
title: FAQ
nav_order: 6
permalink: /faq/
---

# FAQ and troubleshooting
{: .no_toc }

1. TOC
{:toc}

## Setup

**I changed my style and lost my settings.**
Choosing a style replaces settings. Duplicate your theme before switching, or pick the style first.

**A section is missing from Add section.**
Some sections only appear on matching pages, such as Product information on product pages.

**How do I change the logo?**
Theme settings → Brand information, and logo width in the Header section.

**How do I update the theme?**
See [Updating the theme](../getting-started/updating/). Editor settings carry over; code edits don't.

**Does Lush work without apps?**
Yes. The wishlist, product ribbons, estimated delivery, custom fields, gift wrap, discount codes and the shipping estimate are all built in. Filters and product recommendations use Shopify's free Search & Discovery app.

## Products and cart

**The wishlist is empty on another device.**
By design the wishlist lives in the browser only. See [Wishlist](../customizing/wishlist/).

**Product ratings are not showing.**
Install a review app that writes `reviews.rating` and `reviews.rating_count` product metafields, then turn on **Show product rating** and/or the **Review widget**.

**The cart's checkout button is greyed out.**
**Require agreement to terms** is on. Shoppers must tick the terms checkbox first. See [Terms checkbox](../customizing/cart/terms-checkbox/).

**Gift wrap isn't showing in the cart.**
Choose a **Gift wrap product** in the block, and make sure it's in stock and available on the Online Store.

**No estimated delivery date.**
Check that **Maximum business days** is equal to or greater than **Minimum business days**.

**The free shipping bar shows the wrong amount.**
The threshold is entered in your store's primary currency. Check your Markets currency rounding settings.

**Prices appear without a currency symbol.**
Currency display follows **Settings → Markets → Currency formatting**.

**The variant picker doesn't update.**
Check that the product has available variants and that no app is changing the product form.

## Navigation

**The heart icon is missing from the header.**
Check that **Theme settings → Wishlist → Enable wishlist** is on. If **Wishlist type** is *Page*, also set **Wishlist page** in the Header section.

**The header isn't transparent on some pages.**
It's only transparent over a Hero, Slideshow or full-width Video at the very top of the page. See [Transparent header](../customizing/header-navigation/transparent-header/).

**The countdown shows 00:00:00.**
The end date has passed. Remove the block or set a new date. It never restarts on its own.

**My mega menu promo isn't appearing.**
The **Menu item** text must exactly match a top-level menu item that has sub-links.

## Still stuck?

See [Support](../support/).

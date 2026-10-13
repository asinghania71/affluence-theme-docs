---
title: Collection pages
parent: Customizing
nav_order: 4
permalink: /customizing/collection-pages/
---

# Collection pages
{: .no_toc }

1. TOC
{:toc}

Choose **Collections → Default collection** in the page picker and open the **Collection products** section. See the [full settings list](../../reference/sections/main-collection/).

![A collection page with filters on the left, a sort menu and a four-column product grid]({{ '/assets/images/collection/page.png' | relative_url }})

![A collection page on a phone, with the Filter and sort button and a two-column grid]({{ '/assets/images/collection/page-mobile.png' | relative_url }}){: .phone}
*On a phone.*

## Banner

Show or hide the collection banner, image and description. Breadcrumbs are turned on or off for the whole store in **Theme settings → Layout → Show breadcrumbs**.

## Grid and pagination

- **Products per page**, and desktop/mobile column counts.
- **Pagination**: numbered pages, a *Load more* button, or infinite scroll. Numbered pages work without JavaScript and are the safest for search engines.
- **Grid density toggle**: lets shoppers switch between a compact and a wide view. Their choice is remembered in their own browser.

## Filtering and sorting

Turn on **Show filtering**, then choose which filters appear in the free **Shopify Search & Discovery** app, under **Filters** (for example availability, price, color and size). **Show sorting** adds a sort menu. Filters and sorting work without JavaScript.

## Product card options

Cards are styled globally in **Theme settings → Product cards**: image ratio, hover effect, corner radius, vendor, rating, color swatches, quick add, quick view, wishlist button and low-stock message. Badges and ribbons are in **Badges** and **Product ribbons**.

![Product cards with a Sale badge, a New ribbon, color swatches and a heart button]({{ '/assets/images/collection/cards.png' | relative_url }})

### Badges

**Theme settings → Badges** sets where sale, sold out and low stock badges sit (**Position**), their shape (**Corner radius**, **Badge style**) and a color pair for each badge type. Turn them all off with **Show badges on product cards**.

### Product ribbons

Ribbons are your own labels, such as "Bestseller" or "New". Set up to six in **Theme settings → Product ribbons**:

1. Pick a free **Ribbon** slot.
2. Choose **Match type**: **Product tag** (shows on products with that exact tag) or **New arrival** (shows for a number of **Days since added**).
3. Enter **Ribbon text** and colors.
4. Click **Save**.

Choose the **Ribbon shape** (**Rounded pill** or **Diagonal ribbon**) and **Maximum ribbons to show at once**. Turn on **Also show on the product page** to show them on the main product image too.

### Review widget

A small star badge on product images, using the standard `reviews.rating` and `reviews.rating_count` product metafields that review apps such as Shopify's own write. Nothing is shown for products without ratings.

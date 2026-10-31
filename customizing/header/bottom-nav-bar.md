---
title: Bottom navigation bar
parent: Header and navigation
grand_parent: Customizing
nav_order: 8
permalink: /customizing/header-navigation/bottom-nav-bar/
summary: "An app-style bar of shortcuts pinned to the bottom of the screen on phones."
---

# Bottom navigation bar

{% include where.html path="Footer group → Bottom navigation bar" styles="On: Affluence, Bloom, Catalog, Noir, Terra · Off: Atelier · Hides on scroll: Bloom · Floating: Bloom, Noir · 90% opacity: Bloom" %}

On phones, the bottom navigation bar stays pinned to the bottom of the screen while shoppers scroll, like the tab bar in a shopping app. On tablets and desktops it is hidden.

![The bottom navigation bar on a phone: Home, Shop, Search, Wishlist, Account and Your bag]({{ '/assets/images/header/bottom-nav-mobile.png' | relative_url }}){: .phone}

Each item is a block:

| Block | What it does |
|---|---|
| **Link** | Goes to any page or collection you choose. Pick an icon, or upload a **Logo** to show instead |
| **Search** | Opens the search panel |
| **Account** | Goes to the sign-in or account page. Hidden if customer accounts are off |
| **Wishlist** | Opens the wishlist, with a count of saved items. Hidden if the wishlist is off |
| **Cart** | Opens the cart, with a count of items |

To change the bar:

1. In the theme editor, scroll to the footer and open **Bottom navigation bar**.
2. Click an item to edit its **Label** and link, drag to reorder, or click **Add block** to add another.
3. Click **Save**.

Search, Account, Wishlist and Cart can each be added once. A **Wishlist** item needs a **Link** to your wishlist page only if the theme's wishlist type is **Page**.

The item for the page a shopper is on is highlighted: Home and Link items on their own page, Search on search results, Account on account pages, and Cart on the cart page.

## Avoid showing the same icon twice

Each of those four items has **Hide in header on mobile**, on by default. It hides the matching icon in the header on phones, so shoppers don't see a search or cart icon twice. The header on desktop is not affected.

Turn it off for an item if you want the icon in both places.

## Other settings

| Setting | What it does |
|---|---|
| **Color scheme** | The bar's colors |
| **Style** | **Full width** sits flush against the screen edge. **Floating** is a rounded bar with space around it. Default is Full width |
| **Opacity** | Lower values let the page show through the bar, softly blurred. 100% is solid. Default is 100% |
| **Show labels** | Shows the text under each icon. When off, labels stay available to screen readers |
| **Hide when scrolling down** | Slides the bar out of the way as shoppers scroll down, and brings it back as soon as they scroll up or reach the bottom of the page. Off by default |

## Turning the bar off

Click the eye icon next to **Bottom navigation bar** to hide it, or remove the section. The header icons you hid return automatically.

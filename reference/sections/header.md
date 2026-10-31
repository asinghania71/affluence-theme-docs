---
title: Header
nav_order: 10
permalink: /reference/sections/header/
grand_parent: Reference
parent: Sections reference
---

# Header
{: .no_toc }

`sections/header.liquid`

Available on: header.

## Settings

**Navigation**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Menu | link_list | main-menu |  |
| Desktop menu | select | bar | Menu icon opens the menu drawer, as on phones. Hidden suits a store where another section, such as Header menu row, shows the menu. Phones always use the menu drawer. Options: Menu bar · Menu icon · Hidden. |
| Show "Shop all" links | checkbox | on | Adds a link to the parent page at the top of each submenu, on desktop and mobile. |
| Customer account menu | link_list | customer-account-main-menu | Shown only when customer accounts are enabled in Settings > Customer accounts. |
| Wishlist page | url |  | Create a page with the "wishlist" template, then link it here. The icon appears once this is set. |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Logo width | range | 140 |  |
| Logo size when scrolled | range | 100 | Logo size after scrolling. 100% keeps the original size. |
| Shrink the header when scrolling | checkbox | off | Makes the header, logo and menu spacing more compact after scrolling. Requires the header to stay visible when scrolling. A logo size of 100% is reduced to 80%. |
| Logo width on mobile | range | 120 |  |
| Layout | select | center | Options: Logo in the center · Logo on the left · Logo in the center, menu split on both sides · Logo above the menu. |
| Keep the header visible when scrolling | checkbox | on |  |
| Hide when scrolling down | checkbox | off | Hides the header when scrolling down and shows it when scrolling up. Requires the header to stay visible when scrolling. |
| Show a divider below the header | checkbox | on |  |
| Show country and language selectors | checkbox | on | Applies to the header and mobile menu. Shown only when more than one country or language is available in Markets. |


**Search**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show search | checkbox | on | Removes the search icon and search drawer from the header when off. The search page remains available. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Cart**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Cart icon shows | select | count | Options: Item count · Item count and total. |


**Mobile menu**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Featured image | image_picker |  | Optional image shown below the links in the mobile menu. |
| Drill-down navigation | checkbox | off | Opens submenus on a new screen with a back button, instead of expanding in place. Recommended for menus with many levels. |
| Show promo tiles | checkbox | on | Shows the dropdown promo tiles under matching items in the mobile menu. |


**Transparent header**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Transparent header | select | off | Places the header over the first section until customers scroll. Best for pages that start with a full-width image. Becomes solid when a header menu row is added. Options: Off · On the home page only · On every page. |
| Transparent color scheme | color_scheme | scheme-1 | Colors used while the header is over the first section. Use a light scheme for dark images. |
| Logo while transparent | image_picker |  | Optional. Shown only while the header is transparent, such as a white logo. Defaults to the main logo. |

## Blocks

#### Mega menu promo


| Setting | Type | Default | Notes |
|---|---|---|---|
| Menu item | text |  | Must exactly match a top-level menu item that has a dropdown. Up to 2 promos can share a menu item and display side by side, in block order. |
| Collection | collection |  | Fills in any blank image, heading or link, and shows a product count. |
| Image | image_picker |  |  |
| Heading | text |  |  |
| Link label | text |  |  |
| Link | url |  |  |

---
title: Shop the look
nav_order: 10
permalink: /reference/sections/shop-the-look/
grand_parent: Reference
parent: Sections reference
---

# Shop the look
{: .no_toc }

`sections/shop-the-look.liquid`

## Settings

**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | inline_richtext |  | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large. |
| Text | richtext |  |  |
| Button label | text |  |  |
| Button link | url |  |  |


**Image**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  |  |
| Mobile image | image_picker |  | Hotspot positions are shared with the desktop image. Use an image with the same framing so hotspots stay aligned. |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Layout | select | image | List and Carousel show products beside the image, or below it on mobile. Selecting a hotspot scrolls to its product. Options: Image only · Image with product list · Image with product carousel. |
| Hotspot style | select | plus | Options: Plus · Numbered · Dot. |
| Show “Add the look to cart” button | checkbox | off | Adds all in-stock products without options in one click. Products with options keep their own Choose options button. |
| Full width | checkbox | off |  |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 24 |  |

## Blocks

#### Hotspot


| Setting | Type | Default | Notes |
|---|---|---|---|
| Product | product |  |  |
| Dot color | color | #FFFFFF |  |
| Horizontal position | range | 50 | Distance from the left edge of the image. |
| Vertical position | range | 50 | Distance from the top edge of the image. |

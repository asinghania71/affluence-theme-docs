---
title: Promo grid
nav_order: 10
permalink: /reference/sections/promo-grid/
grand_parent: Reference
parent: Sections reference
---

# Promo grid
{: .no_toc }

`sections/promo-grid.liquid`

Up to **8** blocks.

## Settings

**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Overline | text |  |  |
| Heading | inline_richtext |  | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large. |
| Description | richtext |  |  |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Layout | select | feature_left | Options: Equal tiles · Large first tile, left · Large first tile, right. |
| Columns on desktop | range | 3 | Applies to the Equal tiles layout. |
| Tile height | select | medium | Options: Small · Medium · Large. |
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

#### Tile


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  | Without an image, the tile shows a solid background in its color scheme. |
| Image overlay opacity | range | 30 | Darkens the image to keep text readable. |
| Overline | text | New season |  |
| Heading | inline_richtext | Promotion heading |  |
| Text | richtext |  |  |
| Button label | text | Shop now | Leave blank to link the heading instead. |
| Link | url |  |  |
| Content position | select | bottom | Options: Top · Middle · Bottom. |
| Content alignment | select | left | Options: Left · Center. |
| Color scheme | color_scheme | scheme-2 | Used when the tile has no image. |

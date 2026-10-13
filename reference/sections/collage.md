---
title: Collage
nav_order: 10
permalink: /reference/sections/collage/
grand_parent: Reference
parent: Sections reference
---

# Collage
{: .no_toc }

`sections/collage.liquid`

Up to **5** blocks.

## Settings

**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Overline | text |  |  |
| Heading | inline_richtext | Shop the edit | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large · Extra large · Extra extra large. |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Large tile position (desktop) | select |  | Applies only when a tile is set to "Larger tile". Options: Follow block order · Left · Right. |
| Mobile layout | select | collage | Options: Collage · Single column. |


**Product cards**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image ratio | select |  | Adapt keeps each product's original aspect ratio. Portrait and Square crop images to fit. Options: Use theme setting · Adapt · Portrait · Square. |
| Vendor | select |  | Options: Use theme setting · Show · Hide. |
| Rating | select |  | Options: Use theme setting · Show · Hide. |
| Badges | select |  | Options: Use theme setting · Show · Hide. |
| Show review widget | checkbox | on | Displays the product's star rating on its image when ratings are available from a product reviews app. Customize it in Theme settings > Review widget. |
| Review widget size | select |  | "Use theme setting" applies the size set in Theme settings > Review widget. Options: Use theme setting · Small · Medium · Large. |


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
| Content | select | image | Product tiles use the product's image and title. The image and caption settings below are ignored. Options: Image · Product. |
| Larger tile | checkbox | off | If more than one tile is marked, only the first is shown larger. |
| Image | image_picker |  |  |
| Caption | text |  |  |
| Link | url |  |  |
| Product | product |  |  |

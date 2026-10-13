---
title: Store locations
nav_order: 10
permalink: /reference/sections/store-locations/
grand_parent: Reference
parent: Sections reference
---

# Store locations
{: .no_toc }

`sections/store-locations.liquid`

Up to **12** blocks.

## Settings

**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Overline | text |  |  |
| Heading | inline_richtext | Visit us | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large. |
| Description | richtext |  |  |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Map | select | link | Embedded maps load content from Google, which may set cookies. Map image uses each location's image. Options: Directions link only · Embedded Google map · Map image. |
| Columns on desktop | range | 3 |  |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 24 |  |

## Blocks

#### Location


| Setting | Type | Default | Notes |
|---|---|---|---|
| Store name | text | Flagship store |  |
| Address | textarea | 1 Market Street San Francisco, CA 94105 |  |
| Opening hours | richtext | <p>Mon–Sat 10:00–19:00<br>Sun 11:00–17:00</p> |  |
| Phone | text |  | Displayed as a tap-to-call link. |
| Map search | text |  | Optional. What to search on the map, if different from the address. |
| Image | image_picker |  | Shown on the card. With Map image selected, upload a map here. |

---
title: Shoppable shorts
nav_order: 10
permalink: /reference/sections/shoppable-shorts/
grand_parent: Reference
parent: Sections reference
---

# Shoppable shorts
{: .no_toc }

`sections/shoppable-shorts.liquid`

## Settings

**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | inline_richtext |  | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large. |
| Alignment | select | left | Options: Left · Center · Right. |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Layout | select | scroll | Options: Scrolling row · Carousel with arrows · Centered focus. |
| Columns on desktop | range | 4 | Sets the number of videos visible on desktop. On mobile, videos always scroll with the next one partially visible. |
| Full width | checkbox | off |  |


**Features**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Full-screen viewer | checkbox | on | Adds a button that opens uploaded videos full screen, with swiping between videos and the product below. |
| Wishlist heart | checkbox | off | Shows a wishlist button beside the product below each video. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 24 |  |

## Blocks

#### Short


| Setting | Type | Default | Notes |
|---|---|---|---|
| Video | video |  | Shown in a 9:16 vertical frame. Use a vertical video to avoid cropping. |
| YouTube or Vimeo link | url |  | Used when no video is uploaded. Enter a full YouTube or Vimeo link. Always plays muted and looping, with the platform's own controls. |
| Caption | text |  |  |
| Badge | text |  | Short label over the video, such as "New" or "Behind the scenes". |
| Product below video | product |  | Shows the product's image, price and add to cart button below the video. |
| Crop to fill | checkbox | off | On crops the image to fill the space. Off shows the full image, with empty space if its shape differs. |

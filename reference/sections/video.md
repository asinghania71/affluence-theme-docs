---
title: Video
nav_order: 10
permalink: /reference/sections/video/
grand_parent: Reference
parent: Sections reference
---

# Video
{: .no_toc }

`sections/video.liquid`

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Video | video |  |  |
| Video URL | video_url |  | Used when no video is uploaded. Supports YouTube and Vimeo. |
| Cover image | image_picker |  | Shown only for YouTube or Vimeo videos without autoplay. |
| Crop to fill | checkbox | off | On crops the image to fill the space. Off shows the full image, with empty space if its shape differs. |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Autoplay, muted | checkbox | off | Plays automatically, muted and without controls. When off, a cover image with a play button is shown. |
| Loop video | checkbox | on | Applies to uploaded videos. Restarts the video when it ends. |
| Aspect ratio | select | widescreen | Options: Widescreen (16:9) · Landscape (4:3) · Square (1:1). |
| Content width | select | full | Options: Full width · Wide · Narrow. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 24 |  |

## Blocks

#### Theme blocks
Accepts any of Lush's reusable [theme blocks](../../blocks/) (heading, text, button, icon, and more).


#### App blocks
Accepts blocks from installed Shopify apps.

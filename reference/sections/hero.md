---
title: Hero
nav_order: 10
permalink: /reference/sections/hero/
grand_parent: Reference
parent: Sections reference
---

# Hero
{: .no_toc }

`sections/hero.liquid`

Up to **6** blocks.

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  | Fills the height set below. Portrait images work best in the Split layout. |
| Mobile image | image_picker |  | Optional. Defaults to the image above. |
| Video | video |  | Plays muted and looping in place of the image, with a pause button. The image is shown as the poster and for customers who prefer reduced motion. |
| Image corner tag | text |  | Optional. A short label on the image's top-left corner, such as a season or collection name. Shown only in the Split layout on desktop. |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Layout | select | split | Options: Image beside text · Text over image. |
| Vertical position | select | bottom | Position of text over the image. Applies to the Full layout, and to the Split layout on mobile. Options: Top · Middle · Bottom. |
| Horizontal position | select | left | Options: Left · Center · Right. |
| Text alignment | select | left | Options: Left · Center · Right. |
| Text column position (desktop) | select | middle | Options: Top · Middle · Bottom. |
| Height | range | 90 | Percentage of the screen height. |
| Image overlay opacity | range | 55 | Darkens the image to keep text readable. |
| Overlay direction | select | auto | Sets which side of the image the overlay is darkest. Even applies a uniform overlay. Options: Follow text position · Bottom up · Top down · Left to right · Right to left · Even. |
| Scroll effect | select | none | Moves the image as the section scrolls out of view. Disabled for customers who prefer reduced motion. Options: None · Slow zoom · Parallax. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |

## Blocks

#### Overline


| Setting | Type | Default | Notes |
|---|---|---|---|
| Text | text | Overline |  |


#### Heading


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | inline_richtext | A statement worth making | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large · Extra large · Extra extra large. |


#### Text


| Setting | Type | Default | Notes |
|---|---|---|---|
| Text | richtext | <p>Add a sentence or two of supporting copy here.</p> |  |
| Style | select | body | Options: Body · Subdued · Label. |


#### Button


| Setting | Type | Default | Notes |
|---|---|---|---|
| Button label | text | Shop now |  |
| Button link | url |  |  |
| Style | select | primary | Options: Solid · Outline. |


#### Group


| Setting | Type | Default | Notes |
|---|---|---|---|
| Direction | select | group--horizontal | Options: Horizontal · Vertical. |


#### Icon with text


| Setting | Type | Default | Notes |
|---|---|---|---|
| Direction | select | horizontal | Options: Horizontal · Vertical. |


**Item 1**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Icon | select | truck | Options: Star · Heart · Shield · Truck · Return · Badge check · Globe · Tag · Check. |
| Text | inline_richtext | Free shipping over $150 |  |


**Item 2**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Icon | select | return | Options: Star · Heart · Shield · Truck · Return · Badge check · Globe · Tag · Check. |
| Text | inline_richtext | 30-day returns |  |


**Item 3**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Icon | select | shield | Options: Star · Heart · Shield · Truck · Return · Badge check · Globe · Tag · Check. |
| Text | inline_richtext | Secure checkout |  |


#### App blocks
Accepts blocks from installed Shopify apps.

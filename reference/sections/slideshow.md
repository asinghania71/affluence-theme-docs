---
title: Slideshow
nav_order: 10
permalink: /reference/sections/slideshow/
grand_parent: Reference
parent: Sections reference
---

# Slideshow
{: .no_toc }

`sections/slideshow.liquid`

Up to **6** blocks.

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Height | range | 90 | Percentage of the screen height. |


**Navigation**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show arrows | checkbox | on |  |
| Show dots | checkbox | on |  |
| Navigation style | select | dots | Options: Dots · Progress bar. |
| Autoplay | checkbox | on |  |
| Change slides every | range | 5 |  |
| Loop slides | checkbox | on | When off, slides stop at the first and last slide, and autoplay ends on the last slide. |
| Transition | select | slide | Options: Slide · Fade. |
| Image motion | select | none | Slowly zooms the active slide's image. Disabled for customers who prefer reduced motion. Options: None · Slow zoom. |
| Animate text in | checkbox | off | Animates text in as each slide appears. Disabled for customers who prefer reduced motion. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |

## Blocks

#### Slide


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  |  |
| Mobile image | image_picker |  | Optional portrait image for mobile. Defaults to the main image. |
| Video | video |  | Plays muted and looping while this slide is active, with the image as its poster. Not played for customers who prefer reduced motion. |
| Overline | text |  |  |
| Heading | inline_richtext | Slide heading | Italicized words display upright in the accent color. |
| Heading size | select | h0 | Options: Small · Medium · Large. |
| Text | richtext |  |  |
| Button label | text |  |  |
| Button link | url |  |  |
| Second button label | text |  |  |
| Button link | url |  |  |
| Second button style | select | outline | Options: Outline · Solid. |


**Content position**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Vertical position | select | bottom | Options: Top · Middle · Bottom. |
| Horizontal position | select | left | Options: Left · Center · Right. |
| Text alignment | select | left | Options: Left · Center · Right. |
| Show background behind text | checkbox | off | Improves text readability over bright or busy images. |


**Image**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Crop to fill | checkbox | off | On crops the image to fill the space. Off shows the full image, with empty space if its shape differs. |
| Image overlay opacity | range | 0 | Adds extra darkening over the default gradient. Useful for bright images. |
| Overlay direction | select | bottom | Sets which side of the image the overlay is darkest. Even applies a uniform overlay. Options: Follow text position · Bottom up · Top down · Left to right · Right to left · Even. |
| Time on this slide | range | 0 | Set to 0 to use the section's autoplay speed. |

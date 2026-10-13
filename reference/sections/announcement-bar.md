---
title: Announcement bar
nav_order: 10
permalink: /reference/sections/announcement-bar/
grand_parent: Reference
parent: Sections reference
---

# Announcement bar
{: .no_toc }

`sections/announcement-bar.liquid`

Up to **6** blocks. Available on: header.

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Display | select | marquee | Static shows the first announcement only. Scrolling moves continuously through all announcements. Rotating shows one at a time, with previous and next arrows. Options: Static · Scrolling · Rotating. |
| Transition | select | fade | Options: Fade · Slide. |
| Time per announcement | range | 5 |  |
| Scroll direction | select | left | Options: Right to left · Left to right. |
| Start playing | checkbox | on | Applies to scrolling and rotating. When off, the bar starts paused and the pause button is always shown. |
| Show dismiss button | checkbox | off | Lets customers close the bar for the rest of their session. |
| Scroll duration | range | 40 | Longer durations scroll more slowly. Disabled for customers who prefer reduced motion. |
| Show pause button | checkbox | on | Applies to scrolling only. Recommended when the bar scrolls for more than 5 seconds, to meet accessibility guidelines. Scrolling also pauses on hover and focus. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-4 |  |

## Blocks

#### Announcement


| Setting | Type | Default | Notes |
|---|---|---|---|
| Text | inline_richtext | Complimentary shipping on orders over $150 |  |
| Link | url |  |  |
| Icon | select | none | Options: None · Truck · Tag · Star · Heart · Shield · Return · Box · Plane · Lightning bolt. |


#### Countdown


> A real, fixed deadline — the same for every visitor, and it never auto-extends. Set both a date and a time below to turn it on.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Label text | text | Sale ends in |  |
| End date | text |  | Format: YYYY-MM-DD |
| End time | text |  | 24-hour format: HH:MM |

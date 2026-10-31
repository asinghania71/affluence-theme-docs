---
title: Countdown banner
nav_order: 10
permalink: /reference/sections/countdown-banner/
grand_parent: Reference
parent: Sections reference
---

# Countdown banner
{: .no_toc }

`sections/countdown-banner.liquid`

## Settings

> Counts down to a real, fixed deadline — the same for every visitor, never extended. Once it passes, the section hides itself.


| Setting | Type | Default | Notes |
|---|---|---|---|
| End date | text |  | Format: YYYY-MM-DD |
| End time | text |  | 24-hour format: HH:MM |
| Time zone (UTC offset) | text |  | Optional, for example +05:30 or -08:00. Leave blank to use your store's time zone. |


**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Overline | text | Limited time |  |
| Heading | inline_richtext | The seasonal sale ends soon | Italicized words display upright in the accent color. |
| Heading size | select | h1 | Options: Small · Medium · Large · Extra large · Extra extra large. |
| Text | richtext |  |  |
| Button label | text | Shop the sale |  |
| Button link | url |  |  |
| Content alignment | select | center | Options: Left · Center. |


**Background image**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background image | image_picker |  |  |
| Image overlay opacity | range | 40 | Darkens the image to keep text readable. |
| Image height | select | adapt | Options: Adapt to content · Small · Medium · Large. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-2 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 48 |  |

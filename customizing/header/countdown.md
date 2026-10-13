---
title: Countdown timer
parent: Header and navigation
grand_parent: Customizing
nav_order: 2
permalink: /customizing/header-navigation/countdown/
summary: "Count down to the real end of a sale."
thumb: header/countdown.png
thumb_pos: center top
---

# Countdown timer

{% include where.html path="Header group → Announcement bar → Add block → Countdown" styles="Included in all six styles" %}

Count down to the real end of a sale, in the announcement bar.

1. Open the **Announcement bar** section.
2. Click **Add block → Countdown**.
3. Enter **Label text**, for example "Sale ends in".
4. Enter **End date** as `YYYY-MM-DD`, for example `2026-11-30`.
5. Enter **End time** on a 24-hour clock, for example `23:59`.
6. Click **Save**.

![The announcement bar reading "Sale ends in 3d 04:12:55"]({{ '/assets/images/header/countdown.png' | relative_url }})

The timer only starts once both the date and the time are filled in. It counts to your store's time zone (**Settings → General**), so every shopper sees the same deadline, wherever they are.

{: .important }
Only use the countdown for a deadline you'll honor. It never restarts or extends itself: when time runs out it shows `00:00:00`. Remove the block or change the date once the sale is over.

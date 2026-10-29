---
title: Estimated delivery
parent: Product pages
grand_parent: Customizing
nav_order: 5
permalink: /customizing/product-pages/estimated-delivery/
summary: "A delivery date range worked out from your own shipping times."
thumb: product/estimated-delivery.png
---

# Estimated delivery

{% include where.html path="Product template → Product information → Estimated delivery date block" styles="Included in all five styles" %}

Show a delivery window such as "Estimated delivery Oct 16–Oct 21", worked out from your own processing and shipping times.

1. Open **Products → Default product → Product information**.
2. Add the **Estimated delivery date** block.
3. Fill in the settings below, then click **Save**.

| Setting | Example | What it does |
|---|---|---|
| **Order-by cutoff time** | `14:00` | Orders after this time (24-hour clock) count from the next day. Leave blank to ignore |
| **Non-shipping days** | `0,6` | Days you don't ship: 0 = Sunday to 6 = Saturday. The default skips weekends |
| **Minimum business days** | `2` | Fastest delivery |
| **Maximum business days** | `5` | Slowest delivery. Must be equal to or higher than the minimum |
| **Date format** | `%b %d` | How dates are written. `%b %d` gives "Jan 5" |
| **Message** | `Estimated delivery [start]–[end]` | Keep `[start]` and `[end]` |

![The buy buttons with an estimated delivery date range below them]({{ '/assets/images/product/estimated-delivery.png' | relative_url }})

{: .important }
This is an estimate from the numbers you enter, not a carrier promise. Keep it realistic, and update it before holidays.

**Nothing showing?** Check that **Maximum business days** isn't lower than **Minimum business days**.

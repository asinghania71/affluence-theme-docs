---
title: Free shipping bar
parent: Cart
grand_parent: Customizing
nav_order: 2
permalink: /customizing/cart/free-shipping-bar/
---

# Free shipping bar

Show shoppers how much more they need to spend to get free shipping. The bar fills as they add items and changes color once they qualify.

![The free shipping bar partly filled, reading "Spend $5.91 more for free shipping"]({{ '/assets/images/cart/shipping-bar.png' | relative_url }})

1. In the page picker, choose **Cart**, then open the **Cart** section.
2. Select the **Free shipping bar** block. If it isn't there, click **Add block → Free shipping bar**.
3. Enter **Free shipping threshold** as a number without a currency symbol, for example `150`.
4. Edit **Progress message**. Keep `[amount]` where the remaining amount should appear.
5. Edit **Unlocked message**, which shows once the cart reaches the threshold.
6. Click **Save**.

| Setting | What it does |
|---|---|
| **Free shipping threshold** | Order value that unlocks free shipping. Set to `0` to hide the bar |
| **Progress message** | Text while the cart is below the threshold |
| **Unlocked message** | Text once the threshold is reached |
| **Progress bar track**, **Progress bar fill**, **Progress bar when complete** | The three bar colors |

{: .important }
The bar only shows a message. To actually charge $0 for shipping, set up a free shipping rate in **Settings → Shipping and delivery** with the same minimum order amount.

{: .note }
Enter the threshold in your store's main currency. Shoppers in other markets see it converted. If the converted amount looks wrong, check the rounding rules in **Settings → Markets**.

**Related:** [Cart recommendations](../recommendations/) can suggest a product that unlocks free shipping.

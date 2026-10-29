---
title: Terms checkbox
parent: Cart
grand_parent: Customizing
nav_order: 5
permalink: /customizing/cart/terms-checkbox/
summary: "Require customers to accept your terms before checkout."
thumb: cart/terms.png
---

# Terms checkbox

{% include where.html path="Theme settings → Cart → Require agreement to terms" styles="On in Atelier" %}

Require customers to tick a box agreeing to your terms before they can check out.

1. Open **Theme settings → Cart**.
2. Turn on **Require agreement to terms**.
3. Optional: write your own **Agreement text**, and add a link to any page. Leave it blank to use a standard sentence that links to your terms of service.
4. Click **Save**.

![A checkbox reading "I agree to the terms and conditions" above a greyed-out checkout button]({{ '/assets/images/cart/terms.png' | relative_url }})

While the box is unticked, the checkout button is disabled and accelerated checkout buttons (Shop Pay, PayPal and others) are hidden, so shoppers can't skip it.

{: .important }
Add your terms first in **Settings → Policies → Terms of service**, so the default text can link to them. Without a policy, the checkbox reads "I agree to the terms and conditions" with no link.

{: .note }
The checkbox applies to the cart drawer and the cart page. Buy buttons on product pages go straight to checkout and aren't covered. If you need the agreement everywhere, turn off **Show accelerated checkout buttons** in the product page's **Buy buttons** block.

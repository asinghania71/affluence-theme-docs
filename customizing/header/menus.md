---
title: Menus and dropdowns
parent: Header and navigation
grand_parent: Customizing
nav_order: 5
permalink: /customizing/header-navigation/menus/
summary: "Build menus and dropdowns, and add promo images."
thumb: header/mega-menu.png
---

# Menus and dropdowns

{% include where.html path="Shopify admin → Content → Menus, then Header → Menu" %}

## Build the menu

Menus are edited in your Shopify admin, not the theme editor.

1. Go to **Content → Menus** and open **Main menu**.
2. Add top-level links. To create a dropdown, drag links underneath a top-level link to nest them.
3. Click **Save menu**.

In the theme editor, open the **Header** section and check that **Menu** is set to **Main menu**.

**Show "Shop all" links** (on by default) adds a link to the parent page at the top of every dropdown, for example "Shop all Skincare".

## Add a promo image to a dropdown

1. In the **Header** section, click **Add block → Mega menu promo**.
2. In **Menu item**, type the name of a top-level link that has a dropdown, exactly as it appears in the menu, for example `Skincare`.
3. Either choose a **Collection**, which fills the image, heading and link for you, or enter your own **Image**, **Heading**, **Link label** and **Link**.
4. Click **Save**.

![An open dropdown with its links on the left and two collection promo tiles on the right]({{ '/assets/images/header/mega-menu.png' | relative_url }})

Up to two promos can share a menu item. They sit side by side, in block order.

{: .note }
**Promo not showing?** The **Menu item** text must exactly match a top-level link that has sub-links, including capital letters.

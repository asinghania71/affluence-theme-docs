---
title: Popups, alerts and extras
parent: Customizing
nav_order: 12
permalink: /customizing/popups-and-alerts/
summary: "Age verifier, promo popup, back-in-stock requests, pre-order, back to top and more."
---

# Popups, alerts and extras
{: .no_toc }

## Age verifier

{% include where.html path="Customize → Footer group → Add section → Age verifier" %}

Shows a full-screen gate on a visitor's first visit. Visitors choose **Confirm** or are sent to your **Exit link**. Escape and clicking outside do not close it. Their choice is remembered in their browser for the number of days you set.

It confirms age but does not verify identity, and it needs JavaScript. It is not added by default, because it covers the whole page on first visit.

![The age verifier over the home page, with a heading, short text and two buttons]({{ '/assets/images/extras/age-verifier.png' | relative_url }})

![The age verifier on a phone]({{ '/assets/images/extras/age-verifier-mobile.png' | relative_url }}){: .phone}

## Promo popup

{% include where.html path="Customize → Footer group → Add section → Promo popup" %}

An announcement dialog with an image, heading, text, an optional email signup and an optional button. Choose **Open**: *After a delay* or *On exit intent* (the pointer leaving the top of the window; touch screens use the delay). After a visitor closes it, it stays away for **Show again after** days. It never opens on top of another dialog.

In the theme editor, select the section to preview the popup.

![The promo popup open over the home page, with a heading, text and an email field]({{ '/assets/images/extras/promo-popup.png' | relative_url }})

![The promo popup on a phone]({{ '/assets/images/extras/promo-popup-mobile.png' | relative_url }}){: .phone}

## Back-in-stock requests

{% include where.html path="Product page → Add block → Back in stock alert" %}

While the selected variant is sold out, the block shows **Notify me when available** and an email field. Shopify's contact form sends each request to your store email, with the product, variant and link. No app is needed. You send the restock email yourself.

![A sold-out product with the Notify me when available button and an email field open below it]({{ '/assets/images/extras/back-in-stock.png' | relative_url }})

![The back-in-stock form on a phone]({{ '/assets/images/extras/back-in-stock-mobile.png' | relative_url }}){: .phone}

## Pre-order

When a variant tracks inventory, is out of stock and still allows purchase ("Continue selling when out of stock"), the Add to cart button reads **Pre-order** on the product page, the sticky bar and quick add. There is nothing to set up.

## Back to top

{% include where.html path="Theme settings → Layout → Show back to top button" styles="On: Affluence, Catalog" %}

A round button appears after the visitor scrolls past one screen. It moves up out of the way of the sticky add-to-cart bar.

![The back to top button, a round button in the bottom-right corner after scrolling]({{ '/assets/images/extras/back-to-top.png' | relative_url }})

![The back to top button on a phone, above the bottom navigation bar]({{ '/assets/images/extras/back-to-top-mobile.png' | relative_url }}){: .phone}

## Sign in with Shop

{% include where.html path="Customize → Sign in page → Show Sign in with Shop button" %}

Adds the Shop sign-in button under the login form. Shopify shows it only when Shop sign-in is turned on for your store.

## Collection navigation links

{% include where.html path="Collection page → Navigation menu" %}

Pick a menu and its links show as a row above the products, so shoppers can move between related collections.

## Press coverage and lookbook

Add the **Press coverage** section to list publications with a logo or name, a quote and a link. Only add coverage that really exists. Add the **Lookbook** section for a mosaic of images, each linking to a collection or product; set a block to *Tall* or *Wide* to shape the mosaic. Lookbook: Atelier.

![The lookbook section: a mosaic of four photos, one tall and one wide, each with a title]({{ '/assets/images/extras/lookbook.png' | relative_url }})

![The lookbook on a phone]({{ '/assets/images/extras/lookbook-mobile.png' | relative_url }}){: .phone}

![The press coverage section: three publications, each with a short quote]({{ '/assets/images/extras/press-coverage.png' | relative_url }})

## Ingredients, usage and nutrition

Use a **Collapsible row** for ingredients or usage (pick a metafield with the **Connect** button on its text to fill it per product) and a **Specifications** block for a nutrition table.

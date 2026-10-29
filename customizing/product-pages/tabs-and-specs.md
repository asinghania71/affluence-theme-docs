---
title: Tabs, specifications and pop-ups
parent: Product pages
grand_parent: Customizing
nav_order: 6
permalink: /customizing/product-pages/tabs-and-specs/
summary: "Tabs, accordions, specification lists and size-guide pop-ups."
thumb: product/tabs.png
---

# Tabs, specifications and pop-ups
{: .no_toc }

{% include where.html path="Product template → Product information → Tabs, Specifications or Pop-up block" styles="Specifications: Terra" %}

1. TOC
{:toc}

## Collapsible rows

A **Collapsible row** is an accordion: a heading that opens to show text. Use it for shipping, returns or care instructions.

- **Heading** and **Text**: what the row shows.
- **Page content**: also shows a page from **Online Store → Pages**. Use this for content shared across products, so you only edit it once.

## Tabs

Add a **Tabs** block, then add collapsible rows inside it. On desktop each row becomes a tab. On phones they stay collapsible rows, which are easier to use on a small screen.

![Specifications, What's in the box and Warranty tabs, with the Specifications tab open showing a list of details]({{ '/assets/images/product/tabs.png' | relative_url }})

![On a phone, tabs turn into collapsible rows]({{ '/assets/images/product/tabs-mobile.png' | relative_url }}){: .phone}
*On a phone.*

## Specifications

A neat two-column list of details such as material, dimensions and care.

1. Add a **Specifications** block. It can sit on its own or inside a collapsible row or tab.
2. Give it an optional **Heading**.
3. Edit the rows inside. Each has a **Label** and a **Value**.

To show different values for each product, connect a row's **Value** to a product metafield (the database icon next to the field). Rows whose metafield is empty are hidden, so one block works for every product.

## Pop-up (size guide)

A link that opens content in a window, most often a size chart.

| Setting | What it does |
|---|---|
| **Link label** | For example "Size guide" |
| **Icon** | **Ruler**, **Info**, **Truck**, **Return** or none |
| **Page** | The page to show in the pop-up |
| **Text** | Shown when no page is set, or above the page |

{: .note }
Different size charts for different products: create a product metafield of type **Page**, fill it in on each product, and connect the pop-up's **Page** setting to it. Products without a chart don't show the link.

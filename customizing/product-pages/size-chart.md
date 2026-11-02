---
title: Size chart
parent: Product pages
grand_parent: Customizing
nav_order: 8
permalink: /customizing/product-pages/size-chart/
summary: "A size chart that opens beside the product, with an inches/centimeters switch."
thumb: product/size-chart.png
---

# Size chart

{% include where.html path="Product template → Product information → Size chart block" styles="Included in Atelier" %}

Add a link, such as "Size chart", next to the size picker. It opens a window with your measurements. Shoppers can switch between inches and centimeters, tap a row to choose that size, and read how to measure themselves.

1. Open **Products → Default product → Product information**.
2. Add the **Size chart** block and drag it just below the size picker.
3. Type your chart in the **Size chart** box, one row per line, with columns separated by `|` and the heading row first. For example:

```
Size | Chest | Waist | Hips
S | 86 | 68 | 94
M | 92 | 74 | 100
L | 98 | 80 | 106
```

4. Set **Unit used in the chart** to the unit you typed, then click **Save**.

![The size chart window on a product: product heading, Size chart and How to measure tabs, an in/cm switch and a table with a selectable row for each size]({{ '/assets/images/product/size-chart.png' | relative_url }})

| Setting | What it does |
|---|---|
| **Link label** | The text of the link, for example "Size chart" |
| **Icon** | **Ruler**, **Info** or none |
| **Size chart** | The chart, one row per line, columns separated by `\|`. The first column is the size, and it should read the same as your size options (S, M, L) so tapping a row can select it |
| **Unit used in the chart** | **Inches** or **Centimeters**. The window offers the other unit too |
| **Show the product in the sheet** | Shows the product's image, name and price at the top of the window |
| **How to measure (text)** | Instructions for taking measurements. Adds a second tab |
| **How to measure (image)** | An optional illustration for the second tab |

**Different chart for different products:** create a product metafield of type **Multi-line text**, put each product's chart in it, and connect the **Size chart** setting to it. Products without a chart don't show the link.

{: .note }
Sold-out sizes are crossed out in the chart but stay selectable, the same as in the size picker. Rows that don't match any size option can't be selected.

**Nothing showing?** Check that each line has at least one `|`, and that the product has a chart (or a metafield value) to show.

---
title: Variant picker
parent: Product pages
grand_parent: Customizing
nav_order: 2
permalink: /customizing/product-pages/variant-picker/
summary: "Show options as swatches, buttons or a dropdown."
thumb: product/variant-picker.png
---

# Variant picker

{% include where.html path="Product template → Product information → Variant picker block" %}

The **Variant picker** block shows a product's options, such as size and color.

1. Open **Products → Default product → Product information**.
2. Select the **Variant picker** block.
3. Choose a **Style** and a **Swatch shape**.
4. Click **Save**.

| Style | What shoppers see |
|---|---|
| **Automatic** (recommended) | Swatches for options that have swatch colors or images, buttons for the rest, and a dropdown for more than 8 values |
| **Buttons** | Every option as text buttons, including colors |
| **Dropdown** | Every option as a dropdown. Good for long lists |

![Color options shown as buttons, with sold-out colors struck through]({{ '/assets/images/product/variant-picker.png' | relative_url }})

## Set up color swatches

Swatches use the colors and images you set on the product's options in the admin:

1. Open the product in **Products**.
2. In **Variants**, click the option (for example **Color**) and connect it to a category metafield such as **Color**.
3. Give each value a color or an image.

Sold-out combinations are crossed out but stay selectable, so shoppers can still see the price and images.

{: .note }
Swatches on product cards are controlled separately in **Theme settings → Product cards → Show color swatches**.

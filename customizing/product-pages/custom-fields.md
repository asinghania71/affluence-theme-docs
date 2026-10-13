---
title: Custom fields
parent: Product pages
grand_parent: Customizing
nav_order: 4
permalink: /customizing/product-pages/custom-fields/
---

# Custom fields

Collect information from shoppers, such as an engraving, a monogram or a gift message. What they enter is saved with the cart item and shows on the order in your admin. It doesn't change the price.

1. Open **Products → Default product → Product information**.
2. Click **Add block → Custom field** and drag it above **Buy buttons**.
3. Set it up:

| Setting | What it does |
|---|---|
| **Field type** | **Single-line text**, **Multi-line text**, **Checkbox** or **Dropdown** |
| **Label** | The question, for example "Engraving". Also used as the name on the order |
| **Placeholder** | Example text inside an empty field |
| **Choices** | For dropdowns: the options, separated by commas |
| **Character limit** | Maximum length. `0` means no limit |
| **Required** | Shoppers must fill it in before adding to cart |

4. Click **Save**.

![A Gift message text box and a Card design dropdown above the quantity and Add to bag button]({{ '/assets/images/product/custom-field.png' | relative_url }})

{: .note }
Need the field on some products only? Create a separate product template with the block, and assign it to those products.

{: .important }
To charge for personalization, add the fee to the product price or create an add-on product. Custom fields never change the price.

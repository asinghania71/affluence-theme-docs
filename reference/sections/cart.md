---
title: Cart
nav_order: 10
permalink: /reference/sections/cart/
grand_parent: Reference
parent: Sections reference
---

# Cart
{: .no_toc }

`sections/cart.liquid`

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Let customers choose which items to check out | checkbox | on | Adds a checkbox to each cart item so customers can choose which items to check out. When off, all items are checked out. |
| Show selected items subtotal | checkbox | on | Replaces "Select all" with a count of selected items. Requires item selection to be enabled. |
| Image width | range | 25 | Percentage of the line item width. |


**Recommendations**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Source | select | automatic | Automatic uses complementary products from the Shopify Search & Discovery app, based on the first item in the cart. Options: Automatic — based on cart items · Specific collection. |
| Collection | collection |  | Used when the source is a specific collection. Also used when the cart is empty or no automatic recommendations are available. |
| Heading | text | You may also like |  |
| Products to show | range | 4 |  |
| Prioritize free-shipping unlocks | checkbox | on | When a free shipping threshold is set, shows a product that would reach it first. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Cart page**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading size | select | h1 | Options: Small · Medium · Large. |
| Top and bottom padding | range | 40 |  |

## Blocks

#### Cart items


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show vendor | checkbox | on |  |
| Show title | checkbox | on |  |
| Show variant options | checkbox | on |  |
| Show price | checkbox | on |  |
| Show quantity selector | checkbox | on |  |
| Show line discounts | checkbox | on | Shows discounts applied to individual items. Order-level discounts are not included. |
| Show unit price | checkbox | on | Applies only to products with unit pricing, such as price per 100 g. |
| Show low stock badge | checkbox | on |  |
| Low stock threshold | range | 5 | Uses your inventory quantity. Shown only for products that track inventory. |
| Show remove button | checkbox | on |  |


#### Free shipping bar


**Free shipping bar**


> Shows progress toward the free shipping amount you enter. Each cart section has its own settings.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Free shipping threshold | text | 150 | Order value for free shipping, without a currency symbol, such as 150. Set to 0 to hide the bar. |
| Progress message | text | Spend [amount] more for free shipping | Use [amount] where the remaining amount should appear. |
| Unlocked message | text | You've unlocked free shipping |  |
| Progress bar track | color | #E4DFD6 |  |
| Progress bar fill | color | #B5956A |  |
| Progress bar when complete | color | #4A7C59 |  |


#### Recommendations



#### Order note



#### Discount code



#### Gift wrap


| Setting | Type | Default | Notes |
|---|---|---|---|
| Gift wrap product | product |  | Added to the cart when customers select gift wrap. Its title and price are shown next to the checkbox. |
| Show gift message field | checkbox | on |  |


#### Shipping estimate



#### Payment methods



#### Hero banner


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  |  |
| Heading | text |  |  |
| Text | richtext |  |  |
| Button label | text |  |  |
| Button link | url |  |  |


#### Rich text


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text |  |  |
| Text | richtext |  |  |
| Alignment | select | left | Options: Center · Left. |


#### Custom Liquid


| Setting | Type | Default | Notes |
|---|---|---|---|
| Liquid code | liquid |  | Add app snippets or other Liquid code to create advanced customizations. |


#### Featured collection


| Setting | Type | Default | Notes |
|---|---|---|---|
| Collection | collection |  |  |
| Heading | text |  |  |
| Products to show | range | 4 |  |


#### Trust badges



#### Carousel


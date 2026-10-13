---
title: Featured product
nav_order: 10
permalink: /reference/sections/featured-product/
grand_parent: Reference
parent: Sections reference
---

# Featured product
{: .no_toc }

`sections/featured-product.liquid`

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Product | product |  |  |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image position | select | left | Options: Left · Right. |


**Legacy overline and text**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Overline | text |  | Shown only when this section has no Title block. |
| Text | richtext |  | Shown only when this section has no Description block. Defaults to the product description when blank. |


**Review widget**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show review widget | checkbox | on | Displays the product's star rating on its image when ratings are available from a product reviews app. Customize it in Theme settings > Review widget. |
| Review widget size | select |  | "Use theme setting" applies the size set in Theme settings > Review widget. Options: Use theme setting · Small · Medium · Large. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 24 |  |

## Blocks

#### App blocks
Accepts blocks from installed Shopify apps.


#### Vendor



#### Title


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading size | select | h1 | Options: Small · Medium · Large. |


#### Product rating



#### Price



#### Variant picker


| Setting | Type | Default | Notes |
|---|---|---|---|
| Style | select | auto | Automatic uses swatches when option values have swatch colors or images, buttons otherwise, and a dropdown for more than 8 values. Options: Automatic · Buttons · Dropdown. |
| Swatch shape | select | circle | Options: Circle · Square. |


#### Custom field


> Collects text such as an engraving or gift message. It's saved with the cart item and the order, and doesn't change the price.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Field type | select | text | Options: Single-line text · Multi-line text · Checkbox · Dropdown. |
| Label | text | Engraving | Also used as the name on the cart item and order. |
| Placeholder | text |  |  |
| Choices | text |  | Separate choices with commas. |
| Character limit | range | 0 | Set to 0 for no limit. |
| Required | checkbox | off | Customers must complete this field before adding the product to their cart. |


#### Subscription options



#### Buy buttons


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show quantity selector | checkbox | on |  |
| Show accelerated checkout buttons | checkbox | on | Customers see the payment methods available to them, such as Shop Pay or PayPal. |


#### Inventory status


| Setting | Type | Default | Notes |
|---|---|---|---|
| Low stock threshold | range | 5 | Uses your inventory quantity. Shown only for products that track inventory. |


#### SKU



#### Pickup availability



#### Estimated delivery date


> A computed display estimate (cutoff time + processing days) — not a live shipping-carrier integration.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Order-by cutoff time | text |  | 24-hour format: HH:MM. Orders placed after this time add one day to the estimate. Leave blank to disable. |
| Non-shipping days | text | 0,6 | Comma-separated weekday numbers from 0 (Sunday) to 6 (Saturday). The default, 0,6, excludes weekends. |
| Minimum business days | range | 2 | Excludes the non-shipping days set above. |
| Maximum business days | range | 5 | Must be equal to or greater than the minimum. Otherwise, the estimate is not shown. |
| Date format | text | %b %d | Liquid date format, such as %b %d for "Jan 5". |
| Message | text | Estimated delivery [start]–[end] | Use [start] and [end] as placeholders for the computed dates. |


#### Quick order trigger


> Opens a bulk-order table for every variant in a modal. Only shows on products with more than one variant.


#### Description



#### Collapsible row


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text | Details |  |
| Text | richtext |  |  |
| Page content | page |  | Shown after the content above, not instead of it. |


#### Tabs


> Each collapsible row inside becomes a tab on desktop. On mobile they stay collapsible rows.


#### Specifications


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text |  |  |


#### Share



#### Wishlist



#### Text


| Setting | Type | Default | Notes |
|---|---|---|---|
| Text | richtext | <p>Add a sentence or two of supporting copy here.</p> |  |
| Style | select | body | Options: Body · Subdued · Label. |


#### Icon with text


| Setting | Type | Default | Notes |
|---|---|---|---|
| Direction | select | horizontal | Options: Horizontal · Vertical. |


**Item 1**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Icon | select | truck | Options: Star · Heart · Shield · Truck · Return · Badge check · Globe · Tag · Check. |
| Text | inline_richtext | Free shipping over $150 |  |


**Item 2**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Icon | select | return | Options: Star · Heart · Shield · Truck · Return · Badge check · Globe · Tag · Check. |
| Text | inline_richtext | 30-day returns |  |


**Item 3**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Icon | select | shield | Options: Star · Heart · Shield · Truck · Return · Badge check · Globe · Tag · Check. |
| Text | inline_richtext | Secure checkout |  |


#### Pop-up


| Setting | Type | Default | Notes |
|---|---|---|---|
| Link label | text | Size guide |  |
| Icon | select | ruler | Options: None · Ruler · Info · Truck · Return. |
| Page | page |  | Shown in the pop-up. Connect a product metafield (page reference) to show a different page for each product, such as a size chart. The link is hidden for products without one. |
| Text | richtext |  | Used when no page is selected, or shown above the page content. |


#### Complementary products


> Set these up per product in Shopify’s Search & Discovery app. The block stays hidden for products that have none.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text | Pairs well with |  |
| Products to show | range | 3 |  |


#### Custom Liquid


| Setting | Type | Default | Notes |
|---|---|---|---|
| Liquid code | liquid |  | Add app snippets or other Liquid code to create advanced customizations. |

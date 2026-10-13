---
title: Theme blocks
nav_order: 2
permalink: /reference/blocks/
parent: Reference
---

# Theme blocks
{: .no_toc }

Reusable blocks that can be added inside sections that accept theme blocks. Blocks used only by the product page or cart are included too, and also listed under the section that uses them.

## Buy buttons

`blocks/_buy_buttons.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Show quantity selector | checkbox | on |  |
| Show accelerated checkout buttons | checkbox | on | Customers see the payment methods available to them, such as Shop Pay or PayPal. |

## Carousel

`blocks/_cart_carousel.liquid`

## Custom Liquid

`blocks/_cart_custom_liquid.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Liquid code | liquid |  | Add app snippets or other Liquid code to create advanced customizations. |

## Discount code

`blocks/_cart_discount.liquid`

## Featured collection

`blocks/_cart_featured_collection.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Collection | collection |  |  |
| Heading | text |  |  |
| Products to show | range | 4 |  |

## Gift wrap

`blocks/_cart_gift_wrap.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Gift wrap product | product |  | Added to the cart when customers select gift wrap. Its title and price are shown next to the checkbox. |
| Show gift message field | checkbox | on |  |

## Hero banner

`blocks/_cart_hero.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  |  |
| Heading | text |  |  |
| Text | richtext |  |  |
| Button label | text |  |  |
| Button link | url |  |  |

## Payment methods

`blocks/_cart_payment_methods.liquid`

## Rich text

`blocks/_cart_rich_text.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text |  |  |
| Text | richtext |  |  |
| Alignment | select | left | Options: Center · Left. |

## Shipping estimate

`blocks/_cart_shipping_estimate.liquid`

## Carousel slide

`blocks/_cart_slide.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  |  |
| Heading | text |  |  |
| Link | url |  |  |

## Trust badge

`blocks/_cart_trust_badge.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Icon | select | shield | Options: Shield · Lock · Truck · Return arrow · Badge check · Checkmark · Box · Plane · Globe · Tag. |
| Text | text | Secure checkout | Leave blank to hide this item. |

## Trust badges

`blocks/_cart_trust_list.liquid`

## Complementary products

`blocks/_complementary.liquid`

> Set these up per product in Shopify’s Search & Discovery app. The block stays hidden for products that have none.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text | Pairs well with |  |
| Products to show | range | 3 |  |

## Row

`blocks/_content-row.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  |  |
| Mobile image | image_picker |  | Optional. Defaults to the image above. |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image position | select | left | Options: Left · Right. |
| Image ratio | select | portrait | Adapt keeps the image's original aspect ratio. Portrait and Square crop it to fit. Options: Adapt · Portrait · Square. |
| Image width | select | medium | Options: Small · Medium · Large. |
| Content position | select | middle | Options: Top · Middle · Bottom. |
| Content alignment | select | left | Options: Left · Center · Right. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |

## Custom field

`blocks/_custom_field.liquid`

> Collects text such as an engraving or gift message. It's saved with the cart item and the order, and doesn't change the price.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Field type | select | text | Options: Single-line text · Multi-line text · Checkbox · Dropdown. |
| Label | text | Engraving | Also used as the name on the cart item and order. |
| Placeholder | text |  |  |
| Choices | text |  | Separate choices with commas. |
| Character limit | range | 0 | Set to 0 for no limit. |
| Required | checkbox | off | Customers must complete this field before adding the product to their cart. |

## Description

`blocks/_description.liquid`

## Estimated delivery date

`blocks/_estimated_delivery.liquid`

> A computed display estimate (cutoff time + processing days) — not a live shipping-carrier integration.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Order-by cutoff time | text |  | 24-hour format: HH:MM. Orders placed after this time add one day to the estimate. Leave blank to disable. |
| Non-shipping days | text | 0,6 | Comma-separated weekday numbers from 0 (Sunday) to 6 (Saturday). The default, 0,6, excludes weekends. |
| Minimum business days | range | 2 | Excludes the non-shipping days set above. |
| Maximum business days | range | 5 | Must be equal to or greater than the minimum. Otherwise, the estimate is not shown. |
| Date format | text | %b %d | Liquid date format, such as %b %d for "Jan 5". |
| Message | text | Estimated delivery [start]–[end] | Use [start] and [end] as placeholders for the computed dates. |

## Inventory status

`blocks/_inventory.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Low stock threshold | range | 5 | Uses your inventory quantity. Shown only for products that track inventory. |

## Cart items

`blocks/_line_items.liquid`

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

## Order note

`blocks/_note.liquid`

## Pickup availability

`blocks/_pickup_availability.liquid`

## Price

`blocks/_price.liquid`

## Product tag

`blocks/_product-tag.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Product | product |  |  |
| Horizontal position | range | 50 | Distance from the left edge of the video. |
| Vertical position | range | 50 | Distance from the top edge of the video. |
| Show from | range | 0 | Seconds into an uploaded video. Leave both times at 0 to show the tag for the whole video. |
| Hide after | range | 0 | Seconds into an uploaded video. Set to 0 to show until the end. |

## Quick order trigger

`blocks/_quick_order_trigger.liquid`

> Opens a bulk-order table for every variant in a modal. Only shows on products with more than one variant.

## Product rating

`blocks/_rating.liquid`

## Recommendations

`blocks/_recommendations.liquid`

## Subscription options

`blocks/_selling_plan_picker.liquid`

## Share

`blocks/_share.liquid`

## Free shipping bar

`blocks/_shipping_bar.liquid`

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

## Short

`blocks/_short.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Video | video |  | Shown in a 9:16 vertical frame. Use a vertical video to avoid cropping. |
| YouTube or Vimeo link | url |  | Used when no video is uploaded. Enter a full YouTube or Vimeo link. Always plays muted and looping, with the platform's own controls. |
| Caption | text |  |  |
| Badge | text |  | Short label over the video, such as "New" or "Behind the scenes". |
| Product below video | product |  | Shows the product's image, price and add to cart button below the video. |
| Crop to fill | checkbox | off | On crops the image to fill the space. Off shows the full image, with empty space if its shape differs. |

## SKU

`blocks/_sku.liquid`

## Specification

`blocks/_spec_row.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Label | text | Material |  |
| Value | inline_richtext |  | Connect a product metafield to show a different value for each product. Rows without a value are hidden. |

## Specifications

`blocks/_specs.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text |  |  |

## Tabs

`blocks/_tabs.liquid`

> Each collapsible row inside becomes a tab on desktop. On mobile they stay collapsible rows.

## Quotes

`blocks/_testimonial-list.liquid`

> Add, remove and reorder quotes inside this block. The layout is set on the section.

## Quote

`blocks/_testimonial.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Quote | richtext | <p>Share a real review from a customer, a stockist or the press.</p> |  |
| Star rating | range | 0 | The rating from the quoted review. Set to 0 to hide the stars. |
| Author | text | Customer name |  |
| Author detail | text |  | Such as "Verified buyer", or a publication and date. |
| Author photo | image_picker |  |  |
| Product | product |  | Links to the product. With a rating and author, also adds review structured data for search engines. |

## Title

`blocks/_title.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading size | select | h1 | Options: Small · Medium · Large. |

## Variant picker

`blocks/_variant_picker.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Style | select | auto | Automatic uses swatches when option values have swatch colors or images, buttons otherwise, and a dropdown for more than 8 values. Options: Automatic · Buttons · Dropdown. |
| Swatch shape | select | circle | Options: Circle · Square. |

## Vendor

`blocks/_vendor.liquid`

## Wishlist

`blocks/_wishlist.liquid`

## Button

`blocks/button.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Button label | text | Shop now |  |
| Button link | url |  |  |
| Style | select | primary | Options: Solid · Outline. |

## Collapsible row

`blocks/collapsible_row.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text | Details |  |
| Text | richtext |  |  |
| Page content | page |  | Shown after the content above, not instead of it. |

## Custom Liquid

`blocks/custom_liquid.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Liquid code | liquid |  | Add app snippets or other Liquid code to create advanced customizations. |

## Group

`blocks/group.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Direction | select | group--horizontal | Options: Horizontal · Vertical. |

## Heading

`blocks/heading.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | inline_richtext | A statement worth making | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large · Extra large · Extra extra large. |

## Icon

`blocks/icon.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Icon | select | star | Options: Star · Heart · Shield · Truck · Return · Badge check · Globe · Tag · Check. |

## Icon with text

`blocks/icon_with_text.liquid`

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

## Order buttons

`blocks/order_buttons.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Show accelerated checkout buttons | checkbox | on | Customers see the payment methods available to them, such as Shop Pay or PayPal. |

## Overline

`blocks/overline.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Text | text | Overline |  |

## Pop-up

`blocks/popup.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Link label | text | Size guide |  |
| Icon | select | ruler | Options: None · Ruler · Info · Truck · Return. |
| Page | page |  | Shown in the pop-up. Connect a product metafield (page reference) to show a different page for each product, such as a size chart. The link is hidden for products without one. |
| Text | richtext |  | Used when no page is selected, or shown above the page content. |

## Subtotal

`blocks/subtotal.liquid`

## Text

`blocks/text.liquid`

| Setting | Type | Default | Notes |
|---|---|---|---|
| Text | richtext | <p>Add a sentence or two of supporting copy here.</p> |  |
| Style | select | body | Options: Body · Subdued · Label. |

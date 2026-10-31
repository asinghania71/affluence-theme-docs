---
title: Theme settings
nav_order: 1
permalink: /reference/theme-settings/
parent: Reference
---

# Theme settings
{: .no_toc }

Open **Theme settings** (paintbrush icon) in the theme editor.

## Brand information

**Logo and icon**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Logo | image_picker |  | Set logo sizes for desktop and mobile in the Header and Footer sections. |
| Favicon | image_picker |  | Use a square image, at least 32 x 32 pixels. |


**Search and sharing**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Description | inline_richtext |  | Default description for search engines and social sharing when a page does not have one. |
| Social sharing image | image_picker |  | Shown when your store link is shared on social media. Use a landscape image of at least 1200 x 628 pixels. |

## Colors

| Setting | Type | Default | Notes |
|---|---|---|---|
| color_schemes | color_scheme_group |  |  |

## Typography

**Headings**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Font | font_picker | fraunces_n4 |  |
| Font size scale | range | 100 | Resizes all headings. 100% keeps the default size. |
| Letter spacing | range | 0 |  |
| Capitalization | select | none | Options: None · Uppercase · Lowercase. |


**Body text**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Font | font_picker | dm_sans_n4 |  |
| Font size scale | range | 100 | Resizes body and interface text. 100% keeps the default size. |


**Overline**


> The small uppercase label shown above section headings.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Letter spacing | range | 30 |  |

## Layout

**Page**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Page width | select | 140rem | Maximum width of page content on large screens. Full-width sections ignore it. Options: Narrow · Medium · Wide. |
| Page margin | range | 16 | Space between page content and the edge of the screen. |


**Spacing**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Grid gap | range | 1 | Set to 1 pixel to show a thin line between grid items. |
| Space between sections | range | 64 | Default vertical space between sections. Individual sections can add their own padding. |
| Show breadcrumbs | checkbox | on | Applies to product, collection, blog, article, page and quick order list pages. |
| Show back to top button | checkbox | off | Shows a button once the visitor has scrolled down the page. |


**Drawers**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Opens from (desktop) | select | end | Applies to cart, quick view and wishlist drawers on desktop. Options: Left · Right · Top · Bottom. |
| Opens from (mobile) | select | bottom | Applies to cart, quick view and wishlist drawers on mobile. Options: Left · Right · Top · Bottom. |

## Buttons and inputs

**Buttons**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Corner radius | range | 0 | Applies to all buttons. Set to 0 for square corners. |
| Border thickness | range | 1 |  |
| Use uppercase button labels | checkbox | on |  |


**Inputs**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Corner radius | range | 0 | Applies to all text fields and dropdowns. |
| Border thickness | range | 1 |  |

## Media

**Images and video**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Corner radius | range | 0 | Rounds the corners of images and videos, except on product cards. Product card corners are set in Product cards. |
| Use image focal points | checkbox | on | Keeps the image focal point visible when images are cropped. |
| Enable image zoom | checkbox | on | Adds a button that opens product images full screen on product pages and in quick view. |

## Animations

> Animations are turned off automatically for visitors whose device is set to reduce motion.


**Motion**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Reveal sections on scroll | checkbox | on | Fades sections in as customers scroll to them. |
| Speed | select | medium | Speed of hover, drawer and scroll animations. Options: Slow · Medium · Fast. |

## Product cards

**Image**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image ratio | select | adapt | Adapt keeps each product's original aspect ratio. Portrait and Square crop images to fit. Options: Adapt · Portrait · Square. |
| Hover effect | select | second-image | Effect when customers hover over a product image. Show second image applies only to products with two or more images. Options: None · Zoom · Show second image. |
| Corner radius | range | 0 |  |


**Content**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Text alignment | select | left | Options: Left · Center. |
| Show vendor | checkbox | on |  |
| Vendor style | select | accent | Options: Subtle · Accent color. |
| Show product rating | checkbox | on | Ratings appear once a product reviews app adds them to your products. |
| Show color swatches | checkbox | on | Uses the swatch colors and images assigned to product options. Displays up to 5 per option. |


**Quick actions**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show quick add button | checkbox | on | When off, the quick view button is shown instead. Set the quick view style to Secondary button for a full-width button. |
| Show quick view button | checkbox | on | Opens a preview where customers can select options without leaving the page. |
| Quick view style | select | icon | Options: Icon only · Secondary button. |
| Quick view icon | select | zoom | Options: Zoom · Eye · Search · Plus · Grid. |
| Add to cart / quick view position | select | overlay | Overlay shows buttons over the product image on hover. Below shows them under the image at all times. Options: Overlay on image · Below image. |
| Show wishlist button | checkbox | on | Items are saved in the customer's browser. No account or app is required. |
| Wishlist button position | select | corner | Options: Image corner · Next to title · With quick add / quick view. |


**Stock**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show low stock message | checkbox | on | Also applies to the quick order list. Uses your inventory quantity and is shown only for products that track inventory. |
| Low stock threshold | range | 5 | The message appears when inventory is at or below this quantity. |

## Badges

| Setting | Type | Default | Notes |
|---|---|---|---|
| Show badges on product cards | checkbox | on | Applies to sale, sold out, low stock and ribbon badges. Sections with their own badge setting can override this. |


**Shape and placement**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Position | select | top-left | Corner of the product image where badges appear. Options: Top left · Top right · Bottom left. |
| Corner radius | range | 0 |  |
| Badge style | select | bold | Bold increases badge size and adds an outline. Applies to badges on product images. Options: Standard · Bold. |


**Sale badge**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #C0392B |  |
| Text | color | #FFFFFF |  |


**New badge**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #B5956A |  |
| Text | color | #FFFFFF |  |


**Sold out badge**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #8A8070 |  |
| Text | color | #FFFFFF |  |


**Low stock badge**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #FFFFFF |  |
| Text | color | #C0392B |  |


**Order status — success**


> Used for order payment and fulfillment status on the account and order pages.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #E4EDE7 |  |
| Text | color | #4A7C59 |  |


**Order status — attention**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #F3E9DC |  |
| Text | color | #B5956A |  |


**Order status — neutral**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #EDEBE7 |  |
| Text | color | #6B6459 |  |


**Default address badge**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #EDEBE7 |  |
| Text | color | #6B6459 |  |

## Product ribbons

> Define up to six ribbons that appear on any matching product — either one that carries a specific tag, or one added within a set number of days. Leave a slot's ribbon text blank to turn it off.


**Display**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Ribbon shape | select | pill | Pill is a rounded label. Diagonal is a banner across the image corner. Options: Rounded pill · Diagonal ribbon. |
| Maximum ribbons to show at once | range | 3 | When several ribbons match a product, only the first ones, in slot order, are shown. |
| Also show on the product page | checkbox | off | Displays matching ribbons on the main product image, in the badge position. |


**Ribbon 1**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Match type | select | tag | Options: Product tag · New arrival. |
| Product tag | text |  | Not case-sensitive. Otherwise must exactly match a product tag. Used only when the match type is Product tag. |
| Days since added | range | 30 | Shows the ribbon for this many days after the product is created. Used only when the match type is New arrival. |
| Ribbon text | text |  |  |
| Background | color | #111110 |  |
| Text | color | #F9F8F5 |  |


**Ribbon 2**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Match type | select | tag | Options: Product tag · New arrival. |
| Product tag | text |  | Not case-sensitive. Otherwise must exactly match a product tag. Used only when the match type is Product tag. |
| Days since added | range | 30 | Shows the ribbon for this many days after the product is created. Used only when the match type is New arrival. |
| Ribbon text | text |  |  |
| Background | color | #111110 |  |
| Text | color | #F9F8F5 |  |


**Ribbon 3**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Match type | select | tag | Options: Product tag · New arrival. |
| Product tag | text |  | Not case-sensitive. Otherwise must exactly match a product tag. Used only when the match type is Product tag. |
| Days since added | range | 30 | Shows the ribbon for this many days after the product is created. Used only when the match type is New arrival. |
| Ribbon text | text |  |  |
| Background | color | #111110 |  |
| Text | color | #F9F8F5 |  |


**Ribbon 4**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Match type | select | tag | Options: Product tag · New arrival. |
| Product tag | text |  | Not case-sensitive. Otherwise must exactly match a product tag. Used only when the match type is Product tag. |
| Days since added | range | 30 | Shows the ribbon for this many days after the product is created. Used only when the match type is New arrival. |
| Ribbon text | text |  |  |
| Background | color | #111110 |  |
| Text | color | #F9F8F5 |  |


**Ribbon 5**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Match type | select | tag | Options: Product tag · New arrival. |
| Product tag | text |  | Not case-sensitive. Otherwise must exactly match a product tag. Used only when the match type is Product tag. |
| Days since added | range | 30 | Shows the ribbon for this many days after the product is created. Used only when the match type is New arrival. |
| Ribbon text | text |  |  |
| Background | color | #111110 |  |
| Text | color | #F9F8F5 |  |


**Ribbon 6**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Match type | select | tag | Options: Product tag · New arrival. |
| Product tag | text |  | Not case-sensitive. Otherwise must exactly match a product tag. Used only when the match type is Product tag. |
| Days since added | range | 30 | Shows the ribbon for this many days after the product is created. Used only when the match type is New arrival. |
| Ribbon text | text |  |  |
| Background | color | #111110 |  |
| Text | color | #F9F8F5 |  |

## Review widget

**Widget**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Enable review widget | checkbox | on | Shows a badge with the product's rating and review count over its image. Shown only for products with reviews. |
| Position | select | bottom-right | Corner of the product image where the widget appears. Options: Top left · Top right · Bottom left · Bottom right. |
| Size | select | medium | Options: Small · Medium · Large. |


**Appearance**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Background | color | #F9F8F5 |  |
| Text | color | #111110 |  |
| Opacity | range | 100 | Applies to the entire widget, including text. |

## Cart

**Cart behavior**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Cart type | select | drawer | Opens after a product is added to the cart: a drawer, the cart page, or a notification. Options: Drawer · Page · Notification. |
| When an item is removed | select | remove | Ask to confirm opens a dialog first. Remove with undo removes the item and shows an Undo button in its place. Options: Remove immediately · Ask to confirm · Remove with undo. |
| Show "Move to wishlist" on cart items | checkbox | off | Saves the item to the wishlist and removes it from the cart. |


**Terms and conditions**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Require agreement to terms | checkbox | off | Customers tick a checkbox before checking out. Dynamic checkout buttons stay hidden until they do. |
| Agreement text | inline_richtext |  | Leave blank to link to your terms of service policy. |

## Wishlist

| Setting | Type | Default | Notes |
|---|---|---|---|
| Enable wishlist | checkbox | on | Removes all wishlist buttons, the header icon and the wishlist drawer when off. |


**Display**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Wishlist type | select | drawer | Where the wishlist opens. Items are saved in the customer's browser. No account is required. Options: Drawer · Modal · Page. |


**Behavior**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show "Move to cart" button | checkbox | on | Replaces the quick add button on saved items with one that moves the item to the cart. |
| Confirm before clearing wishlist | checkbox | on | Asks for confirmation before "Clear all" removes all saved items. |
| Show notification when an item is removed | checkbox | on | Applies when a single item is removed, such as by clicking the heart icon again. |

## Search

**Predictive search**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Show suggestions as customers type | checkbox | on | Shows matching products and suggestions as customers type. When off, customers go directly to the search results page. |
| Show product vendor | checkbox | off |  |
| Show product price | checkbox | on |  |
| Suggested searches | link_list |  | Links shown in the search drawer before customers type, such as collections or popular searches. |
| Show recent searches | checkbox | off | Saved in the customer's browser only. |

## Social media

**Profile links**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Instagram | text |  | Enter the full URL, including https:// |
| Facebook | text |  | Enter the full URL, including https:// |
| Pinterest | text |  | Enter the full URL, including https:// |
| TikTok | text |  | Enter the full URL, including https:// |
| YouTube | text |  | Enter the full URL, including https:// |
| X | text |  | Enter the full URL, including https:// |

## Returns and shipping data

> Shared with Google as structured data on product pages so listings can show return and shipping details. Only enter what your store really offers; leave a field blank to omit it.


**Returns**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Return window (days) | number |  | Leave blank if you do not accept returns. |
| Return shipping | select | FreeReturn | Applies only when the return window is greater than 0 days. Options: Free returns · Customer pays return shipping. |


**Shipping**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Shipping cost | number |  | In your store currency. Enter 0 for free shipping. Leave blank to omit shipping details. |
| Handling time (max days) | number |  | Days needed to prepare an order for shipment. |
| Delivery time, minimum (days) | number |  | Days in transit after shipment. Leave blank for 0. |
| Delivery time, maximum (days) | number |  | Delivery times are shared only when both this field and handling time are set. |

---
title: Footer
nav_order: 10
permalink: /reference/sections/footer/
grand_parent: Reference
parent: Sections reference
---

# Footer
{: .no_toc }

`sections/footer.liquid`

Up to **12** blocks. Available on: footer. Limit: 1 per page.

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Show payment icons | checkbox | on |  |
| Show Follow on Shop button | checkbox | on | Lets customers follow your store on the Shop app. Requires Shop Pay. |
| Show policy links | checkbox | on |  |
| Show country and language selectors | checkbox | on | Shown only when more than one country or language is available in Markets. |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Layout | select | columns | Column settings apply to the Columns and Wordmark layouts. Options: Columns · Centered · Wordmark. |
| Columns on desktop | range | 3 | Number of columns for menu, newsletter and text blocks. The brand block keeps its own wider column. |
| Columns on mobile | range | 1 |  |
| Collapse menus on mobile | checkbox | on | On mobile, menus open on tap. They are always expanded on larger screens. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top padding | range | 72 |  |
| Bottom padding | range | 48 | Mobile uses two thirds of these values. |

## Blocks

#### Brand (max 1)


| Setting | Type | Default | Notes |
|---|---|---|---|
| Logo width | range | 160 |  |
| Logo width on mobile | range | 120 |  |
| Description | inline_richtext | Considered essentials for the everyday ritual. |  |
| Show social media icons | checkbox | on |  |


#### Menu


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text |  | Leave blank to use the menu title. |
| Menu | link_list | footer |  |


#### Signup (max 1)


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text | The inner circle |  |
| Text | inline_richtext | First access to new arrivals and private events. |  |


#### Image


| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  |  |
| Image description | text |  | Read by screen readers. Required when the image is linked. Leave blank to use the image's alt text. |
| Image width | range | 120 |  |
| Link | url |  |  |


#### Follow us (max 1)


> Shows the social links set in Theme settings. Hidden when there are none.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text | Follow us |  |


#### Text


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text |  |  |
| Text | richtext | <p>Share store details, promotions or brand content with your customers.</p> |  |

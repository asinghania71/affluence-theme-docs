---
title: Header menu row
nav_order: 10
permalink: /reference/sections/header-menu-row/
grand_parent: Reference
parent: Sections reference
---

# Header menu row
{: .no_toc }

`sections/header-menu-row.liquid`

Available on: header. Limit: 1 per page.

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Menu | link_list | main-menu | Shown as a second row below the header. A transparent header becomes solid while this row is present. |
| Alignment | select | center | Options: Left · Centered. |
| Dropdown style | select | list | Columns also shows third-level links. Options: List · Columns (full-width panel). |
| Current page indicator | select | underline | Options: Underline · None (bold text). |
| Uppercase links | checkbox | off |  |
| Stick with the header | checkbox | on | Keeps the row below the header while scrolling. Requires the header to stay visible when scrolling. |
| Show a divider below the row | checkbox | on |  |
| On mobile | select | scroll | Options: Scrolling strip of links · Hide the row. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |

## Blocks

#### Highlight


| Setting | Type | Default | Notes |
|---|---|---|---|
| Menu link | url |  | Recommended over the title. The badge stays in place if the link is renamed or translated. |
| Menu link title | text |  | Used when no link is selected. Must exactly match the title of a top-level link in the menu above. |
| Style | select | badge | Options: Badge · Accent color. |
| Badge color | select | new | Options: New · Sale · Low stock. |
| Badge text | text |  | Shown next to the link, such as "New" or "Sale". Leave blank to change only the link color. |


#### Utility link (max 1)


| Setting | Type | Default | Notes |
|---|---|---|---|
| Text | text |  | Shown at the end of the row on desktop, such as "Store locator". |
| Link | url |  |  |

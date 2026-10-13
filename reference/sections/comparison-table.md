---
title: Comparison table
nav_order: 10
permalink: /reference/sections/comparison-table/
grand_parent: Reference
parent: Sections reference
---

# Comparison table
{: .no_toc }

`sections/comparison-table.liquid`

Up to **30** blocks.

## Settings

**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Overline | text |  |  |
| Heading | inline_richtext | Compare | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large. |
| Description | richtext |  |  |


**Table**


> Add up to 4 product or custom columns, then a row per feature. Type yes or no in a cell to show a check or a cross.


| Setting | Type | Default | Notes |
|---|---|---|---|
| Highlighted column | range | 0 | Set to 0 for no highlight. |
| Show column images | checkbox | on |  |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 24 |  |

## Blocks

#### Product column


| Setting | Type | Default | Notes |
|---|---|---|---|
| Product | product |  |  |


#### Custom column


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text | Column |  |
| Subheading | text |  |  |
| Image | image_picker |  |  |
| Link | url |  |  |


#### Row


| Setting | Type | Default | Notes |
|---|---|---|---|
| Feature | text | Feature |  |
| Column 1 | text |  | Enter "yes" or "no" to show a check or cross. Leave a product column blank to use the metafield below. |
| Column 2 | text |  |  |
| Column 3 | text |  |  |
| Column 4 | text |  |  |
| Product metafield | text |  | Metafield namespace and key. Fills blank cells in product columns. |

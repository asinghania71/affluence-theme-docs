---
title: Multi-collection tabs
nav_order: 10
permalink: /reference/sections/multi-collection-tabs/
grand_parent: Reference
parent: Sections reference
---

# Multi-collection tabs
{: .no_toc }

`sections/multi-collection-tabs.liquid`

## Settings

**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Overline | text |  |  |
| Heading | inline_richtext |  | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large. |
| Alignment | select | left | Options: Left · Center · Right. |
| Description | richtext |  |  |
| Description style | select | body | Options: Body · Subtitle. |


**Tabs**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Tab style | select | pills | "Text only" hides the tab images. Options: Pills · Underline · Text only · Image above title. |
| Keep tabs visible while scrolling | checkbox | off | Keeps the tab row below the header while this section is in view. |
| Image shape | select | circle | Options: Circle · Square. |
| Tab image size | range | 64 |  |
| Tab image size on mobile | range | 48 |  |


**Layout**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Products per tab | range | 8 |  |
| Pagination | select | pages | Pages links to each collection page. Load more and Infinite scroll load products within this section. Options: Numbered pages · "Load more" button · Infinite scroll · None. |
| Show "View all" link | checkbox | off |  |
| Show filter and sort | checkbox | off | Adds a drawer with filters and sort options for the active tab. Without JavaScript, customers are sent to the collection page. |
| Show sorting | checkbox | on |  |
| Load tabs on demand | checkbox | off | Loads only the first tab with the page, and other tabs when selected. Improves speed with many tabs. Without JavaScript, other tabs show a link instead of products. |
| Columns on desktop | range | 4 |  |
| Columns on mobile | range | 2 |  |
| Full width | checkbox | off |  |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 24 |  |

## Blocks

#### Collection


| Setting | Type | Default | Notes |
|---|---|---|---|
| Collection | collection |  |  |
| Tab title | text |  | Defaults to the collection title. |
| Tab image | image_picker |  | Defaults to the collection image. |
| Tab badge | text |  | Short label on the tab, such as "New" or "Sale". |
| Tab description | textarea |  | Text shown above this tab's products. |
| Products in this tab | range | 0 | Set to 0 to use the section's "Products per tab" setting. |

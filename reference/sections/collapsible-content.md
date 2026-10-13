---
title: Collapsible content
nav_order: 10
permalink: /reference/sections/collapsible-content/
grand_parent: Reference
parent: Sections reference
---

# Collapsible content
{: .no_toc }

`sections/collapsible-content.liquid`

## Settings

| Setting | Type | Default | Notes |
|---|---|---|---|
| Image | image_picker |  |  |
| Image position | select | left | Options: Left · Right. |


**Heading**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Overline | text |  |  |
| Heading | inline_richtext | Frequently asked questions | Italicized words display upright in the accent color. |
| Heading size | select | h2 | Options: Small · Medium · Large · Extra large · Extra extra large. |
| Alignment | select | left | Options: Left · Center · Right. |
| Layout | select | none | Options: None · Boxed rows · Boxed section. |


**Behavior**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Only allow one row open at a time | checkbox | on | Opening a row closes any other open row. Requires JavaScript. |
| Open the first row by default | checkbox | off |  |
| Add FAQ structured data | checkbox | on | Adds FAQ structured data for search engines. Turn off if this section is not used for questions and answers. |


**Color scheme**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Color scheme | color_scheme | scheme-1 |  |


**Section padding**


| Setting | Type | Default | Notes |
|---|---|---|---|
| Top and bottom padding | range | 24 |  |

## Blocks

#### Row


| Setting | Type | Default | Notes |
|---|---|---|---|
| Heading | text | Question goes here |  |
| Text | richtext | <p>Answer goes here.</p> |  |
| Page content | page |  | Optional. Shows the page content instead of the text above. |

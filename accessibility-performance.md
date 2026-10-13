---
title: Accessibility and performance
nav_order: 5
permalink: /accessibility-performance/
---

# Accessibility and performance
{: .no_toc }

1. TOC
{:toc}

## Accessibility

Lush is built toward WCAG 2.1 AA:

- Visible keyboard focus on every interactive element.
- Form fields have labels connected to their inputs.
- Drawers and modals contain focus and close with the **Esc** key.
- Controls have comfortable touch targets.
- Animations, the scrolling announcement bar and video autoplay respect the visitor's **reduced motion** preference.
- Predictive search works with the keyboard and announces results to screen readers.

**What you control as the merchant**

- Write meaningful **alt text** for every image.
- Choose colors with enough contrast. Body text should reach 4.5:1.
- Give links and buttons descriptive labels, not "click here".
- Use real headings in order, and avoid using headings just for size.

## Performance

- Ships no external script or font hosts. Everything is served from Shopify.
- Written in native CSS and vanilla JavaScript with no third-party libraries.
- Core shopping flows (navigation, the product form, filters, pagination) work without JavaScript.

**What you control as the merchant**

- Upload images no larger than needed. Very large originals slow pages down even when Shopify resizes them.
- Keep the number of sections on the home page reasonable.
- Each installed app can add scripts. Remove apps you no longer use.
- Prefer a single video section over several autoplaying videos.

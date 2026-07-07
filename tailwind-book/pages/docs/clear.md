---
type: Web Page
title: clear - Layout - Tailwind CSS
description: Utilities for controlling the wrapping of content around an element.
resource: https://tailwindcss.com/docs/clear
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Layout

Utilities for controlling the wrapping of content around an element.

| Class | Styles | 
|---|---|
| `clear-left` | `clear: left;` | 
| `clear-right` | `clear: right;` | 
| `clear-both` | `clear: both;` | 
| `clear-start` | `clear: inline-start;` | 
| `clear-end` | `clear: inline-end;` | 
| `clear-none` | `clear: none;` | 

Use the `clear-left` utility to position an element below any preceding left-floated elements:

Use the `clear-right` utility to position an element below any preceding right-floated elements:

Use the `clear-both` utility to position an element below all preceding floated elements:

Use the `clear-start` and `clear-end` utilities, which use logical properties to map to either the left or right side based on the text direction:

Use the `clear-none` utility to reset any clears that are applied to an element:

Prefix a `clear` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="clear-left md:clear-none ...">  Lorem ipsum dolor sit amet...</p>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/clear

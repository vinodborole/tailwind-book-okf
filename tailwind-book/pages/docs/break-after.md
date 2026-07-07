---
type: Web Page
title: break-after - Layout - Tailwind CSS
description: Utilities for controlling how a column or page should break after an
  element.
resource: https://tailwindcss.com/docs/break-after
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Layout

Utilities for controlling how a column or page should break after an element.

| Class | Styles | 
|---|---|
| `break-after-auto` | `break-after: auto;` | 
| `break-after-avoid` | `break-after: avoid;` | 
| `break-after-all` | `break-after: all;` | 
| `break-after-avoid-page` | `break-after: avoid-page;` | 
| `break-after-page` | `break-after: page;` | 
| `break-after-left` | `break-after: left;` | 
| `break-after-right` | `break-after: right;` | 
| `break-after-column` | `break-after: column;` | 

Use utilities like `break-after-column` and `break-after-page` to control how a column or page break should behave after an element:

`<div class="columns-2">  <p>Well, let me tell you something, ...</p>  <p class="break-after-column">Sure, go ahead, laugh...</p>  <p>Maybe we can live without...</p>  <p>Look. If you think this is...</p></div>`Prefix a `break-after` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="break-after-column md:break-after-auto ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/break-after

---
type: Web Page
title: break-inside - Layout - Tailwind CSS
description: Utilities for controlling how a column or page should break within an
  element.
resource: https://tailwindcss.com/docs/break-inside
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Layout

Utilities for controlling how a column or page should break within an element.

| Class | Styles | 
|---|---|
| `break-inside-auto` | `break-inside: auto;` | 
| `break-inside-avoid` | `break-inside: avoid;` | 
| `break-inside-avoid-page` | `break-inside: avoid-page;` | 
| `break-inside-avoid-column` | `break-inside: avoid-column;` | 

Use utilities like `break-inside-column` and `break-inside-avoid-page` to control how a column or page break should behave within an element:

`<div class="columns-2">  <p>Well, let me tell you something, ...</p>  <p class="break-inside-avoid-column">Sure, go ahead, laugh...</p>  <p>Maybe we can live without...</p>  <p>Look. If you think this is...</p></div>`Prefix a `break-inside` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="break-inside-avoid-column md:break-inside-auto ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/break-inside

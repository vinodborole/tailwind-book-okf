---
type: Web Page
title: place-self - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how an individual item is justified and aligned
  at the same time.
resource: https://tailwindcss.com/docs/place-self
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for controlling how an individual item is justified and aligned at the same time.

| Class | Styles | 
|---|---|
| `place-self-auto` | `place-self: auto;` | 
| `place-self-start` | `place-self: start;` | 
| `place-self-end` | `place-self: end;` | 
| `place-self-end-safe` | `place-self: safe end;` | 
| `place-self-center` | `place-self: center;` | 
| `place-self-center-safe` | `place-self: safe center;` | 
| `place-self-stretch` | `place-self: stretch;` | 

Use `place-self-auto` to align an item based on the value of the container's `place-items` property:

Use `place-self-start` to align an item to the start on both axes:

Use `place-self-center` to align an item at the center on both axes:

Use `place-self-end` to align an item to the end on both axes:

Use `place-self-stretch` to stretch an item on both axes:

Prefix a `place-self` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="place-self-start md:place-self-end ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/place-self

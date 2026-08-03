---
type: Web Page
title: justify-self - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how an individual grid item is aligned along
  its inline axis.
resource: https://tailwindcss.com/docs/justify-self
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Flexbox & Grid

Utilities for controlling how an individual grid item is aligned along its inline axis.

| Class | Styles | 
|---|---|
| `justify-self-auto` | `justify-self: auto;` | 
| `justify-self-start` | `justify-self: start;` | 
| `justify-self-center` | `justify-self: center;` | 
| `justify-self-center-safe` | `justify-self: safe center;` | 
| `justify-self-end` | `justify-self: end;` | 
| `justify-self-end-safe` | `justify-self: safe end;` | 
| `justify-self-stretch` | `justify-self: stretch;` | 

Use the `justify-self-auto` utility to align an item based on the value of the grid's `justify-items` property:

Use the `justify-self-start` utility to align a grid item to the start of its inline axis:

Use the `justify-self-center` or `justify-self-center-safe` utilities to align a grid item along the center of its inline axis:

Resize the container to see the alignment behavior

When there is not enough space available, the `justify-self-center-safe` utility will align the item to the start of the container instead of the end.

Use the `justify-self-end` or `justify-self-end-safe` utilities to align a grid item to the end of its inline axis:

When there is not enough space available, the `justify-self-end-safe` utility will align the item to the start of the container instead of the end.

Use the `justify-self-stretch` utility to stretch a grid item to fill the grid area on its inline axis:

Prefix a `justify-self` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="justify-self-start md:justify-self-end ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/justify-self

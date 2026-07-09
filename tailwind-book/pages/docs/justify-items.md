---
type: Web Page
title: justify-items - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how grid items are aligned along their inline
  axis.
resource: https://tailwindcss.com/docs/justify-items
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Flexbox & Grid

Utilities for controlling how grid items are aligned along their inline axis.

| Class | Styles | 
|---|---|
| `justify-items-start` | `justify-items: start;` | 
| `justify-items-end` | `justify-items: end;` | 
| `justify-items-end-safe` | `justify-items: safe end;` | 
| `justify-items-center` | `justify-items: center;` | 
| `justify-items-center-safe` | `justify-items: safe center;` | 
| `justify-items-stretch` | `justify-items: stretch;` | 
| `justify-items-normal` | `justify-items: normal;` | 

Use the `justify-items-start` utility to justify grid items against the start of their inline axis:

Use the `justify-items-end` or `justify-items-end-safe` utilities to justify grid items against the end of their inline axis:

Resize the container to see the alignment behavior

When there is not enough space available, the `justify-items-end-safe` utility will align items to the start of the container instead of the end.

Use the `justify-items-center` or `justify-items-center-safe` utilities to justify grid items against the end of their inline axis:

Resize the container to see the alignment behavior

When there is not enough space available, the `justify-items-center-safe` utility will align items to the start of the container instead of the center.

Use the `justify-items-stretch` utility to stretch items along their inline axis:

Prefix a `justify-items` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid justify-items-start md:justify-items-center ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/justify-items

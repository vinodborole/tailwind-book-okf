---
type: Web Page
title: box-decoration-break - Layout - Tailwind CSS
description: Utilities for controlling how element fragments should be rendered across
  multiple lines, columns, or pages.
resource: https://tailwindcss.com/docs/box-decoration-break
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Layout

Utilities for controlling how element fragments should be rendered across multiple lines, columns, or pages.

| Class | Styles | 
|---|---|
| `box-decoration-clone` | `box-decoration-break: clone;` | 
| `box-decoration-slice` | `box-decoration-break: slice;` | 

Use the `box-decoration-slice` and `box-decoration-clone` utilities to control whether properties like background, border, border-image, box-shadow, clip-path, margin, and padding should be rendered as if the element were one continuous fragment, or distinct blocks:

Prefix a `box-decoration-break` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="box-decoration-clone md:box-decoration-slice ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/box-decoration-break

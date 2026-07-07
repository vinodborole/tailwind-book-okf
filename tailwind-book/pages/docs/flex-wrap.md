---
type: Web Page
title: flex-wrap - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how flex items wrap.
resource: https://tailwindcss.com/docs/flex-wrap
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for controlling how flex items wrap.

| Class | Styles | 
|---|---|
| `flex-nowrap` | `flex-wrap: nowrap;` | 
| `flex-wrap` | `flex-wrap: wrap;` | 
| `flex-wrap-reverse` | `flex-wrap: wrap-reverse;` | 

Use `flex-nowrap` to prevent flex items from wrapping, causing inflexible items to overflow the container if necessary:

Use `flex-wrap` to allow flex items to wrap:

Use `flex-wrap-reverse` to wrap flex items in the reverse direction:

Prefix a `flex-wrap` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="flex flex-wrap md:flex-wrap-reverse ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/flex-wrap

---
type: Web Page
title: list-style-image - Typography - Tailwind CSS
description: Utilities for controlling the marker images for list items.
resource: https://tailwindcss.com/docs/list-style-image
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Typography

Utilities for controlling the marker images for list items.

| Class | Styles | 
|---|---|
| `list-image-[` | `list-style-image: ` | 
| `list-image-(` | `list-style-image: var(` | 
| `list-image-none` | `list-style-image: none;` | 

Use the `list-image-[` syntax to control the marker image for list items:`<value>`]

Use the `list-image-(<custom-property>)` syntax to control the marker image for list items using a CSS variable:

`<ul class="list-image-(--my-list-image)">  <!-- ... --></ul>`This is just a shorthand for `list-image-[var(<custom-property>)]` that adds the `var()` function for you automatically.

Use the `list-image-none` utility to remove an existing marker image from list items:

`<ul class="list-image-none">  <!-- ... --></ul>`Prefix a `list-style-image` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<ul class="list-image-none md:list-image-[url(/img/checkmark.png)] ...">  <!-- ... --></ul>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/list-style-image

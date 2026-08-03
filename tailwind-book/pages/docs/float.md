---
type: Web Page
title: float - Layout - Tailwind CSS
description: Utilities for controlling the wrapping of content around an element.
resource: https://tailwindcss.com/docs/float
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Layout

Utilities for controlling the wrapping of content around an element.

| Class | Styles | 
|---|---|
| `float-right` | `float: right;` | 
| `float-left` | `float: left;` | 
| `float-start` | `float: inline-start;` | 
| `float-end` | `float: inline-end;` | 
| `float-none` | `float: none;` | 

Use the `float-right` utility to float an element to the right of its container:

Use the `float-left` utility to float an element to the left of its container:

Use the `float-start` and `float-end` utilities, which use [logical properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Logical_Properties/Basic_concepts) to map to either the left or right side based on the text direction:

Use the `float-none` utility to reset any floats that are applied to an element:

Prefix a `float` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<img class="float-right md:float-left" src="/img/mountains.jpg" />`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/float

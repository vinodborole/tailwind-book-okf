---
type: Web Page
title: text-align - Typography - Tailwind CSS
description: Utilities for controlling the alignment of text.
resource: https://tailwindcss.com/docs/text-align
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Typography

Utilities for controlling the alignment of text.

| Class | Styles | 
|---|---|
| `text-left` | `text-align: left;` | 
| `text-center` | `text-align: center;` | 
| `text-right` | `text-align: right;` | 
| `text-justify` | `text-align: justify;` | 
| `text-start` | `text-align: start;` | 
| `text-end` | `text-align: end;` | 

Use the `text-left` utility to left align the text of an element:

Use the `text-right` utility to right align the text of an element:

Use the `text-center` utility to center the text of an element:

Use the `text-justify` utility to justify the text of an element:

Use the `text-start` and `text-end` utilities, which use [logical properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Logical_Properties/Basic_concepts) to map to either the left or right side based on the text direction:

Prefix a `text-align` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="text-left md:text-center ...">  Lorem ipsum dolor sit amet...</p>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/text-align

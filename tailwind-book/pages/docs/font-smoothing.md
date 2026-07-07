---
type: Web Page
title: font-smoothing - Typography - Tailwind CSS
description: Utilities for controlling the font smoothing of an element.
resource: https://tailwindcss.com/docs/font-smoothing
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Typography

Utilities for controlling the font smoothing of an element.

| Class | Styles | 
|---|---|
| `antialiased` | ```
-webkit-font-smoothing: antialiased;
-moz-osx-font-smoothing: grayscale;
```
 | 
| `subpixel-antialiased` | ```
-webkit-font-smoothing: auto;
-moz-osx-font-smoothing: auto;
```
 | 

Use the `antialiased` utility to render text using grayscale antialiasing:

Use the `subpixel-antialiased` utility to render text using subpixel antialiasing:

Prefix `-webkit-font-smoothing` and `-moz-osx-font-smoothing` utilities with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="antialiased md:subpixel-antialiased ...">  Lorem ipsum dolor sit amet...</p>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/font-smoothing

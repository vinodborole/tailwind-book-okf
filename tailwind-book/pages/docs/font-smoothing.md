---
type: Web Page
title: font-smoothing - Typography - Tailwind CSS
description: Utilities for controlling the font smoothing of an element.
resource: https://tailwindcss.com/docs/font-smoothing
timestamp: '2026-07-09T12:17:00.933290+00:00'
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

`<p class="antialiased md:subpixel-antialiased ...">  Lorem ipsum dolor sit amet...</p>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/font-smoothing

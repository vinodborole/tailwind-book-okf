---
type: Web Page
title: height - Sizing - Tailwind CSS
description: Utilities for setting the height of an element.
resource: https://tailwindcss.com/docs/height
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Sizing

Utilities for setting the height of an element.

| Class | Styles | 
|---|---|
| `h-` | `height: calc(var(--spacing) * ` | 
| `h-` | `height: calc(` | 
| `h-auto` | `height: auto;` | 
| `h-px` | `height: 1px;` | 
| `h-full` | `height: 100%;` | 
| `h-screen` | `height: 100vh;` | 
| `h-dvh` | `height: 100dvh;` | 
| `h-dvw` | `height: 100dvw;` | 
| `h-lvh` | `height: 100lvh;` | 
| `h-lvw` | `height: 100lvw;` | 
| `h-svh` | `height: 100svh;` | 
| `h-svw` | `height: 100svw;` | 
| `h-min` | `height: min-content;` | 
| `h-max` | `height: max-content;` | 
| `h-fit` | `height: fit-content;` | 
| `h-lh` | `height: 1lh;` | 
| `h-(` | `height: var(` | 
| `h-[` | `height: ` | 
| `size-` | `width: calc(var(--spacing) * ` | 
| `size-` | `width: calc(` | 
| `size-auto` | ```
width: auto;
height: auto;
```
 | 
| `size-px` | ```
width: 1px;
height: 1px;
```
 | 
| `size-full` | ```
width: 100%;
height: 100%;
```
 | 
| `size-dvw` | ```
width: 100dvw;
height: 100dvw;
```
 | 
| `size-dvh` | ```
width: 100dvh;
height: 100dvh;
```
 | 
| `size-lvw` | ```
width: 100lvw;
height: 100lvw;
```
 | 
| `size-lvh` | ```
width: 100lvh;
height: 100lvh;
```
 | 
| `size-svw` | ```
width: 100svw;
height: 100svw;
```
 | 
| `size-svh` | ```
width: 100svh;
height: 100svh;
```
 | 
| `size-min` | ```
width: min-content;
height: min-content;
```
 | 
| `size-max` | ```
width: max-content;
height: max-content;
```
 | 
| `size-fit` | ```
width: fit-content;
height: fit-content;
```
 | 
| `size-(` | `width: var(` | 
| `size-[` | `width: ` | 

Use `h-` utilities like `<number>``h-24` and `h-64` to set an element to a fixed height based on the spacing scale:

Use `h-full` or `h-` utilities like `<fraction>``h-1/2` and `h-2/5` to give an element a percentage-based height:

Use the `h-screen` utility to make an element span the entire height of the viewport:

`<div class="h-screen">  <!-- ... --></div>`Use the `h-dvh` utility to make an element span the entire height of the viewport, which changes as the browser UI expands or contracts:

Scroll the viewport to see the viewport height change

Use the `h-lvh` utility to set an element's height to the largest possible height of the viewport:

Scroll the viewport to see the viewport height change

Use the `h-svh` utility to set an element's height to the smallest possible height of the viewport:

Scroll the viewport to see the viewport height change

Use utilities like `size-px`, `size-4`, and `size-full` to set both the width and height of an element at the same time:

Use the `h-[` syntax to set the height based on a completely custom value:`<value>`]

`<div class="h-[32rem] ...">  <!-- ... --></div>`For CSS variables, you can also use the `h-(` syntax:`<custom-property>`)

`<div class="h-(--my-height) ...">  <!-- ... --></div>`This is just a shorthand for `h-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `height` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="h-1/2 md:h-full ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `h-` and `<number>``size-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/height

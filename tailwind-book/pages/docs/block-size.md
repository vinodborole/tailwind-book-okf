---
type: Web Page
title: block-size - Sizing - Tailwind CSS
description: Utilities for setting the block size of an element.
resource: https://tailwindcss.com/docs/block-size
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Sizing

Utilities for setting the block size of an element.

| Class | Styles | 
|---|---|
| `block-` | `block-size: calc(var(--spacing) * ` | 
| `block-` | `block-size: calc(` | 
| `block-auto` | `block-size: auto;` | 
| `block-px` | `block-size: 1px;` | 
| `block-full` | `block-size: 100%;` | 
| `block-screen` | `block-size: 100vh;` | 
| `block-dvh` | `block-size: 100dvh;` | 
| `block-dvw` | `block-size: 100dvw;` | 
| `block-lvh` | `block-size: 100lvh;` | 
| `block-lvw` | `block-size: 100lvw;` | 
| `block-svh` | `block-size: 100svh;` | 
| `block-svw` | `block-size: 100svw;` | 
| `block-min` | `block-size: min-content;` | 
| `block-max` | `block-size: max-content;` | 
| `block-fit` | `block-size: fit-content;` | 
| `block-lh` | `block-size: 1lh;` | 
| `block-(` | `block-size: var(` | 
| `block-[` | `block-size: ` | 

Use `block-` utilities like `<number>``block-24` and `block-64` to set an element to a fixed block size based on the spacing scale:

Use `block-full` or `block-` utilities like `<fraction>``block-1/2` and `block-2/5` to give an element a percentage-based block size:

Use the `block-screen` utility to make an element span the entire block size of the viewport:

`<div class="block-screen">  <!-- ... --></div>`Use the `block-dvh` utility to make an element span the entire block size of the viewport, which changes as the browser UI expands or contracts:

`<div class="block-dvh">  <!-- ... --></div>`Use the `block-lvh` utility to set an element's block size to the largest possible size of the viewport:

`<div class="block-lvh">  <!-- ... --></div>`Use the `block-svh` utility to set an element's block size to the smallest possible size of the viewport:

`<div class="block-svh">  <!-- ... --></div>`Use the `block-[` syntax to set the block size based on a completely custom value:`<value>`]

`<div class="block-[32rem] ...">  <!-- ... --></div>`For CSS variables, you can also use the `block-(` syntax:`<custom-property>`)

`<div class="block-(--my-block-size) ...">  <!-- ... --></div>`This is just a shorthand for `block-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `block-size` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="block-1/2 md:block-full ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `block-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/block-size

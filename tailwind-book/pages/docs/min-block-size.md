---
type: Web Page
title: min-block-size - Sizing - Tailwind CSS
description: Utilities for setting the minimum block size of an element.
resource: https://tailwindcss.com/docs/min-block-size
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Sizing

Utilities for setting the minimum block size of an element.

| Class | Styles | 
|---|---|
| `min-block-` | `min-block-size: calc(var(--spacing) * ` | 
| `min-block-` | `min-block-size: calc(` | 
| `min-block-px` | `min-block-size: 1px;` | 
| `min-block-full` | `min-block-size: 100%;` | 
| `min-block-screen` | `min-block-size: 100vh;` | 
| `min-block-dvh` | `min-block-size: 100dvh;` | 
| `min-block-dvw` | `min-block-size: 100dvw;` | 
| `min-block-lvh` | `min-block-size: 100lvh;` | 
| `min-block-lvw` | `min-block-size: 100lvw;` | 
| `min-block-svw` | `min-block-size: 100svw;` | 
| `min-block-svh` | `min-block-size: 100svh;` | 
| `min-block-auto` | `min-block-size: auto;` | 
| `min-block-min` | `min-block-size: min-content;` | 
| `min-block-max` | `min-block-size: max-content;` | 
| `min-block-fit` | `min-block-size: fit-content;` | 
| `min-block-lh` | `min-block-size: 1lh;` | 
| `min-block-(` | `min-block-size: var(` | 
| `min-block-[` | `min-block-size: ` | 

Use `min-block-` utilities like `<number>``min-block-24` and `min-block-64` to set an element to a fixed minimum block size based on the spacing scale:

Use `min-block-full` or `min-block-` utilities like `<fraction>``min-block-1/2`, and `min-block-2/5` to give an element a percentage-based minimum block size:

Use the `min-block-[` syntax to set the minimum block size based on a completely custom value:`<value>`]

`<div class="min-block-[220px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `min-block-(` syntax:`<custom-property>`)

`<div class="min-block-(--my-min-block-size) ...">  <!-- ... --></div>`This is just a shorthand for `min-block-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `min-block-size` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="block-24 min-block-0 md:min-block-full ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `min-block-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/min-block-size

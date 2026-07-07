---
type: Web Page
title: max-block-size - Sizing - Tailwind CSS
description: Utilities for setting the maximum block size of an element.
resource: https://tailwindcss.com/docs/max-block-size
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Sizing

Utilities for setting the maximum block size of an element.

| Class | Styles | 
|---|---|
| `max-block-` | `max-block-size: calc(var(--spacing) * ` | 
| `max-block-` | `max-block-size: calc(` | 
| `max-block-none` | `max-block-size: none;` | 
| `max-block-px` | `max-block-size: 1px;` | 
| `max-block-full` | `max-block-size: 100%;` | 
| `max-block-screen` | `max-block-size: 100vh;` | 
| `max-block-dvh` | `max-block-size: 100dvh;` | 
| `max-block-dvw` | `max-block-size: 100dvw;` | 
| `max-block-lvh` | `max-block-size: 100lvh;` | 
| `max-block-lvw` | `max-block-size: 100lvw;` | 
| `max-block-svh` | `max-block-size: 100svh;` | 
| `max-block-svw` | `max-block-size: 100svw;` | 
| `max-block-min` | `max-block-size: min-content;` | 
| `max-block-max` | `max-block-size: max-content;` | 
| `max-block-fit` | `max-block-size: fit-content;` | 
| `max-block-lh` | `max-block-size: 1lh;` | 
| `max-block-(` | `max-block-size: var(` | 
| `max-block-[` | `max-block-size: ` | 

Use `max-block-` utilities like `<number>``max-block-24` and `max-block-64` to set an element to a fixed maximum block size based on the spacing scale:

Use `max-block-full` or `max-block-` utilities like `<fraction>``max-block-1/2` and `max-block-2/5` to give an element a percentage-based maximum block size:

Use the `max-block-[` syntax to set the maximum block size based on a completely custom value:`<value>`]

`<div class="max-block-[220px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `max-block-(` syntax:`<custom-property>`)

`<div class="max-block-(--my-max-block-size) ...">  <!-- ... --></div>`This is just a shorthand for `max-block-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `max-block-size` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="block-48 max-block-full md:max-block-screen ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

The `max-block-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the theme variable documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/max-block-size

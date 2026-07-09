---
type: Web Page
title: min-height - Sizing - Tailwind CSS
description: Utilities for setting the minimum height of an element.
resource: https://tailwindcss.com/docs/min-height
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Sizing

Utilities for setting the minimum height of an element.

| Class | Styles | 
|---|---|
| `min-h-` | `min-height: calc(var(--spacing) * ` | 
| `min-h-` | `min-height: calc(` | 
| `min-h-px` | `min-height: 1px;` | 
| `min-h-full` | `min-height: 100%;` | 
| `min-h-screen` | `min-height: 100vh;` | 
| `min-h-dvh` | `min-height: 100dvh;` | 
| `min-h-dvw` | `min-height: 100dvw;` | 
| `min-h-lvh` | `min-height: 100lvh;` | 
| `min-h-lvw` | `min-height: 100lvw;` | 
| `min-h-svw` | `min-height: 100svw;` | 
| `min-h-svh` | `min-height: 100svh;` | 
| `min-h-auto` | `min-height: auto;` | 
| `min-h-min` | `min-height: min-content;` | 
| `min-h-max` | `min-height: max-content;` | 
| `min-h-fit` | `min-height: fit-content;` | 
| `min-h-lh` | `min-height: 1lh;` | 
| `min-h-(` | `min-height: var(` | 
| `min-h-[` | `min-height: ` | 

Use `min-h-` utilities like `<number>``min-h-24` and `min-h-64` to set an element to a fixed minimum height based on the spacing scale:

Use `min-h-full` or `min-h-` utilities like `<fraction>``min-h-1/2`, and `min-h-2/5` to give an element a percentage-based minimum height:

Use the `min-h-[` syntax to set the minimum height based on a completely custom value:`<value>`]

`<div class="min-h-[220px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `min-h-(` syntax:`<custom-property>`)

`<div class="min-h-(--my-min-height) ...">  <!-- ... --></div>`This is just a shorthand for `min-h-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `min-height` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="h-24 min-h-0 md:min-h-full ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `min-h-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/min-height

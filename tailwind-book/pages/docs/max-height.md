---
type: Web Page
title: max-height - Sizing - Tailwind CSS
description: Utilities for setting the maximum height of an element.
resource: https://tailwindcss.com/docs/max-height
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Sizing

Utilities for setting the maximum height of an element.

| Class | Styles | 
|---|---|
| `max-h-` | `max-height: calc(var(--spacing) * ` | 
| `max-h-` | `max-height: calc(` | 
| `max-h-none` | `max-height: none;` | 
| `max-h-px` | `max-height: 1px;` | 
| `max-h-full` | `max-height: 100%;` | 
| `max-h-screen` | `max-height: 100vh;` | 
| `max-h-dvh` | `max-height: 100dvh;` | 
| `max-h-dvw` | `max-height: 100dvw;` | 
| `max-h-lvh` | `max-height: 100lvh;` | 
| `max-h-lvw` | `max-height: 100lvw;` | 
| `max-h-svh` | `max-height: 100svh;` | 
| `max-h-svw` | `max-height: 100svw;` | 
| `max-h-min` | `max-height: min-content;` | 
| `max-h-max` | `max-height: max-content;` | 
| `max-h-fit` | `max-height: fit-content;` | 
| `max-h-lh` | `max-height: 1lh;` | 
| `max-h-(` | `max-height: var(` | 
| `max-h-[` | `max-height: ` | 

Use `max-h-` utilities like `<number>``max-h-24` and `max-h-64` to set an element to a fixed maximum height based on the spacing scale:

Use `max-h-full` or `max-h-` utilities like `<fraction>``max-h-1/2` and `max-h-2/5` to give an element a percentage-based maximum height:

Use the `max-h-[` syntax to set the maximum height based on a completely custom value:`<value>`]

`<div class="max-h-[220px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `max-h-(` syntax:`<custom-property>`)

`<div class="max-h-(--my-max-height) ...">  <!-- ... --></div>`This is just a shorthand for `max-h-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `max-height` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="h-48 max-h-full md:max-h-screen ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `max-h-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/max-height

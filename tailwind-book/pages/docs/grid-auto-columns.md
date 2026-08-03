---
type: Web Page
title: grid-auto-columns - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling the size of implicitly-created grid columns.
resource: https://tailwindcss.com/docs/grid-auto-columns
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Flexbox & Grid

Utilities for controlling the size of implicitly-created grid columns.

| Class | Styles | 
|---|---|
| `auto-cols-auto` | `grid-auto-columns: auto;` | 
| `auto-cols-min` | `grid-auto-columns: min-content;` | 
| `auto-cols-max` | `grid-auto-columns: max-content;` | 
| `auto-cols-fr` | `grid-auto-columns: minmax(0, 1fr);` | 
| `auto-cols-``<number>` | `grid-auto-columns: calc(var(--spacing) *` `<number>` ); | 
| `auto-cols-(``<custom-property>` ) | `grid-auto-columns: var(``<custom-property>` ); | 
| `auto-cols-[``<value>` ] | `grid-auto-columns:` `<value>` ; | 

Use utilities like `auto-cols-min` and `auto-cols-max` to control the size of implicitly-created grid columns:

`<div class="grid auto-cols-max grid-flow-col">  <div>01</div>  <div>02</div>  <div>03</div></div>`
Use the `auto-cols-[` syntax to set the size of implicitly-created grid columns based on a completely custom value:`<value>`]

`<div class="auto-cols-[minmax(0,2fr)] ...">  <!-- ... --></div>`
For CSS variables, you can also use the `auto-cols-(` syntax:`<custom-property>`)

`<div class="auto-cols-(--my-auto-cols) ...">  <!-- ... --></div>`
This is just a shorthand for `auto-cols-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `grid-auto-columns` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid grid-flow-col auto-cols-max md:auto-cols-min ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/grid-auto-columns

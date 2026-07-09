---
type: Web Page
title: grid-auto-rows - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling the size of implicitly-created grid rows.
resource: https://tailwindcss.com/docs/grid-auto-rows
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Flexbox & Grid

Utilities for controlling the size of implicitly-created grid rows.

| Class | Styles | 
|---|---|
| `auto-rows-auto` | `grid-auto-rows: auto;` | 
| `auto-rows-min` | `grid-auto-rows: min-content;` | 
| `auto-rows-max` | `grid-auto-rows: max-content;` | 
| `auto-rows-fr` | `grid-auto-rows: minmax(0, 1fr);` | 
| `auto-rows-` | `grid-auto-rows: calc(var(--spacing) * ` | 
| `auto-rows-(` | `grid-auto-rows: var(` | 
| `auto-rows-[` | `grid-auto-rows: ` | 

Use utilities like `auto-rows-min` and `auto-rows-max` to control the size of implicitly-created grid rows:

`<div class="grid grid-flow-row auto-rows-max">  <div>01</div>  <div>02</div>  <div>03</div></div>`Use the `auto-rows-[` syntax to set the size of implicitly-created grid rows based on a completely custom value:`<value>`]

`<div class="auto-rows-[minmax(0,2fr)] ...">  <!-- ... --></div>`For CSS variables, you can also use the `auto-rows-(` syntax:`<custom-property>`)

`<div class="auto-rows-(--my-auto-rows) ...">  <!-- ... --></div>`This is just a shorthand for `auto-rows-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `grid-auto-rows` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid grid-flow-row auto-rows-max md:auto-rows-min ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/grid-auto-rows

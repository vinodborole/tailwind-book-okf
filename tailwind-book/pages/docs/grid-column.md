---
type: Web Page
title: grid-column - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how elements are sized and placed across grid
  columns.
resource: https://tailwindcss.com/docs/grid-column
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for controlling how elements are sized and placed across grid columns.

| Class | Styles | 
|---|---|
| `col-span-` | `grid-column: span ` | 
| `col-span-full` | `grid-column: 1 / -1;` | 
| `col-span-(` | `grid-column: span var(` | 
| `col-span-[` | `grid-column: span ` | 
| `col-start-` | `grid-column-start: ` | 
| `-col-start-` | `grid-column-start: calc(` | 
| `col-start-auto` | `grid-column-start: auto;` | 
| `col-start-(` | `grid-column-start: var(` | 
| `col-start-[` | `grid-column-start: ` | 
| `col-end-` | `grid-column-end: ` | 
| `-col-end-` | `grid-column-end: calc(` | 
| `col-end-auto` | `grid-column-end: auto;` | 
| `col-end-(` | `grid-column-end: var(` | 
| `col-end-[` | `grid-column-end: ` | 
| `col-auto` | `grid-column: auto;` | 
| `col-` | `grid-column: ` | 
| `-col-` | `grid-column: calc(` | 
| `col-(` | `grid-column: var(` | 
| `col-[` | `grid-column: ` | 

Use `col-span-` utilities like `<number>``col-span-2` and `col-span-4` to make an element span *n* columns:

Use `col-start-` or `<number>``col-end-` utilities like `<number>``col-start-2` and `col-end-3` to make an element start or end at the *nth* grid line:

These can also be combined with the `col-span-` utilities to span a specific number of columns.`<number>`

Use utilities like `col-[`,`<value>`]`col-span-[`,`<value>`]`col-start-[`, and `<value>`]`col-end-[` to set the grid column size and location based on a completely custom value:`<value>`]

`<div class="col-[16_/_span_16] ...">  <!-- ... --></div>`For CSS variables, you can also use the `col-(` syntax:`<custom-property>`)

`<div class="col-(--my-columns) ...">  <!-- ... --></div>`This is just a shorthand for `col-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix `grid-column`,`grid-column-start`, and `grid-column-end` utilities with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="col-span-2 md:col-span-6 ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/grid-column

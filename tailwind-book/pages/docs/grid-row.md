---
type: Web Page
title: grid-row - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how elements are sized and placed across grid
  rows.
resource: https://tailwindcss.com/docs/grid-row
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Flexbox & Grid

Utilities for controlling how elements are sized and placed across grid rows.

| Class | Styles | 
|---|---|
| `row-span-` | `grid-row: span ` | 
| `row-span-full` | `grid-row: 1 / -1;` | 
| `row-span-(` | `grid-row: span var(` | 
| `row-span-[` | `grid-row: span ` | 
| `row-start-` | `grid-row-start: ` | 
| `-row-start-` | `grid-row-start: calc(` | 
| `row-start-auto` | `grid-row-start: auto;` | 
| `row-start-(` | `grid-row-start: var(` | 
| `row-start-[` | `grid-row-start: ` | 
| `row-end-` | `grid-row-end: ` | 
| `-row-end-` | `grid-row-end: calc(` | 
| `row-end-auto` | `grid-row-end: auto;` | 
| `row-end-(` | `grid-row-end: var(` | 
| `row-end-[` | `grid-row-end: ` | 
| `row-auto` | `grid-row: auto;` | 
| `row-` | `grid-row: ` | 
| `-row-` | `grid-row: calc(` | 
| `row-(` | `grid-row: var(` | 
| `row-[` | `grid-row: ` | 

Use `row-span-` utilities like `<number>``row-span-2` and `row-span-4` to make an element span *n* rows:

Use `row-start-` or `<number>``row-end-` utilities like `<number>``row-start-2` and `row-end-3` to make an element start or end at the *nth* grid line:

These can also be combined with the `row-span-` utilities to span a specific number of rows.`<number>`

Use utilities like `row-[`,`<value>`]`row-span-[`,`<value>`]`row-start-[`, and `<value>`]`row-end-[` to set the grid row size and location based on a completely custom value:`<value>`]

`<div class="row-[span_16_/_span_16] ...">  <!-- ... --></div>`For CSS variables, you can also use the `row-(` syntax:`<custom-property>`)

`<div class="row-(--my-rows) ...">  <!-- ... --></div>`This is just a shorthand for `row-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix `grid-row`,`grid-row-start`, and `grid-row-end` utilities with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="row-span-3 md:row-span-4 ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/grid-row

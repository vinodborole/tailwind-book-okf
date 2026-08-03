---
type: Web Page
title: grid-column - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how elements are sized and placed across grid
  columns.
resource: https://tailwindcss.com/docs/grid-column
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Flexbox & Grid

Utilities for controlling how elements are sized and placed across grid columns.

| Class | Styles | 
|---|---|
| `col-span-``<number>` | `grid-column: span` `<number>` / span`<number>` ; | 
| `col-span-full` | `grid-column: 1 / -1;` | 
| `col-span-(``<custom-property>` ) | `grid-column: span var(``<custom-property>` ) / span var(`<custom-property>` ); | 
| `col-span-[``<value>` ] | `grid-column: span` `<value>` / span`<value>` ; | 
| `col-start-``<number>` | `grid-column-start:` `<number>` ; | 
| `-col-start-``<number>` | `grid-column-start: calc(``<number>` * -1); | 
| `col-start-auto` | `grid-column-start: auto;` | 
| `col-start-(``<custom-property>` ) | `grid-column-start: var(``<custom-property>` ); | 
| `col-start-[``<value>` ] | `grid-column-start:` `<value>` ; | 
| `col-end-``<number>` | `grid-column-end:` `<number>` ; | 
| `-col-end-``<number>` | `grid-column-end: calc(``<number>` * -1); | 
| `col-end-auto` | `grid-column-end: auto;` | 
| `col-end-(``<custom-property>` ) | `grid-column-end: var(``<custom-property>` ); | 
| `col-end-[``<value>` ] | `grid-column-end:` `<value>` ; | 
| `col-auto` | `grid-column: auto;` | 
| `col-``<number>` | `grid-column:` `<number>` ; | 
| `-col-``<number>` | `grid-column: calc(``<number>` * -1); | 
| `col-(``<custom-property>` ) | `grid-column: var(``<custom-property>` ); | 
| `col-[``<value>` ] | `grid-column:` `<value>` ; | 

Use `col-span-` utilities like `<number>``col-span-2` and `col-span-4` to make an element span *n* columns:

Use `col-start-` or `<number>``col-end-` utilities like `<number>``col-start-2` and `col-end-3` to make an element start or end at the *nth* grid line:

These can also be combined with the `col-span-` utilities to span a specific number of columns.`<number>`

Use utilities like `col-[`,`<value>`]`col-span-[`,`<value>`]`col-start-[`, and `<value>`]`col-end-[` to set the grid column size and location based on a completely custom value:`<value>`]

`<div class="col-[16_/_span_16] ...">  <!-- ... --></div>`
For CSS variables, you can also use the `col-(` syntax:`<custom-property>`)

`<div class="col-(--my-columns) ...">  <!-- ... --></div>`
This is just a shorthand for `col-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix `grid-column`,`grid-column-start`, and `grid-column-end` utilities with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="col-span-2 md:col-span-6 ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/grid-column

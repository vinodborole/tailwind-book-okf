---
type: Web Page
title: grid-row - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how elements are sized and placed across grid
  rows.
resource: https://tailwindcss.com/docs/grid-row
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Flexbox & Grid

Utilities for controlling how elements are sized and placed across grid rows.

| Class | Styles | 
|---|---|
| `row-span-``<number>` | `grid-row: span` `<number>` / span`<number>` ; | 
| `row-span-full` | `grid-row: 1 / -1;` | 
| `row-span-(``<custom-property>` ) | `grid-row: span var(``<custom-property>` ) / span var(`<custom-property>` ); | 
| `row-span-[``<value>` ] | `grid-row: span` `<value>` / span`<value>` ; | 
| `row-start-``<number>` | `grid-row-start:` `<number>` ; | 
| `-row-start-``<number>` | `grid-row-start: calc(``<number>` * -1); | 
| `row-start-auto` | `grid-row-start: auto;` | 
| `row-start-(``<custom-property>` ) | `grid-row-start: var(``<custom-property>` ); | 
| `row-start-[``<value>` ] | `grid-row-start:` `<value>` ; | 
| `row-end-``<number>` | `grid-row-end:` `<number>` ; | 
| `-row-end-``<number>` | `grid-row-end: calc(``<number>` * -1); | 
| `row-end-auto` | `grid-row-end: auto;` | 
| `row-end-(``<custom-property>` ) | `grid-row-end: var(``<custom-property>` ); | 
| `row-end-[``<value>` ] | `grid-row-end:` `<value>` ; | 
| `row-auto` | `grid-row: auto;` | 
| `row-``<number>` | `grid-row:` `<number>` ; | 
| `-row-``<number>` | `grid-row: calc(``<number>` * -1); | 
| `row-(``<custom-property>` ) | `grid-row: var(``<custom-property>` ); | 
| `row-[``<value>` ] | `grid-row:` `<value>` ; | 

Use `row-span-` utilities like `<number>``row-span-2` and `row-span-4` to make an element span *n* rows:

Use `row-start-` or `<number>``row-end-` utilities like `<number>``row-start-2` and `row-end-3` to make an element start or end at the *nth* grid line:

These can also be combined with the `row-span-` utilities to span a specific number of rows.`<number>`

Use utilities like `row-[`,`<value>`]`row-span-[`,`<value>`]`row-start-[`, and `<value>`]`row-end-[` to set the grid row size and location based on a completely custom value:`<value>`]

`<div class="row-[span_16_/_span_16] ...">  <!-- ... --></div>`
For CSS variables, you can also use the `row-(` syntax:`<custom-property>`)

`<div class="row-(--my-rows) ...">  <!-- ... --></div>`
This is just a shorthand for `row-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix `grid-row`,`grid-row-start`, and `grid-row-end` utilities with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="row-span-3 md:row-span-4 ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/grid-row

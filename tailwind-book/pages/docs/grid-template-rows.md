---
type: Web Page
title: grid-template-rows - Flexbox & Grid - Tailwind CSS
description: Utilities for specifying the rows in a grid layout.
resource: https://tailwindcss.com/docs/grid-template-rows
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Flexbox & Grid

Utilities for specifying the rows in a grid layout.

| Class | Styles | 
|---|---|
| `grid-rows-``<number>` | `grid-template-rows: repeat(``<number>` , minmax(0, 1fr)); | 
| `grid-rows-none` | `grid-template-rows: none;` | 
| `grid-rows-subgrid` | `grid-template-rows: subgrid;` | 
| `grid-rows-[``<value>` ] | `grid-template-rows:` `<value>` ; | 
| `grid-rows-(``<custom-property>` ) | `grid-template-rows: var(``<custom-property>` ); | 

Use `grid-rows-` utilities like `<number>``grid-rows-2` and `grid-rows-4` to create grids with *n* equally sized rows:

Use the `grid-rows-subgrid` utility to adopt the row tracks defined by the item's parent:

Use the `grid-rows-[` syntax to set the rows based on a completely custom value:`<value>`]

`<div class="grid-rows-[200px_minmax(900px,1fr)_100px] ...">  <!-- ... --></div>`
For CSS variables, you can also use the `grid-rows-(` syntax:`<custom-property>`)

`<div class="grid-rows-(--my-grid-rows) ...">  <!-- ... --></div>`
This is just a shorthand for `grid-rows-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `grid-template-rows` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid grid-rows-2 md:grid-rows-6 ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/grid-template-rows

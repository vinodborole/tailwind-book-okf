---
type: Web Page
title: grid-template-rows - Flexbox & Grid - Tailwind CSS
description: Utilities for specifying the rows in a grid layout.
resource: https://tailwindcss.com/docs/grid-template-rows
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for specifying the rows in a grid layout.

| Class | Styles | 
|---|---|
| `grid-rows-` | `grid-template-rows: repeat(` | 
| `grid-rows-none` | `grid-template-rows: none;` | 
| `grid-rows-subgrid` | `grid-template-rows: subgrid;` | 
| `grid-rows-[` | `grid-template-rows: ` | 
| `grid-rows-(` | `grid-template-rows: var(` | 

Use `grid-rows-` utilities like `<number>``grid-rows-2` and `grid-rows-4` to create grids with *n* equally sized rows:

Use the `grid-rows-subgrid` utility to adopt the row tracks defined by the item's parent:

Use the `grid-rows-[` syntax to set the rows based on a completely custom value:`<value>`]

`<div class="grid-rows-[200px_minmax(900px,1fr)_100px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `grid-rows-(` syntax:`<custom-property>`)

`<div class="grid-rows-(--my-grid-rows) ...">  <!-- ... --></div>`This is just a shorthand for `grid-rows-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `grid-template-rows` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid grid-rows-2 md:grid-rows-6 ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/grid-template-rows

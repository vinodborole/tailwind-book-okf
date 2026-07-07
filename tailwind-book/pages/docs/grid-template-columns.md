---
type: Web Page
title: grid-template-columns - Flexbox & Grid - Tailwind CSS
description: Utilities for specifying the columns in a grid layout.
resource: https://tailwindcss.com/docs/grid-template-columns
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for specifying the columns in a grid layout.

| Class | Styles | 
|---|---|
| `grid-cols-` | `grid-template-columns: repeat(` | 
| `grid-cols-none` | `grid-template-columns: none;` | 
| `grid-cols-subgrid` | `grid-template-columns: subgrid;` | 
| `grid-cols-[` | `grid-template-columns: ` | 
| `grid-cols-(` | `grid-template-columns: var(` | 

Use `grid-cols-` utilities like `<number>``grid-cols-2` and `grid-cols-4` to create grids with *n* equally sized columns:

Use the `grid-cols-subgrid` utility to adopt the column tracks defined by the item's parent:

Use the `grid-cols-[` syntax to set the columns based on a completely custom value:`<value>`]

`<div class="grid-cols-[200px_minmax(900px,_1fr)_100px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `grid-cols-(` syntax:`<custom-property>`)

`<div class="grid-cols-(--my-grid-cols) ...">  <!-- ... --></div>`This is just a shorthand for `grid-cols-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `grid-template-columns` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid grid-cols-1 md:grid-cols-6 ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/grid-template-columns

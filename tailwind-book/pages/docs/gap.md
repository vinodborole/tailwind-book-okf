---
type: Web Page
title: gap - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling gutters between grid and flexbox items.
resource: https://tailwindcss.com/docs/gap
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for controlling gutters between grid and flexbox items.

| Class | Styles | 
|---|---|
| `gap-` | `gap: calc(var(--spacing) * ` | 
| `gap-(` | `gap: var(` | 
| `gap-[` | `gap: ` | 
| `gap-x-` | `column-gap: calc(var(--spacing) * ` | 
| `gap-x-(` | `column-gap: var(` | 
| `gap-x-[` | `column-gap: ` | 
| `gap-y-` | `row-gap: calc(var(--spacing) * ` | 
| `gap-y-(` | `row-gap: var(` | 
| `gap-y-[` | `row-gap: ` | 

Use `gap-` utilities like `<number>``gap-2` and `gap-4` to change the gap between both rows and columns in grid and flexbox layouts:

Use `gap-x-` or `<number>``gap-y-` utilities like `<number>``gap-x-8` and `gap-y-4` to change the gap between columns and rows independently:

Use utilities like `gap-[`,`<value>`]`gap-x-[`, and `<value>`]`gap-y-[` to set the gap based on a completely custom value:`<value>`]

`<div class="gap-[10vw] ...">  <!-- ... --></div>`For CSS variables, you can also use the `gap-(` syntax:`<custom-property>`)

`<div class="gap-(--my-gap) ...">  <!-- ... --></div>`This is just a shorthand for `gap-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix `gap`,`column-gap`, and `row-gap` utilities with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid gap-4 md:gap-6 ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/gap

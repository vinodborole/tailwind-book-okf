---
type: Web Page
title: order - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling the order of flex and grid items.
resource: https://tailwindcss.com/docs/order
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for controlling the order of flex and grid items.

| Class | Styles | 
|---|---|
| `order-` | `order: ` | 
| `-order-` | `order: calc(` | 
| `order-first` | `order: -9999;` | 
| `order-last` | `order: 9999;` | 
| `order-none` | `order: 0;` | 
| `order-(` | `order: var(` | 
| `order-[` | `order: ` | 

Use `order-` utilities like `<number>``order-1` and `order-3` to render flex and grid items in a different order than they appear in the document:

Use the `order-first` and `order-last` utilities to render flex and grid items first or last:

To use a negative order value, prefix the class name with a dash to convert it to a negative value:

`<div class="-order-1">  <!-- ... --></div>`Use the `order-[` syntax to set the order based on a completely custom value:`<value>`]

`<div class="order-[min(var(--total-items),10)] ...">  <!-- ... --></div>`For CSS variables, you can also use the `order-(` syntax:`<custom-property>`)

`<div class="order-(--my-order) ...">  <!-- ... --></div>`This is just a shorthand for `order-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix an `order` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="order-first md:order-last ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/order

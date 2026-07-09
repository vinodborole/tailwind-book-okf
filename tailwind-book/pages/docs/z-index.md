---
type: Web Page
title: z-index - Layout - Tailwind CSS
description: Utilities for controlling the stack order of an element.
resource: https://tailwindcss.com/docs/z-index
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Layout

Utilities for controlling the stack order of an element.

| Class | Styles | 
|---|---|
| `z-` | `z-index: ` | 
| `z-auto` | `z-index: auto;` | 
| `z-[` | `z-index: ` | 
| `z-(` | `z-index: var(` | 

Use the `z-` utilities like `<number>``z-10` and `z-50` to control the stack order (or three-dimensional positioning) of an element, regardless of the order it has been displayed:

To use a negative z-index value, prefix the class name with a dash to convert it to a negative value:

Use the `z-[` syntax to set the stack order based on a completely custom value:`<value>`]

`<div class="z-[calc(var(--index)+1)] ...">  <!-- ... --></div>`For CSS variables, you can also use the `z-(` syntax:`<custom-property>`)

`<div class="z-(--my-z) ...">  <!-- ... --></div>`This is just a shorthand for `z-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `z-index` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="z-0 md:z-50 ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/z-index

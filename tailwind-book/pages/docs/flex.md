---
type: Web Page
title: flex - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how flex items both grow and shrink.
resource: https://tailwindcss.com/docs/flex
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Flexbox & Grid

Utilities for controlling how flex items both grow and shrink.

| Class | Styles | 
|---|---|
| `flex-` | `flex: ` | 
| `flex-` | `flex: calc(` | 
| `flex-auto` | `flex: auto;` | 
| `flex-initial` | `flex: 0 auto;` | 
| `flex-none` | `flex: none;` | 
| `flex-(` | `flex: var(` | 
| `flex-[` | `flex: ` | 

Use `flex-` utilities like `<number>``flex-1` to allow a flex item to grow and shrink as needed, ignoring its initial size:

Use `flex-initial` to allow a flex item to shrink but not grow, taking into account its initial size:

Use `flex-auto` to allow a flex item to grow and shrink, taking into account its initial size:

Use `flex-none` to prevent a flex item from growing or shrinking:

Use the `flex-[` syntax to set the flex shorthand property based on a completely custom value:`<value>`]

`<div class="flex-[3_1_auto] ...">  <!-- ... --></div>`For CSS variables, you can also use the `flex-(` syntax:`<custom-property>`)

`<div class="flex-(--my-flex) ...">  <!-- ... --></div>`This is just a shorthand for `flex-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `flex` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="flex-none md:flex-1 ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/flex

---
type: Web Page
title: flex-grow - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how flex items grow.
resource: https://tailwindcss.com/docs/flex-grow
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Flexbox & Grid

Utilities for controlling how flex items grow.

| Class | Styles | 
|---|---|
| `grow` | `flex-grow: 1;` | 
| `grow-``<number>` | `flex-grow:` `<number>` ; | 
| `grow-[``<value>` ] | `flex-grow:` `<value>` ; | 
| `grow-(``<custom-property>` ) | `flex-grow: var(``<custom-property>` ); | 

Use `grow` to allow a flex item to grow to fill any available space:

Use `grow-` utilities like `<number>``grow-3` to make flex items grow proportionally based on their growth factor, allowing them to fill the available space relative to each other:

Use `grow-0` to prevent a flex item from growing:

Use the `grow-[` syntax to set the flex grow factor based on a completely custom value:`<value>`]

`<div class="grow-[25vw] ...">  <!-- ... --></div>`
For CSS variables, you can also use the `grow-(` syntax:`<custom-property>`)

`<div class="grow-(--my-grow) ...">  <!-- ... --></div>`
This is just a shorthand for `grow-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `flex-grow` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grow md:grow-0 ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/flex-grow

---
type: Web Page
title: flex-shrink - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how flex items shrink.
resource: https://tailwindcss.com/docs/flex-shrink
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Flexbox & Grid

Utilities for controlling how flex items shrink.

| Class | Styles | 
|---|---|
| `shrink` | `flex-shrink: 1;` | 
| `shrink-` | `flex-shrink: ` | 
| `shrink-[` | `flex-shrink: ` | 
| `shrink-(` | `flex-shrink: var(` | 

Use `shrink` to allow a flex item to shrink if needed:

Use `shrink-0` to prevent a flex item from shrinking:

Use the `shrink-[` syntax to set the flex shrink factor based on a completely custom value:`<value>`]

`<div class="shrink-[calc(100vw-var(--sidebar))] ...">  <!-- ... --></div>`For CSS variables, you can also use the `shrink-(` syntax:`<custom-property>`)

`<div class="shrink-(--my-shrink) ...">  <!-- ... --></div>`This is just a shorthand for `shrink-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `flex-shrink` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="shrink md:shrink-0 ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/flex-shrink

---
type: Web Page
title: padding - Spacing - Tailwind CSS
description: Utilities for controlling an element's padding.
resource: https://tailwindcss.com/docs/padding
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Spacing

Utilities for controlling an element's padding.

| Class | Styles | 
|---|---|
| `p-` | `padding: calc(var(--spacing) * ` | 
| `p-px` | `padding: 1px;` | 
| `p-(` | `padding: var(` | 
| `p-[` | `padding: ` | 
| `px-` | `padding-inline: calc(var(--spacing) * ` | 
| `px-px` | `padding-inline: 1px;` | 
| `px-(` | `padding-inline: var(` | 
| `px-[` | `padding-inline: ` | 
| `py-` | `padding-block: calc(var(--spacing) * ` | 
| `py-px` | `padding-block: 1px;` | 
| `py-(` | `padding-block: var(` | 
| `py-[` | `padding-block: ` | 
| `ps-` | `padding-inline-start: calc(var(--spacing) * ` | 
| `ps-px` | `padding-inline-start: 1px;` | 
| `ps-(` | `padding-inline-start: var(` | 
| `ps-[` | `padding-inline-start: ` | 
| `pe-` | `padding-inline-end: calc(var(--spacing) * ` | 
| `pe-px` | `padding-inline-end: 1px;` | 
| `pe-(` | `padding-inline-end: var(` | 
| `pe-[` | `padding-inline-end: ` | 
| `pbs-` | `padding-block-start: calc(var(--spacing) * ` | 
| `pbs-px` | `padding-block-start: 1px;` | 
| `pbs-(` | `padding-block-start: var(` | 
| `pbs-[` | `padding-block-start: ` | 
| `pbe-` | `padding-block-end: calc(var(--spacing) * ` | 
| `pbe-px` | `padding-block-end: 1px;` | 
| `pbe-(` | `padding-block-end: var(` | 
| `pbe-[` | `padding-block-end: ` | 
| `pt-` | `padding-top: calc(var(--spacing) * ` | 
| `pt-px` | `padding-top: 1px;` | 
| `pt-(` | `padding-top: var(` | 
| `pt-[` | `padding-top: ` | 
| `pr-` | `padding-right: calc(var(--spacing) * ` | 
| `pr-px` | `padding-right: 1px;` | 
| `pr-(` | `padding-right: var(` | 
| `pr-[` | `padding-right: ` | 
| `pb-` | `padding-bottom: calc(var(--spacing) * ` | 
| `pb-px` | `padding-bottom: 1px;` | 
| `pb-(` | `padding-bottom: var(` | 
| `pb-[` | `padding-bottom: ` | 
| `pl-` | `padding-left: calc(var(--spacing) * ` | 
| `pl-px` | `padding-left: 1px;` | 
| `pl-(` | `padding-left: var(` | 
| `pl-[` | `padding-left: ` | 

Use `p-` utilities like `<number>``p-4` and `p-8` to control the padding on all sides of an element:

Use `pt-`, `<number>``pr-`, `<number>``pb-`, and `<number>``pl-` utilities like `<number>``pt-6` and `pr-4` to control the padding on one side of an element:

Use `px-` utilities like `<number>``px-4` and `px-8` to control the horizontal padding of an element:

Use `py-` utilities like `<number>``py-4` and `py-8` to control the vertical padding of an element:

Use `ps-` or `<number>``pe-` utilities like `<number>``ps-4` and `pe-8` to set the `padding-inline-start` and `padding-inline-end` logical properties, which map to either the left or right side based on the text direction:

For more control, you can also use the LTR and RTL modifiers to conditionally apply specific styles depending on the current text direction.

Use the `pbs-` and `<number>``pbe-` utilities to set the `<number>``padding-block-start` and `padding-block-end` logical properties, which map to either the top or bottom side based on the writing mode:

`<div class="pbs-8 ...">pbs-8</div>`Use utilities like `p-[`,`<value>`]`px-[`, and `<value>`]`pb-[` to set the padding based on a completely custom value:`<value>`]

`<div class="p-[5px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `p-(` syntax:`<custom-property>`)

`<div class="p-(--my-padding) ...">  <!-- ... --></div>`This is just a shorthand for `p-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `padding` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="py-4 md:py-8 ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

The `p-`,`<number>``px-`,`<number>``py-`,`<number>``ps-`,`<number>``pe-`,`<number>``pbs-`,`<number>``pbe-`,`<number>``pt-`,`<number>``pr-`,`<number>``pb-`, and `<number>``pl-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the theme variable documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/padding

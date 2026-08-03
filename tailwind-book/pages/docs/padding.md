---
type: Web Page
title: padding - Spacing - Tailwind CSS
description: Utilities for controlling an element's padding.
resource: https://tailwindcss.com/docs/padding
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Spacing

Utilities for controlling an element's padding.

| Class | Styles | 
|---|---|
| `p-``<number>` | `padding: calc(var(--spacing) *` `<number>` ); | 
| `p-px` | `padding: 1px;` | 
| `p-(``<custom-property>` ) | `padding: var(``<custom-property>` ); | 
| `p-[``<value>` ] | `padding:` `<value>` ; | 
| `px-``<number>` | `padding-inline: calc(var(--spacing) *` `<number>` ); | 
| `px-px` | `padding-inline: 1px;` | 
| `px-(``<custom-property>` ) | `padding-inline: var(``<custom-property>` ); | 
| `px-[``<value>` ] | `padding-inline:` `<value>` ; | 
| `py-``<number>` | `padding-block: calc(var(--spacing) *` `<number>` ); | 
| `py-px` | `padding-block: 1px;` | 
| `py-(``<custom-property>` ) | `padding-block: var(``<custom-property>` ); | 
| `py-[``<value>` ] | `padding-block:` `<value>` ; | 
| `ps-``<number>` | `padding-inline-start: calc(var(--spacing) *` `<number>` ); | 
| `ps-px` | `padding-inline-start: 1px;` | 
| `ps-(``<custom-property>` ) | `padding-inline-start: var(``<custom-property>` ); | 
| `ps-[``<value>` ] | `padding-inline-start:` `<value>` ; | 
| `pe-``<number>` | `padding-inline-end: calc(var(--spacing) *` `<number>` ); | 
| `pe-px` | `padding-inline-end: 1px;` | 
| `pe-(``<custom-property>` ) | `padding-inline-end: var(``<custom-property>` ); | 
| `pe-[``<value>` ] | `padding-inline-end:` `<value>` ; | 
| `pbs-``<number>` | `padding-block-start: calc(var(--spacing) *` `<number>` ); | 
| `pbs-px` | `padding-block-start: 1px;` | 
| `pbs-(``<custom-property>` ) | `padding-block-start: var(``<custom-property>` ); | 
| `pbs-[``<value>` ] | `padding-block-start:` `<value>` ; | 
| `pbe-``<number>` | `padding-block-end: calc(var(--spacing) *` `<number>` ); | 
| `pbe-px` | `padding-block-end: 1px;` | 
| `pbe-(``<custom-property>` ) | `padding-block-end: var(``<custom-property>` ); | 
| `pbe-[``<value>` ] | `padding-block-end:` `<value>` ; | 
| `pt-``<number>` | `padding-top: calc(var(--spacing) *` `<number>` ); | 
| `pt-px` | `padding-top: 1px;` | 
| `pt-(``<custom-property>` ) | `padding-top: var(``<custom-property>` ); | 
| `pt-[``<value>` ] | `padding-top:` `<value>` ; | 
| `pr-``<number>` | `padding-right: calc(var(--spacing) *` `<number>` ); | 
| `pr-px` | `padding-right: 1px;` | 
| `pr-(``<custom-property>` ) | `padding-right: var(``<custom-property>` ); | 
| `pr-[``<value>` ] | `padding-right:` `<value>` ; | 
| `pb-``<number>` | `padding-bottom: calc(var(--spacing) *` `<number>` ); | 
| `pb-px` | `padding-bottom: 1px;` | 
| `pb-(``<custom-property>` ) | `padding-bottom: var(``<custom-property>` ); | 
| `pb-[``<value>` ] | `padding-bottom:` `<value>` ; | 
| `pl-``<number>` | `padding-left: calc(var(--spacing) *` `<number>` ); | 
| `pl-px` | `padding-left: 1px;` | 
| `pl-(``<custom-property>` ) | `padding-left: var(``<custom-property>` ); | 
| `pl-[``<value>` ] | `padding-left:` `<value>` ; | 

Use `p-` utilities like `<number>``p-4` and `p-8` to control the padding on all sides of an element:

Use `pt-`, `<number>``pr-`, `<number>``pb-`, and `<number>``pl-` utilities like `<number>``pt-6` and `pr-4` to control the padding on one side of an element:

Use `px-` utilities like `<number>``px-4` and `px-8` to control the horizontal padding of an element:

Use `py-` utilities like `<number>``py-4` and `py-8` to control the vertical padding of an element:

Use `ps-` or `<number>``pe-` utilities like `<number>``ps-4` and `pe-8` to set the `padding-inline-start` and `padding-inline-end` logical properties, which map to either the left or right side based on the text direction:

For more control, you can also use the [LTR and RTL modifiers](/docs/hover-focus-and-other-states#rtl-support) to conditionally apply specific styles depending on the current text direction.

Use the `pbs-` and `<number>``pbe-` utilities to set the `<number>``padding-block-start` and `padding-block-end` logical properties, which map to either the top or bottom side based on the writing mode:

`<div class="pbs-8 ...">pbs-8</div>`
Use utilities like `p-[`,`<value>`]`px-[`, and `<value>`]`pb-[` to set the padding based on a completely custom value:`<value>`]

`<div class="p-[5px] ...">  <!-- ... --></div>`
For CSS variables, you can also use the `p-(` syntax:`<custom-property>`)

`<div class="p-(--my-padding) ...">  <!-- ... --></div>`
This is just a shorthand for `p-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `padding` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="py-4 md:py-8 ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `p-`,`<number>``px-`,`<number>``py-`,`<number>``ps-`,`<number>``pe-`,`<number>``pbs-`,`<number>``pbe-`,`<number>``pt-`,`<number>``pr-`,`<number>``pb-`, and `<number>``pl-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`
Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/padding

---
type: Web Page
title: line-height - Typography - Tailwind CSS
description: Utilities for controlling the leading, or line height, of an element.
resource: https://tailwindcss.com/docs/line-height
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Typography

Utilities for controlling the leading, or line height, of an element.

| Class | Styles | 
|---|---|
| `text-``<size>` /`<number>` | `font-size:` `<size>` ; line-height: calc(var(--spacing) *`<number>` ); | 
| `text-``<size>` /(`<custom-property>` ) | `font-size:` `<size>` ; line-height: var(`<custom-property>` ); | 
| `text-``<size>` /[`<value>` ] | `font-size:` `<size>` ; line-height:`<value>` ; | 
| `leading-none` | `line-height: 1;` | 
| `leading-``<number>` | `line-height: calc(var(--spacing) *` `<number>` ); | 
| `leading-(``<custom-property>` ) | `line-height: var(``<custom-property>` ); | 
| `leading-[``<value>` ] | `line-height:` `<value>` ; | 

Use font size utilities like `text-sm/6` and `text-lg/7` to set the font size and line-height of an element at the same time:

Each font size utility also sets a default line height when one isn't provided. You can learn more about these values and how to customize them in the [font-size documentation](/docs/font-size).

Use `leading-` utilities like `<number>``leading-6` and `leading-7` to set the line height of an element independent of the font-size:

Use the `leading-none` utility to set the line height of an element equal to its font size:

Use the `leading-[` syntax to set the line height based on a completely custom value:`<value>`]

`<p class="leading-[1.5] ...">  Lorem ipsum dolor sit amet...</p>`
For CSS variables, you can also use the `leading-(` syntax:`<custom-property>`)

`<p class="leading-(--my-line-height) ...">  Lorem ipsum dolor sit amet...</p>`
This is just a shorthand for `leading-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `line-height` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="leading-5 md:leading-6 ...">  Lorem ipsum dolor sit amet...</p>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `leading-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`
Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/line-height

---
type: Web Page
title: font-weight - Typography - Tailwind CSS
description: Utilities for controlling the font weight of an element.
resource: https://tailwindcss.com/docs/font-weight
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Typography

Utilities for controlling the font weight of an element.

| Class | Styles | 
|---|---|
| `font-thin` | `font-weight: 100;` | 
| `font-extralight` | `font-weight: 200;` | 
| `font-light` | `font-weight: 300;` | 
| `font-normal` | `font-weight: 400;` | 
| `font-medium` | `font-weight: 500;` | 
| `font-semibold` | `font-weight: 600;` | 
| `font-bold` | `font-weight: 700;` | 
| `font-extrabold` | `font-weight: 800;` | 
| `font-black` | `font-weight: 900;` | 
| `font-(` | `font-weight: var(` | 
| `font-[` | `font-weight: ` | 

Use utilities like `font-thin` and `font-bold` to set the font weight of an element:

Use the `font-[` syntax to set the font weight based on a completely custom value:`<value>`]

`<p class="font-[1000] ...">  Lorem ipsum dolor sit amet...</p>`For CSS variables, you can also use the `font-(weight:` syntax:`<custom-property>`)

`<p class="font-(weight:--my-font-weight) ...">  Lorem ipsum dolor sit amet...</p>`This is just a shorthand for `font-[weight:var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `font-weight` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="font-normal md:font-bold ...">  Lorem ipsum dolor sit amet...</p>`Learn more about using variants in the variants documentation.

Use the `--font-weight-*` theme variables to customize the font weight utilities in your project:

`@theme {  --font-weight-extrablack: 1000; }`Now the `font-extrablack` utility can be used in your markup:

`<div class="font-extrablack">  <!-- ... --></div>`Learn more about customizing your theme in the theme documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/font-weight

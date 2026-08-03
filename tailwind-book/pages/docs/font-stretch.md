---
type: Web Page
title: font-stretch - Typography - Tailwind CSS
description: Utilities for selecting the width of a font face.
resource: https://tailwindcss.com/docs/font-stretch
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Typography

Utilities for selecting the width of a font face.

| Class | Styles | 
|---|---|
| `font-stretch-ultra-condensed` | `font-stretch: ultra-condensed; /* 50% */` | 
| `font-stretch-extra-condensed` | `font-stretch: extra-condensed; /* 62.5% */` | 
| `font-stretch-condensed` | `font-stretch: condensed; /* 75% */` | 
| `font-stretch-semi-condensed` | `font-stretch: semi-condensed; /* 87.5% */` | 
| `font-stretch-normal` | `font-stretch: normal; /* 100% */` | 
| `font-stretch-semi-expanded` | `font-stretch: semi-expanded; /* 112.5% */` | 
| `font-stretch-expanded` | `font-stretch: expanded; /* 125% */` | 
| `font-stretch-extra-expanded` | `font-stretch: extra-expanded; /* 150% */` | 
| `font-stretch-ultra-expanded` | `font-stretch: ultra-expanded; /* 200% */` | 
| `font-stretch-``<percentage>` | `font-stretch:` `<percentage>` ; | 
| `font-stretch-(``<custom-property>` ) | `font-stretch: var(``<custom-property>` ); | 
| `font-stretch-[``<value>` ] | `font-stretch:` `<value>` ; | 

Use utilities like `font-stretch-condensed` and `font-stretch-expanded` to set the width of a font face:

This only applies to fonts that have multiple width variations available, otherwise the browser selects the closest match.

Use `font-stretch-` utilities like `<percentage>``font-stretch-50%` and `font-stretch-125%` to set the width of a font face using a percentage:

Use the `font-stretch-[` syntax to set the font width based on a completely custom value:`<value>`]

`<p class="font-stretch-[66.66%] ...">  Lorem ipsum dolor sit amet...</p>`
For CSS variables, you can also use the `font-stretch-(` syntax:`<custom-property>`)

`<p class="font-stretch-(--my-font-width) ...">  Lorem ipsum dolor sit amet...</p>`
This is just a shorthand for `font-stretch-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `font-stretch` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="font-stretch-normal md:font-stretch-expanded ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/font-stretch

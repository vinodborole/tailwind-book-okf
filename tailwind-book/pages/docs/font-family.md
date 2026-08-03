---
type: Web Page
title: font-family - Typography - Tailwind CSS
description: Utilities for controlling the font family of an element.
resource: https://tailwindcss.com/docs/font-family
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Typography

Utilities for controlling the font family of an element.

| Class | Styles | 
|---|---|
| `font-sans` | `font-family: var(--font-sans); /* -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji' */` | 
| `font-serif` | `font-family: var(--font-serif); /* ui-serif, Georgia, Cambria, 'Times New Roman', Times, serif */` | 
| `font-mono` | `font-family: var(--font-mono); /* ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace */` | 
| `font-(family-name:``<custom-property>` ) | `font-family: var(``<custom-property>` ); | 
| `font-[``<value>` ] | `font-family:` `<value>` ; | 

Use utilities like `font-sans` and `font-mono` to set the font family of an element:

Use the `font-[` syntax to set the font family based on a completely custom value:`<value>`]

`<p class="font-[Open_Sans] ...">  Lorem ipsum dolor sit amet...</p>`
For CSS variables, you can also use the `font-(family-name:` syntax:`<custom-property>`)

`<p class="font-(family-name:--my-font) ...">  Lorem ipsum dolor sit amet...</p>`
This is just a shorthand for `font-[family-name:var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `font-family` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="font-sans md:font-serif ...">  Lorem ipsum dolor sit amet...</p>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

Use the `--font-*` theme variables to customize the font family utilities in your project:

`@theme {  --font-display: "Oswald", sans-serif; }`
Now the `font-display` utility can be used in your markup:

`<div class="font-display">  <!-- ... --></div>`
You can also provide default `font-feature-settings` and `font-variation-settings` values for a font family:

`@theme {  --font-display: "Oswald", sans-serif;  --font-display--font-feature-settings: "cv02", "cv03", "cv04", "cv11";   --font-display--font-variation-settings: "opsz" 32; }`
If needed, use the [@font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face) at-rule to load custom fonts:

`@font-face {  font-family: Oswald;  font-style: normal;  font-weight: 200 700;  font-display: swap;  src: url("/fonts/Oswald.woff2") format("woff2");}`
If you're loading a font from a service like [Google Fonts](https://fonts.google.com/), make sure to put the `@import` at the very top of your CSS file:

`@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");@import "tailwindcss";@theme {  --font-roboto: "Roboto", sans-serif; }`
Browsers require that `@import` statements come before any other rules, so URL imports need to be above imports like `@import "tailwindcss"` which are inlined in the compiled CSS.

Learn more about customizing your theme in the [theme documentation](/docs/theme#customizing-your-theme).

# Citations

1. Source page: https://tailwindcss.com/docs/font-family

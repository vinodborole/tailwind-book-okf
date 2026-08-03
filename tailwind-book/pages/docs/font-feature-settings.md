---
type: Web Page
title: font-feature-settings - Typography - Tailwind CSS
description: Utilities for controlling advanced typographic features.
resource: https://tailwindcss.com/docs/font-feature-settings
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Typography

Utilities for controlling advanced typographic features.

| Class | Styles | 
|---|---|
| `font-features-[``<value>` ] | `font-feature-settings:` `<value>` ; | 
| `font-features-(``<custom-property>` ) | `font-feature-settings: var(``<custom-property>` ); | 

Use the `font-features-[` utility to enable OpenType features in fonts that support them:`<value>`]

`<p class="font-features-['smcp'] ...">This text uses small caps.</p>`
You can enable multiple OpenType features by separating them with commas:

`<p class="font-features-['smcp','onum'] ...">This text uses small caps and oldstyle numbers.</p>`
Use the `font-features-(` syntax to apply font feature settings from a CSS variable:`<custom-property>`)

`<p class="font-features-(--my-features) ...">  <!-- ... --></p>`
Prefix a `font-feature-settings` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="font-features-['tnum'] md:font-features-['smcp'] ...">  Lorem ipsum dolor sit amet...</p>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/font-feature-settings

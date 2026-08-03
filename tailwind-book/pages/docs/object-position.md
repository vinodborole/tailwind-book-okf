---
type: Web Page
title: object-position - Layout - Tailwind CSS
description: Utilities for controlling how a replaced element's content should be
  positioned within its container.
resource: https://tailwindcss.com/docs/object-position
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Layout

Utilities for controlling how a replaced element's content should be positioned within its container.

| Class | Styles | 
|---|---|
| `object-top-left` | `object-position: top left;` | 
| `object-top` | `object-position: top;` | 
| `object-top-right` | `object-position: top right;` | 
| `object-left` | `object-position: left;` | 
| `object-center` | `object-position: center;` | 
| `object-right` | `object-position: right;` | 
| `object-bottom-left` | `object-position: bottom left;` | 
| `object-bottom` | `object-position: bottom;` | 
| `object-bottom-right` | `object-position: bottom right;` | 
| `object-(``<custom-property>` ) | `object-position: var(``<custom-property>` ); | 
| `object-[``<value>` ] | `object-position:` `<value>` ; | 

Use utilities like `object-left` and `object-bottom-right` to specify how a replaced element's content should be positioned within its container:

Hover over examples to see the full image

Use the `object-[` syntax to set the object position based on a completely custom value:`<value>`]

`<img class="object-[25%_75%] ..." src="/img/mountains.jpg" />`
For CSS variables, you can also use the `object-(` syntax:`<custom-property>`)

`<img class="object-(--my-object) ..." src="/img/mountains.jpg" />`
This is just a shorthand for `object-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix an `object-position` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<img class="object-center md:object-top ..." src="/img/mountains.jpg" />`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/object-position

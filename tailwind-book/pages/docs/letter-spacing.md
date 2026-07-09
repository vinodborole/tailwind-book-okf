---
type: Web Page
title: letter-spacing - Typography - Tailwind CSS
description: Utilities for controlling the tracking, or letter spacing, of an element.
resource: https://tailwindcss.com/docs/letter-spacing
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Typography

Utilities for controlling the tracking, or letter spacing, of an element.

| Class | Styles | 
|---|---|
| `tracking-tighter` | `letter-spacing: var(--tracking-tighter); /* -0.05em */` | 
| `tracking-tight` | `letter-spacing: var(--tracking-tight); /* -0.025em */` | 
| `tracking-normal` | `letter-spacing: var(--tracking-normal); /* 0em */` | 
| `tracking-wide` | `letter-spacing: var(--tracking-wide); /* 0.025em */` | 
| `tracking-wider` | `letter-spacing: var(--tracking-wider); /* 0.05em */` | 
| `tracking-widest` | `letter-spacing: var(--tracking-widest); /* 0.1em */` | 
| `tracking-(` | `letter-spacing: var(` | 
| `tracking-[` | `letter-spacing: ` | 

Use utilities like `tracking-tight` and `tracking-wide` to set the letter spacing of an element:

Using negative values doesn't make a ton of sense with the named letter spacing scale Tailwind includes out of the box, but if you've customized your scale to use numbers it can be useful:

`@theme {  --tracking-1: 0em;  --tracking-2: 0.025em;  --tracking-3: 0.05em;  --tracking-4: 0.1em;}`To use a negative letter spacing value, prefix the class name with a dash to convert it to a negative value:

`<p class="-tracking-2">The quick brown fox ...</p>`Use the `tracking-[` syntax to set the letter spacing based on a completely custom value:`<value>`]

`<p class="tracking-[.25em] ...">  Lorem ipsum dolor sit amet...</p>`For CSS variables, you can also use the `tracking-(` syntax:`<custom-property>`)

`<p class="tracking-(--my-tracking) ...">  Lorem ipsum dolor sit amet...</p>`This is just a shorthand for `tracking-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `letter-spacing` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="tracking-tight md:tracking-wide ...">  Lorem ipsum dolor sit amet...</p>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

Use the `--tracking-*` theme variables to customize the letter spacing utilities in your project:

`@theme {  --tracking-tightest: -0.075em; }`Now the `tracking-tightest` utility can be used in your markup:

`<p class="tracking-tightest">  Lorem ipsum dolor sit amet...</p>`Learn more about customizing your theme in the [theme documentation](/docs/theme#customizing-your-theme).

# Citations

1. Source page: https://tailwindcss.com/docs/letter-spacing

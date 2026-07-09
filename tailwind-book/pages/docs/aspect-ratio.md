---
type: Web Page
title: aspect-ratio - Layout - Tailwind CSS
description: Utilities for controlling the aspect ratio of an element.
resource: https://tailwindcss.com/docs/aspect-ratio
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Layout

Utilities for controlling the aspect ratio of an element.

| Class | Styles | 
|---|---|
| `aspect-` | `aspect-ratio: ` | 
| `aspect-square` | `aspect-ratio: 1 / 1;` | 
| `aspect-video` | `aspect-ratio: var(--aspect-video); /* 16 / 9 */` | 
| `aspect-auto` | `aspect-ratio: auto;` | 
| `aspect-(` | `aspect-ratio: var(` | 
| `aspect-[` | `aspect-ratio: ` | 

Use `aspect-` utilities like `<ratio>``aspect-3/2` to give an element a specific aspect ratio:

Resize the example to see the expected behavior

Use the `aspect-video` utility to give a video element a 16 / 9 aspect ratio:

Resize the example to see the expected behavior

Use the `aspect-[` syntax to set the aspect ratio based on a completely custom value:`<value>`]

`<img class="aspect-[calc(4*3+1)/3] ..." src="/img/villas.jpg" />`For CSS variables, you can also use the `aspect-(` syntax:`<custom-property>`)

`<img class="aspect-(--my-aspect-ratio) ..." src="/img/villas.jpg" />`This is just a shorthand for `aspect-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix an `aspect-ratio` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<iframe class="aspect-video md:aspect-square ..." src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

Use the `--aspect-*` theme variables to customize the aspect ratio utilities in your project:

`@theme {  --aspect-retro: 4 / 3; }`Now the `aspect-retro` utility can be used in your markup:

`<iframe class="aspect-retro" src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe>`Learn more about customizing your theme in the [theme documentation](/docs/theme#customizing-your-theme).

# Citations

1. Source page: https://tailwindcss.com/docs/aspect-ratio

---
type: Web Page
title: list-style-type - Typography - Tailwind CSS
description: Utilities for controlling the marker style of a list.
resource: https://tailwindcss.com/docs/list-style-type
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Typography

Utilities for controlling the marker style of a list.

| Class | Styles | 
|---|---|
| `list-disc` | `list-style-type: disc;` | 
| `list-decimal` | `list-style-type: decimal;` | 
| `list-none` | `list-style-type: none;` | 
| `list-(` | `list-style-type: var(` | 
| `list-[` | `list-style-type: ` | 

Use utilities like `list-disc` and `list-decimal` to control the style of the markers in a list:

Use the `list-[` syntax to set the marker based on a completely custom value:`<value>`]

`<ol class="list-[upper-roman] ...">  <!-- ... --></ol>`For CSS variables, you can also use the `list-(` syntax:`<custom-property>`)

`<ol class="list-(--my-marker) ...">  <!-- ... --></ol>`This is just a shorthand for `list-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `list-style-type` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<ul class="list-none md:list-disc ...">  <!-- ... --></ul>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/list-style-type

---
type: Web Page
title: line-clamp - Typography - Tailwind CSS
description: Utilities for clamping text to a specific number of lines.
resource: https://tailwindcss.com/docs/line-clamp
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Typography

Utilities for clamping text to a specific number of lines.

| Class | Styles | 
|---|---|
| `line-clamp-` | ```
overflow: hidden;
display: -webkit-box;
-webkit-box-orient: vertical;
-webkit-line-clamp: 
```
 | 
| `line-clamp-none` | ```
overflow: visible;
display: block;
-webkit-box-orient: horizontal;
-webkit-line-clamp: unset;
```
 | 
| `line-clamp-(` | ```
overflow: hidden;
display: -webkit-box;
-webkit-box-orient: vertical;
-webkit-line-clamp: var(
```
 | 
| `line-clamp-[` | ```
overflow: hidden;
display: -webkit-box;
-webkit-box-orient: vertical;
-webkit-line-clamp: 
```
 | 

Use `line-clamp-` utilities like `<number>``line-clamp-2` and `line-clamp-3` to truncate multi-line text after a specific number of lines:

Use `line-clamp-none` to undo a previously applied line clamp utility:

`<p class="line-clamp-3 lg:line-clamp-none">  <!-- ... --></p>`Use the `line-clamp-[` syntax to set the number of lines based on a completely custom value:`<value>`]

`<p class="line-clamp-[calc(var(--characters)/100)] ...">  Lorem ipsum dolor sit amet...</p>`For CSS variables, you can also use the `line-clamp-(` syntax:`<custom-property>`)

`<p class="line-clamp-(--my-line-count) ...">  Lorem ipsum dolor sit amet...</p>`This is just a shorthand for `line-clamp-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `line-clamp` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="line-clamp-3 md:line-clamp-4 ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/line-clamp

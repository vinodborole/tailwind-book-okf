---
type: Web Page
title: grid-auto-flow - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how elements in a grid are auto-placed.
resource: https://tailwindcss.com/docs/grid-auto-flow
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Flexbox & Grid

Utilities for controlling how elements in a grid are auto-placed.

| Class | Styles | 
|---|---|
| `grid-flow-row` | `grid-auto-flow: row;` | 
| `grid-flow-col` | `grid-auto-flow: column;` | 
| `grid-flow-dense` | `grid-auto-flow: dense;` | 
| `grid-flow-row-dense` | `grid-auto-flow: row dense;` | 
| `grid-flow-col-dense` | `grid-auto-flow: column dense;` | 

Use utilities like `grid-flow-col` and `grid-flow-row-dense` to control how the auto-placement algorithm works for a grid layout:

Prefix a `grid-auto-flow` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid grid-flow-col md:grid-flow-row ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/grid-auto-flow

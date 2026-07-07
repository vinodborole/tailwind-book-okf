---
type: Web Page
title: align-items - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how flex and grid items are positioned along
  a container's cross axis.
resource: https://tailwindcss.com/docs/align-items
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for controlling how flex and grid items are positioned along a container's cross axis.

| Class | Styles | 
|---|---|
| `items-start` | `align-items: flex-start;` | 
| `items-end` | `align-items: flex-end;` | 
| `items-end-safe` | `align-items: safe flex-end;` | 
| `items-center` | `align-items: center;` | 
| `items-center-safe` | `align-items: safe center;` | 
| `items-baseline` | `align-items: baseline;` | 
| `items-baseline-last` | `align-items: last baseline;` | 
| `items-stretch` | `align-items: stretch;` | 

Use the `items-stretch` utility to stretch items to fill the container's cross axis:

Use the `items-start` utility to align items to the start of the container's cross axis:

Use the `items-center` utility to align items along the center of the container's cross axis:

Use the `items-end` utility to align items to the end of the container's cross axis:

Use the `items-baseline` utility to align items along the container's cross axis such that all of their baselines align:

Use the `items-baseline-last` utility to align items along the container's cross axis such that all of their baselines align with the last baseline in the container:

This is useful for ensuring that text items align with each other, even if they have different heights.

Prefix an `align-items` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="flex items-stretch md:items-center ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/align-items

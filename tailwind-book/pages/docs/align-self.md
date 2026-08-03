---
type: Web Page
title: align-self - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how an individual flex or grid item is positioned
  along its container's cross axis.
resource: https://tailwindcss.com/docs/align-self
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Flexbox & Grid

Utilities for controlling how an individual flex or grid item is positioned along its container's cross axis.

| Class | Styles | 
|---|---|
| `self-auto` | `align-self: auto;` | 
| `self-start` | `align-self: flex-start;` | 
| `self-end` | `align-self: flex-end;` | 
| `self-end-safe` | `align-self: safe flex-end;` | 
| `self-center` | `align-self: center;` | 
| `self-center-safe` | `align-self: safe center;` | 
| `self-stretch` | `align-self: stretch;` | 
| `self-baseline` | `align-self: baseline;` | 
| `self-baseline-last` | `align-self: last baseline;` | 

Use the `self-auto` utility to align an item based on the value of the container's `align-items` property:

Use the `self-start` utility to align an item to the start of the container's cross axis, despite the container's `align-items` value:

Use the `self-center` utility to align an item along the center of the container's cross axis, despite the container's `align-items` value:

Use the `self-end` utility to align an item to the end of the container's cross axis, despite the container's `align-items` value:

Use the `self-stretch` utility to stretch an item to fill the container's cross axis, despite the container's `align-items` value:

Use the `self-baseline` utility to align an item such that its baseline aligns with the baseline of the flex container's cross axis:

Use the `self-baseline-last` utility to align an item along the container's cross axis such that its baseline aligns with the last baseline in the container:

This is useful for ensuring that text items align with each other, even if they have different heights.

Prefix an `align-self` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="self-auto md:self-end ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/align-self

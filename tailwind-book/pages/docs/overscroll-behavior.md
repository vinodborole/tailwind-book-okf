---
type: Web Page
title: overscroll-behavior - Layout - Tailwind CSS
description: Utilities for controlling how the browser behaves when reaching the boundary
  of a scrolling area.
resource: https://tailwindcss.com/docs/overscroll-behavior
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Layout

Utilities for controlling how the browser behaves when reaching the boundary of a scrolling area.

| Class | Styles | 
|---|---|
| `overscroll-auto` | `overscroll-behavior: auto;` | 
| `overscroll-contain` | `overscroll-behavior: contain;` | 
| `overscroll-none` | `overscroll-behavior: none;` | 
| `overscroll-x-auto` | `overscroll-behavior-x: auto;` | 
| `overscroll-x-contain` | `overscroll-behavior-x: contain;` | 
| `overscroll-x-none` | `overscroll-behavior-x: none;` | 
| `overscroll-y-auto` | `overscroll-behavior-y: auto;` | 
| `overscroll-y-contain` | `overscroll-behavior-y: contain;` | 
| `overscroll-y-none` | `overscroll-behavior-y: none;` | 

Use the `overscroll-contain` utility to prevent scrolling in the target area from triggering scrolling in the parent element, but preserve "bounce" effects when scrolling past the end of the container in operating systems that support it:

Scroll to see behavior

Use the `overscroll-none` utility to prevent scrolling in the target area from triggering scrolling in the parent element, and also prevent "bounce" effects when scrolling past the end of the container:

Scroll to see behavior

Use the `overscroll-auto` utility to make it possible for the user to continue scrolling a parent scroll area when they reach the boundary of the primary scroll area:

Scroll to see behavior

Prefix an `overscroll-behavior` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="overscroll-auto md:overscroll-contain ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/overscroll-behavior

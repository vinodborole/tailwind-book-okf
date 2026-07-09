---
type: Web Page
title: place-content - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how content is justified and aligned at the
  same time.
resource: https://tailwindcss.com/docs/place-content
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Flexbox & Grid

Utilities for controlling how content is justified and aligned at the same time.

| Class | Styles | 
|---|---|
| `place-content-center` | `place-content: center;` | 
| `place-content-center-safe` | `place-content: safe center;` | 
| `place-content-start` | `place-content: start;` | 
| `place-content-end` | `place-content: end;` | 
| `place-content-end-safe` | `place-content: safe end;` | 
| `place-content-between` | `place-content: space-between;` | 
| `place-content-around` | `place-content: space-around;` | 
| `place-content-evenly` | `place-content: space-evenly;` | 
| `place-content-baseline` | `place-content: baseline;` | 
| `place-content-stretch` | `place-content: stretch;` | 

Use `place-content-center` to pack items in the center of the inline and block axes:

Use `place-content-start` to pack items against the start of the inline and block axes:

Use `place-content-end` to pack items against the end of the inline and block axes:

Use `place-content-between` to distribute grid items along the inline and block axes so that there is an equal amount of space between each row and column on each axis respectively:

Use `place-content-around` to distribute grid items along the inline and block axes so that there is an equal amount of space around each row and column on each axis respectively:

Use `place-content-evenly` to distribute grid items such that they are evenly spaced on the inline and block axes:

Use `place-content-stretch` to stretch grid items along their grid areas on the inline and block axes:

Prefix a `place-content` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid place-content-start md:place-content-center ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/place-content

---
type: Web Page
title: align-content - Flexbox & Grid - Tailwind CSS
description: Utilities for controlling how rows are positioned in multi-row flex and
  grid containers.
resource: https://tailwindcss.com/docs/align-content
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Flexbox & Grid

Utilities for controlling how rows are positioned in multi-row flex and grid containers.

| Class | Styles | 
|---|---|
| `content-normal` | `align-content: normal;` | 
| `content-center` | `align-content: center;` | 
| `content-start` | `align-content: flex-start;` | 
| `content-end` | `align-content: flex-end;` | 
| `content-between` | `align-content: space-between;` | 
| `content-around` | `align-content: space-around;` | 
| `content-evenly` | `align-content: space-evenly;` | 
| `content-baseline` | `align-content: baseline;` | 
| `content-stretch` | `align-content: stretch;` | 

Use `content-start` to pack rows in a container against the start of the cross axis:

Use `content-center` to pack rows in a container in the center of the cross axis:

Use `content-end` to pack rows in a container against the end of the cross axis:

Use `content-between` to distribute rows in a container such that there is an equal amount of space between each line:

Use `content-around` to distribute rows in a container such that there is an equal amount of space around each line:

Use `content-evenly` to distribute rows in a container such that there is an equal amount of space around each item, but also accounting for the doubling of space you would normally see between each item when using `content-around`:

Use `content-stretch` to allow content items to fill the available space along the container’s cross axis:

Use `content-normal` to pack content items in their default position as if no `align-content` value was set:

Prefix an `align-content` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="grid content-start md:content-around ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/align-content

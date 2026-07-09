---
type: Web Page
title: position - Layout - Tailwind CSS
description: Utilities for controlling how an element is positioned in the document.
resource: https://tailwindcss.com/docs/position
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Layout

Utilities for controlling how an element is positioned in the document.

| Class | Styles | 
|---|---|
| `static` | `position: static;` | 
| `fixed` | `position: fixed;` | 
| `absolute` | `position: absolute;` | 
| `relative` | `position: relative;` | 
| `sticky` | `position: sticky;` | 

Use the `static` utility to position an element according to the normal flow of the document:

With statically positioned elements, any [offsets](/docs/top-right-bottom-left) will be ignored and the element will not act as a position reference for absolutely positioned children.

Use the `relative` utility to position an element according to the normal flow of the document:

With relatively position elements, any [offsets](/docs/top-right-bottom-left) are calculated relative to the element's normal position and the element will act as a position reference for absolutely positioned children.

Use the `absolute` utility to position an element *outside* of the normal flow of the document, causing neighboring elements to act as if the element doesn't exist:

With absolutely positioned elements, any [offsets](/docs/top-right-bottom-left) are calculated relative to the nearest parent that has a position other than `static`, and the element will act as a position reference for other absolutely positioned children.

Use the `fixed` utility to position an element relative to the browser window:

Scroll this element to see the fixed positioning in action

With fixed positioned elements, any [offsets](/docs/top-right-bottom-left) are calculated relative to the viewport and the element will act as a position reference for absolutely positioned children:

Use the `sticky` utility to position an element as `relative` until it crosses a specified threshold, then treat it as `fixed` until its parent is off screen:

Scroll this element to see the sticky positioning in action

With sticky positioned elements, any [offsets](/docs/top-right-bottom-left) are calculated relative to the element's normal position and the element will act as a position reference for absolutely positioned children.

Prefix a `position` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="relative md:absolute ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/position

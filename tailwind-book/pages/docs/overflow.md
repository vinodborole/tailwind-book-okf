---
type: Web Page
title: overflow - Layout - Tailwind CSS
description: Utilities for controlling how an element handles content that is too
  large for the container.
resource: https://tailwindcss.com/docs/overflow
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Layout

Utilities for controlling how an element handles content that is too large for the container.

| Class | Styles | 
|---|---|
| `overflow-auto` | `overflow: auto;` | 
| `overflow-hidden` | `overflow: hidden;` | 
| `overflow-clip` | `overflow: clip;` | 
| `overflow-visible` | `overflow: visible;` | 
| `overflow-scroll` | `overflow: scroll;` | 
| `overflow-x-auto` | `overflow-x: auto;` | 
| `overflow-y-auto` | `overflow-y: auto;` | 
| `overflow-x-hidden` | `overflow-x: hidden;` | 
| `overflow-y-hidden` | `overflow-y: hidden;` | 
| `overflow-x-clip` | `overflow-x: clip;` | 
| `overflow-y-clip` | `overflow-y: clip;` | 
| `overflow-x-visible` | `overflow-x: visible;` | 
| `overflow-y-visible` | `overflow-y: visible;` | 
| `overflow-x-scroll` | `overflow-x: scroll;` | 
| `overflow-y-scroll` | `overflow-y: scroll;` | 

Use the `overflow-visible` utility to prevent content within an element from being clipped:

Note that any content that overflows the bounds of the element will then be visible.

Use the `overflow-hidden` utility to clip any content within an element that overflows the bounds of that element:

Use the `overflow-auto` utility to add scrollbars to an element in the event that its content overflows the bounds of that element:

Scroll vertically

Unlike `overflow-scroll`, which always shows scrollbars, this utility will only show them if scrolling is necessary.

Use the `overflow-x-auto` utility to allow horizontal scrolling if needed:

Scroll horizontally

Use the `overflow-y-auto` utility to allow vertical scrolling if needed:

Use the `overflow-x-scroll` utility to allow horizontal scrolling and always show scrollbars unless always-visible scrollbars are disabled by the operating system:

Use the `overflow-y-scroll` utility to allow vertical scrolling and always show scrollbars unless always-visible scrollbars are disabled by the operating system:

Use the `overflow-scroll` utility to add scrollbars to an element:

Scroll vertically and horizontally

Unlike `overflow-auto`, which only shows scrollbars if they are necessary, this utility always shows them. Note that some operating systems (like macOS) hide unnecessary scrollbars regardless of this setting.

Prefix an `overflow` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="overflow-auto md:overflow-scroll ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/overflow

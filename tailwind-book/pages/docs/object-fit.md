---
type: Web Page
title: object-fit - Layout - Tailwind CSS
description: Utilities for controlling how a replaced element's content should be
  resized.
resource: https://tailwindcss.com/docs/object-fit
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Layout

Utilities for controlling how a replaced element's content should be resized.

| Class | Styles | 
|---|---|
| `object-contain` | `object-fit: contain;` | 
| `object-cover` | `object-fit: cover;` | 
| `object-fill` | `object-fit: fill;` | 
| `object-none` | `object-fit: none;` | 
| `object-scale-down` | `object-fit: scale-down;` | 

Use the `object-cover` utility to resize an element's content to cover its container:

Use the `object-contain` utility to resize an element's content to stay contained within its container:

Use the `object-fill` utility to stretch an element's content to fit its container:

Use the `object-scale-down` utility to display an element's content at its original size but scale it down to fit its container if necessary:

Use the `object-none` utility to display an element's content at its original size ignoring the container size:

Prefix an `object-fit` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<img class="object-contain md:object-cover" src="/img/mountains.jpg" />`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

# Citations

1. Source page: https://tailwindcss.com/docs/object-fit

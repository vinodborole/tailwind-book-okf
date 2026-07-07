---
type: Web Page
title: isolation - Layout - Tailwind CSS
description: Utilities for controlling whether an element should explicitly create
  a new stacking context.
resource: https://tailwindcss.com/docs/isolation
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Layout

Utilities for controlling whether an element should explicitly create a new stacking context.

| Class | Styles | 
|---|---|
| `isolate` | `isolation: isolate;` | 
| `isolation-auto` | `isolation: auto;` | 

Use the `isolate` and `isolation-auto` utilities to control whether an element should explicitly create a new stacking context:

`<div class="isolate ...">  <!-- ... --></div>`Prefix an `isolation` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="isolate md:isolation-auto ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/isolation

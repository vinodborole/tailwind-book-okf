---
type: Web Page
title: min-inline-size - Sizing - Tailwind CSS
description: Utilities for setting the minimum inline size of an element.
resource: https://tailwindcss.com/docs/min-inline-size
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Sizing

Utilities for setting the minimum inline size of an element.

| Class | Styles | 
|---|---|
| `min-inline-` | `min-inline-size: calc(var(--spacing) * ` | 
| `min-inline-` | `min-inline-size: calc(` | 
| `min-inline-3xs` | `min-inline-size: var(--container-3xs); /* 16rem (256px) */` | 
| `min-inline-2xs` | `min-inline-size: var(--container-2xs); /* 18rem (288px) */` | 
| `min-inline-xs` | `min-inline-size: var(--container-xs); /* 20rem (320px) */` | 
| `min-inline-sm` | `min-inline-size: var(--container-sm); /* 24rem (384px) */` | 
| `min-inline-md` | `min-inline-size: var(--container-md); /* 28rem (448px) */` | 
| `min-inline-lg` | `min-inline-size: var(--container-lg); /* 32rem (512px) */` | 
| `min-inline-xl` | `min-inline-size: var(--container-xl); /* 36rem (576px) */` | 
| `min-inline-2xl` | `min-inline-size: var(--container-2xl); /* 42rem (672px) */` | 
| `min-inline-3xl` | `min-inline-size: var(--container-3xl); /* 48rem (768px) */` | 
| `min-inline-4xl` | `min-inline-size: var(--container-4xl); /* 56rem (896px) */` | 
| `min-inline-5xl` | `min-inline-size: var(--container-5xl); /* 64rem (1024px) */` | 
| `min-inline-6xl` | `min-inline-size: var(--container-6xl); /* 72rem (1152px) */` | 
| `min-inline-7xl` | `min-inline-size: var(--container-7xl); /* 80rem (1280px) */` | 
| `min-inline-auto` | `min-inline-size: auto;` | 
| `min-inline-px` | `min-inline-size: 1px;` | 
| `min-inline-full` | `min-inline-size: 100%;` | 
| `min-inline-screen` | `min-inline-size: 100vw;` | 
| `min-inline-dvw` | `min-inline-size: 100dvw;` | 
| `min-inline-dvh` | `min-inline-size: 100dvh;` | 
| `min-inline-lvw` | `min-inline-size: 100lvw;` | 
| `min-inline-lvh` | `min-inline-size: 100lvh;` | 
| `min-inline-svw` | `min-inline-size: 100svw;` | 
| `min-inline-svh` | `min-inline-size: 100svh;` | 
| `min-inline-min` | `min-inline-size: min-content;` | 
| `min-inline-max` | `min-inline-size: max-content;` | 
| `min-inline-fit` | `min-inline-size: fit-content;` | 
| `min-inline-(` | `min-inline-size: var(` | 
| `min-inline-[` | `min-inline-size: ` | 

Use `min-inline-` utilities like `<number>``min-inline-24` and `min-inline-64` to set an element to a fixed minimum inline size based on the spacing scale:

Use `min-inline-full` or `min-inline-` utilities like `<fraction>``min-inline-1/2` and `min-inline-2/5` to give an element a percentage-based minimum inline size:

Use utilities like `min-inline-sm` and `min-inline-xl` to set an element to a fixed minimum inline size based on the container scale:

Use the `min-inline-[` syntax to set the minimum inline size based on a completely custom value:`<value>`]

`<div class="min-inline-[220px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `min-inline-(` syntax:`<custom-property>`)

`<div class="min-inline-(--my-min-inline-size) ...">  <!-- ... --></div>`This is just a shorthand for `min-inline-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `min-inline-size` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="inline-24 min-inline-full md:min-inline-0 ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

The `min-inline-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the theme variable documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/min-inline-size

---
type: Web Page
title: inline-size - Sizing - Tailwind CSS
description: Utilities for setting the inline size of an element.
resource: https://tailwindcss.com/docs/inline-size
timestamp: '2026-08-03T09:00:03.448760+00:00'
---

Sizing

Utilities for setting the inline size of an element.

| Class | Styles | 
|---|---|
| `inline-``<number>` | `inline-size: calc(var(--spacing) *` `<number>` ); | 
| `inline-``<fraction>` | `inline-size: calc(``<fraction>` * 100%); | 
| `inline-3xs` | `inline-size: var(--container-3xs); /* 16rem (256px) */` | 
| `inline-2xs` | `inline-size: var(--container-2xs); /* 18rem (288px) */` | 
| `inline-xs` | `inline-size: var(--container-xs); /* 20rem (320px) */` | 
| `inline-sm` | `inline-size: var(--container-sm); /* 24rem (384px) */` | 
| `inline-md` | `inline-size: var(--container-md); /* 28rem (448px) */` | 
| `inline-lg` | `inline-size: var(--container-lg); /* 32rem (512px) */` | 
| `inline-xl` | `inline-size: var(--container-xl); /* 36rem (576px) */` | 
| `inline-2xl` | `inline-size: var(--container-2xl); /* 42rem (672px) */` | 
| `inline-3xl` | `inline-size: var(--container-3xl); /* 48rem (768px) */` | 
| `inline-4xl` | `inline-size: var(--container-4xl); /* 56rem (896px) */` | 
| `inline-5xl` | `inline-size: var(--container-5xl); /* 64rem (1024px) */` | 
| `inline-6xl` | `inline-size: var(--container-6xl); /* 72rem (1152px) */` | 
| `inline-7xl` | `inline-size: var(--container-7xl); /* 80rem (1280px) */` | 
| `inline-auto` | `inline-size: auto;` | 
| `inline-px` | `inline-size: 1px;` | 
| `inline-full` | `inline-size: 100%;` | 
| `inline-screen` | `inline-size: 100vw;` | 
| `inline-dvw` | `inline-size: 100dvw;` | 
| `inline-dvh` | `inline-size: 100dvh;` | 
| `inline-lvw` | `inline-size: 100lvw;` | 
| `inline-lvh` | `inline-size: 100lvh;` | 
| `inline-svw` | `inline-size: 100svw;` | 
| `inline-svh` | `inline-size: 100svh;` | 
| `inline-min` | `inline-size: min-content;` | 
| `inline-max` | `inline-size: max-content;` | 
| `inline-fit` | `inline-size: fit-content;` | 
| `inline-(``<custom-property>` ) | `inline-size: var(``<custom-property>` ); | 
| `inline-[``<value>` ] | `inline-size:` `<value>` ; | 

Use `inline-` utilities like `<number>``inline-24` and `inline-64` to set an element to a fixed inline size based on the spacing scale:

Use `inline-full` or `inline-` utilities like `<fraction>``inline-1/2` and `inline-2/5` to give an element a percentage-based inline size:

Use utilities like `inline-sm` and `inline-xl` to set an element to a fixed inline size based on the container scale:

Use the `inline-screen` utility to make an element span the entire inline size of the viewport:

`<div class="inline-screen">  <!-- ... --></div>`
Use the `inline-auto` utility to remove an element's assigned inline size under a specific condition, like at a particular breakpoint:

`<div class="inline-full md:inline-auto">  <!-- ... --></div>`
Use the `inline-[` syntax to set the inline size based on a completely custom value:`<value>`]

`<div class="inline-[5px] ...">  <!-- ... --></div>`
For CSS variables, you can also use the `inline-(` syntax:`<custom-property>`)

`<div class="inline-(--my-inline-size) ...">  <!-- ... --></div>`
This is just a shorthand for `inline-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix an `inline-size` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="inline-1/2 md:inline-full ...">  <!-- ... --></div>`
Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `inline-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`
Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/inline-size

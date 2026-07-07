---
type: Web Page
title: width - Sizing - Tailwind CSS
description: Utilities for setting the width of an element.
resource: https://tailwindcss.com/docs/width
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Sizing

Utilities for setting the width of an element.

| Class | Styles | 
|---|---|
| `w-` | `width: calc(var(--spacing) * ` | 
| `w-` | `width: calc(` | 
| `w-3xs` | `width: var(--container-3xs); /* 16rem (256px) */` | 
| `w-2xs` | `width: var(--container-2xs); /* 18rem (288px) */` | 
| `w-xs` | `width: var(--container-xs); /* 20rem (320px) */` | 
| `w-sm` | `width: var(--container-sm); /* 24rem (384px) */` | 
| `w-md` | `width: var(--container-md); /* 28rem (448px) */` | 
| `w-lg` | `width: var(--container-lg); /* 32rem (512px) */` | 
| `w-xl` | `width: var(--container-xl); /* 36rem (576px) */` | 
| `w-2xl` | `width: var(--container-2xl); /* 42rem (672px) */` | 
| `w-3xl` | `width: var(--container-3xl); /* 48rem (768px) */` | 
| `w-4xl` | `width: var(--container-4xl); /* 56rem (896px) */` | 
| `w-5xl` | `width: var(--container-5xl); /* 64rem (1024px) */` | 
| `w-6xl` | `width: var(--container-6xl); /* 72rem (1152px) */` | 
| `w-7xl` | `width: var(--container-7xl); /* 80rem (1280px) */` | 
| `w-auto` | `width: auto;` | 
| `w-px` | `width: 1px;` | 
| `w-full` | `width: 100%;` | 
| `w-screen` | `width: 100vw;` | 
| `w-dvw` | `width: 100dvw;` | 
| `w-dvh` | `width: 100dvh;` | 
| `w-lvw` | `width: 100lvw;` | 
| `w-lvh` | `width: 100lvh;` | 
| `w-svw` | `width: 100svw;` | 
| `w-svh` | `width: 100svh;` | 
| `w-min` | `width: min-content;` | 
| `w-max` | `width: max-content;` | 
| `w-fit` | `width: fit-content;` | 
| `w-(` | `width: var(` | 
| `w-[` | `width: ` | 
| `size-` | `width: calc(var(--spacing) * ` | 
| `size-` | `width: calc(` | 
| `size-auto` | ```
width: auto;
height: auto;
```
 | 
| `size-px` | ```
width: 1px;
height: 1px;
```
 | 
| `size-full` | ```
width: 100%;
height: 100%;
```
 | 
| `size-dvw` | ```
width: 100dvw;
height: 100dvw;
```
 | 
| `size-dvh` | ```
width: 100dvh;
height: 100dvh;
```
 | 
| `size-lvw` | ```
width: 100lvw;
height: 100lvw;
```
 | 
| `size-lvh` | ```
width: 100lvh;
height: 100lvh;
```
 | 
| `size-svw` | ```
width: 100svw;
height: 100svw;
```
 | 
| `size-svh` | ```
width: 100svh;
height: 100svh;
```
 | 
| `size-min` | ```
width: min-content;
height: min-content;
```
 | 
| `size-max` | ```
width: max-content;
height: max-content;
```
 | 
| `size-fit` | ```
width: fit-content;
height: fit-content;
```
 | 
| `size-(` | `width: var(` | 
| `size-[` | `width: ` | 

Use `w-` utilities like `<number>``w-24` and `w-64` to set an element to a fixed width based on the spacing scale:

Use `w-full` or `w-` utilities like `<fraction>``w-1/2` and `w-2/5` to give an element a percentage-based width:

Use utilities like `w-sm` and `w-xl` to set an element to a fixed width based on the container scale:

Use the `w-screen` utility to make an element span the entire width of the viewport:

`<div class="w-screen">  <!-- ... --></div>`Alternatively, you can match the width of the large, small or dynamic viewports using the `w-lvw`, `w-svw`, and `w-dvw` utilities.

Use the `w-auto` utility to remove an element's assigned width under a specific condition, like at a particular breakpoint:

`<div class="w-full md:w-auto">  <!-- ... --></div>`Use utilities like `size-px`, `size-4`, and `size-full` to set both the width and height of an element at the same time:

Use the `w-[` syntax to set the width based on a completely custom value:`<value>`]

`<div class="w-[5px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `w-(` syntax:`<custom-property>`)

`<div class="w-(--my-width) ...">  <!-- ... --></div>`This is just a shorthand for `w-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `width` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="w-1/2 md:w-full ...">  <!-- ... --></div>`Learn more about using variants in the variants documentation.

The `w-` and `<number>``size-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the theme variable documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/width

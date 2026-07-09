---
type: Web Page
title: margin - Spacing - Tailwind CSS
description: Utilities for controlling an element's margin.
resource: https://tailwindcss.com/docs/margin
timestamp: '2026-07-09T12:17:00.933290+00:00'
---

Spacing

Utilities for controlling an element's margin.

| Class | Styles | 
|---|---|
| `m-` | `margin: calc(var(--spacing) * ` | 
| `-m-` | `margin: calc(var(--spacing) * -` | 
| `m-auto` | `margin: auto;` | 
| `m-px` | `margin: 1px;` | 
| `-m-px` | `margin: -1px;` | 
| `m-(` | `margin: var(` | 
| `m-[` | `margin: ` | 
| `mx-` | `margin-inline: calc(var(--spacing) * ` | 
| `-mx-` | `margin-inline: calc(var(--spacing) * -` | 
| `mx-auto` | `margin-inline: auto;` | 
| `mx-px` | `margin-inline: 1px;` | 
| `-mx-px` | `margin-inline: -1px;` | 
| `mx-(` | `margin-inline: var(` | 
| `mx-[` | `margin-inline: ` | 
| `my-` | `margin-block: calc(var(--spacing) * ` | 
| `-my-` | `margin-block: calc(var(--spacing) * -` | 
| `my-auto` | `margin-block: auto;` | 
| `my-px` | `margin-block: 1px;` | 
| `-my-px` | `margin-block: -1px;` | 
| `my-(` | `margin-block: var(` | 
| `my-[` | `margin-block: ` | 
| `ms-` | `margin-inline-start: calc(var(--spacing) * ` | 
| `-ms-` | `margin-inline-start: calc(var(--spacing) * -` | 
| `ms-auto` | `margin-inline-start: auto;` | 
| `ms-px` | `margin-inline-start: 1px;` | 
| `-ms-px` | `margin-inline-start: -1px;` | 
| `ms-(` | `margin-inline-start: var(` | 
| `ms-[` | `margin-inline-start: ` | 
| `me-` | `margin-inline-end: calc(var(--spacing) * ` | 
| `-me-` | `margin-inline-end: calc(var(--spacing) * -` | 
| `me-auto` | `margin-inline-end: auto;` | 
| `me-px` | `margin-inline-end: 1px;` | 
| `-me-px` | `margin-inline-end: -1px;` | 
| `me-(` | `margin-inline-end: var(` | 
| `me-[` | `margin-inline-end: ` | 
| `mbs-` | `margin-block-start: calc(var(--spacing) * ` | 
| `-mbs-` | `margin-block-start: calc(var(--spacing) * -` | 
| `mbs-auto` | `margin-block-start: auto;` | 
| `mbs-px` | `margin-block-start: 1px;` | 
| `-mbs-px` | `margin-block-start: -1px;` | 
| `mbs-(` | `margin-block-start: var(` | 
| `mbs-[` | `margin-block-start: ` | 
| `mbe-` | `margin-block-end: calc(var(--spacing) * ` | 
| `-mbe-` | `margin-block-end: calc(var(--spacing) * -` | 
| `mbe-auto` | `margin-block-end: auto;` | 
| `mbe-px` | `margin-block-end: 1px;` | 
| `-mbe-px` | `margin-block-end: -1px;` | 
| `mbe-(` | `margin-block-end: var(` | 
| `mbe-[` | `margin-block-end: ` | 
| `mt-` | `margin-top: calc(var(--spacing) * ` | 
| `-mt-` | `margin-top: calc(var(--spacing) * -` | 
| `mt-auto` | `margin-top: auto;` | 
| `mt-px` | `margin-top: 1px;` | 
| `-mt-px` | `margin-top: -1px;` | 
| `mt-(` | `margin-top: var(` | 
| `mt-[` | `margin-top: ` | 
| `mr-` | `margin-right: calc(var(--spacing) * ` | 
| `-mr-` | `margin-right: calc(var(--spacing) * -` | 
| `mr-auto` | `margin-right: auto;` | 
| `mr-px` | `margin-right: 1px;` | 
| `-mr-px` | `margin-right: -1px;` | 
| `mr-(` | `margin-right: var(` | 
| `mr-[` | `margin-right: ` | 
| `mb-` | `margin-bottom: calc(var(--spacing) * ` | 
| `-mb-` | `margin-bottom: calc(var(--spacing) * -` | 
| `mb-auto` | `margin-bottom: auto;` | 
| `mb-px` | `margin-bottom: 1px;` | 
| `-mb-px` | `margin-bottom: -1px;` | 
| `mb-(` | `margin-bottom: var(` | 
| `mb-[` | `margin-bottom: ` | 
| `ml-` | `margin-left: calc(var(--spacing) * ` | 
| `-ml-` | `margin-left: calc(var(--spacing) * -` | 
| `ml-auto` | `margin-left: auto;` | 
| `ml-px` | `margin-left: 1px;` | 
| `-ml-px` | `margin-left: -1px;` | 
| `ml-(` | `margin-left: var(` | 
| `ml-[` | `margin-left: ` | 
| `space-x-` | ```
& > :not(:last-child) {
  --tw-space-x-reverse: 0;
  margin-inline-start: calc(calc(var(--spacing) * 
```
 | 
| `-space-x-` | ```
& > :not(:last-child) {
  --tw-space-x-reverse: 0;
  margin-inline-start: calc(calc(var(--spacing) * -
```
 | 
| `space-x-px` | ```
& > :not(:last-child) {
  --tw-space-x-reverse: 0;
  margin-inline-start: calc(1px * var(--tw-space-x-reverse));
  margin-inline-end: calc(1px * calc(1 - var(--tw-space-x-reverse)));
};
```
 | 
| `-space-x-px` | ```
& > :not(:last-child) {
  --tw-space-x-reverse: 0;
  margin-inline-start: calc(-1px * var(--tw-space-x-reverse));
  margin-inline-end: calc(-1px * calc(1 - var(--tw-space-x-reverse)));
};
```
 | 
| `space-x-(` | ```
& > :not(:last-child) {
  --tw-space-x-reverse: 0;
  margin-inline-start: calc(var(
```
 | 
| `space-x-[` | ```
& > :not(:last-child) {
  --tw-space-x-reverse: 0;
  margin-inline-start: calc(
```
 | 
| `space-y-` | ```
& > :not(:last-child) {
  --tw-space-y-reverse: 0;
  margin-block-start: calc(calc(var(--spacing) * 
```
 | 
| `-space-y-` | ```
& > :not(:last-child) {
  --tw-space-y-reverse: 0;
  margin-block-start: calc(calc(var(--spacing) * -
```
 | 
| `space-y-px` | ```
& > :not(:last-child) {
  --tw-space-y-reverse: 0;
  margin-block-start: calc(1px * var(--tw-space-y-reverse));
  margin-block-end: calc(1px * calc(1 - var(--tw-space-y-reverse)));
};
```
 | 
| `-space-y-px` | ```
& > :not(:last-child) {
  --tw-space-y-reverse: 0;
  margin-block-start: calc(-1px * var(--tw-space-y-reverse));
  margin-block-end: calc(-1px * calc(1 - var(--tw-space-y-reverse)));
};
```
 | 
| `space-y-(` | ```
& > :not(:last-child) {
  --tw-space-y-reverse: 0;
  margin-block-start: calc(var(
```
 | 
| `space-y-[` | ```
& > :not(:last-child) {
  --tw-space-y-reverse: 0;
  margin-block-start: calc(
```
 | 
| `space-x-reverse` | ```
& > :not(:last-child)) {
  --tw-space-x-reverse: 1;
}
```
 | 
| `space-y-reverse` | ```
& > :not(:last-child)) {
  --tw-space-y-reverse: 1;
}
```
 | 

Use `m-` utilities like `<number>``m-4` and `m-8` to control the margin on all sides of an element:

Use `mt-`, `<number>``mr-`, `<number>``mb-`, and `<number>``ml-` utilities like `<number>``ml-2` and `mt-6` to control the margin on one side of an element:

Use `mx-` utilities like `<number>``mx-4` and `mx-8` to control the horizontal margin of an element:

Use `my-` utilities like `<number>``my-4` and `my-8` to control the vertical margin of an element:

To use a negative margin value, prefix the class name with a dash to convert it to a negative value:

Use `ms-` or `<number>``me-` utilities like `<number>``ms-4` and `me-8` to set the `margin-inline-start` and `margin-inline-end` logical properties:

Use the `mbs-` and `<number>``mbe-` utilities to set the `<number>``margin-block-start` and `margin-block-end` logical properties, which map to either the top or bottom side based on the writing mode:

`<div class="mbs-8 ...">mbs-8</div>`Use `space-x-` or `<number>``space-y-` utilities like `<number>``space-x-4` and `space-y-8` to control the space between elements:

If your elements are in reverse order (using say `flex-row-reverse` or `flex-col-reverse`), use the `space-x-reverse` or `space-y-reverse` utilities to ensure the space is added to the correct side of each element:

The space utilities are really just a shortcut for adding margin to all-but-the-last-item in a group, and aren't designed to handle complex cases like grids, layouts that wrap, or situations where the children are rendered in a complex custom order rather than their natural DOM order.

For those situations, it's better to use the [gap utilities](/docs/gap) when possible, or add margin to every element with a matching negative margin on the parent.

Additionally, the space utilities are not designed to work together with the [divide utilities](/docs/border-width#between-children). For those situations, consider adding margin/padding utilities to the children instead.

Use utilities like `m-[`,`<value>`]`mx-[`, and `<value>`]`mb-[` to set the margin based on a completely custom value:`<value>`]

`<div class="m-[5px] ...">  <!-- ... --></div>`For CSS variables, you can also use the `m-(` syntax:`<custom-property>`)

`<div class="m-(--my-margin) ...">  <!-- ... --></div>`This is just a shorthand for `m-[var(` that adds the `<custom-property>`)]`var()` function for you automatically.

Prefix a `margin` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<div class="mt-4 md:mt-8 ...">  <!-- ... --></div>`Learn more about using variants in the [variants documentation](/docs/hover-focus-and-other-states).

The `m-`,`<number>``mx-`,`<number>``my-`,`<number>``ms-`,`<number>``me-`,`<number>``mbs-`,`<number>``mbe-`,`<number>``mt-`,`<number>``mr-`,`<number>``mb-`, and `<number>``ml-` utilities are driven by the `<number>``--spacing` theme variable, which can be customized in your own theme:

`@theme {  --spacing: 1px; }`Learn more about customizing the spacing scale in the [theme variable documentation](/docs/theme).

# Citations

1. Source page: https://tailwindcss.com/docs/margin

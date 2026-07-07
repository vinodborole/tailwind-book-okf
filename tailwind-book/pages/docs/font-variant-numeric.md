---
type: Web Page
title: font-variant-numeric - Typography - Tailwind CSS
description: Utilities for controlling the variant of numbers.
resource: https://tailwindcss.com/docs/font-variant-numeric
timestamp: '2026-07-07T10:59:46.333743+00:00'
---

Typography

Utilities for controlling the variant of numbers.

| Class | Styles | 
|---|---|
| `normal-nums` | `font-variant-numeric: normal;` | 
| `ordinal` | `font-variant-numeric: ordinal;` | 
| `slashed-zero` | `font-variant-numeric: slashed-zero;` | 
| `lining-nums` | `font-variant-numeric: lining-nums;` | 
| `oldstyle-nums` | `font-variant-numeric: oldstyle-nums;` | 
| `proportional-nums` | `font-variant-numeric: proportional-nums;` | 
| `tabular-nums` | `font-variant-numeric: tabular-nums;` | 
| `diagonal-fractions` | `font-variant-numeric: diagonal-fractions;` | 
| `stacked-fractions` | `font-variant-numeric: stacked-fractions;` | 

Use the `ordinal` utility to enable special glyphs for the ordinal markers in fonts that support them:

Use the `slashed-zero` utility to force a zero with a slash in fonts that support them:

Use the `lining-nums` utility to use numeric glyphs that are aligned by their baseline in fonts that support them:

Use the `oldstyle-nums` utility to use numeric glyphs where some numbers have descenders in fonts that support them:

Use the `proportional-nums` utility to use numeric glyphs that have proportional widths in fonts that support them:

Use the `tabular-nums` utility to use numeric glyphs that have uniform/tabular widths in fonts that support them:

Use the `diagonal-fractions` utility to replace numbers separated by a slash with common diagonal fractions in fonts that support them:

Use the `stacked-fractions` utility to replace numbers separated by a slash with common stacked fractions in fonts that support them:

The `font-variant-numeric` utilities are composable so you can enable multiple variants by combining them:

Use the `normal-nums` property to reset numeric font variants:

`<p class="slashed-zero tabular-nums md:normal-nums ...">  <!-- ... --></p>`Prefix a `font-variant-numeric` utility with a breakpoint variant like `md:` to only apply the utility at medium screen sizes and above:

`<p class="proportional-nums md:tabular-nums ...">  Lorem ipsum dolor sit amet...</p>`Learn more about using variants in the variants documentation.

# Citations

1. Source page: https://tailwindcss.com/docs/font-variant-numeric

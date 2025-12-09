# Styling SVG's

SVG shapes can be styled two different ways:
1. Using attributes directly on the shapes
2. Ussing CSS to style certain classes or IDs

---

## Inline Styling
Inline Styling adds the style attributes directly to each SVG element.

```html
<circle cx="60" cy="60" r="30" fill="red" stroke="black" stroke-width="3" />
```

## CSS Styling
You can also style SVG elements using CSS inside the `<svg>` block.

```html
<svg width="120" height="120">
  <style>
    .blue-circle {
      fill: steelblue;
      stroke: black;
      stroke-width: 2;
    }
  </style>

  <circle class="blue-circle" cx="60" cy="60" r="30" />
</svg>
```

---
id: button
title: Button
sidebar_label: Button
---

Neu provides different button implementations.

## Default Button

To create a button, add the `neu-btn` classname to any `<a>` or `<button>` element.

<div class="element-renderer">
  <button class="neu-btn">Default button</button>
</div>

```html
<button class="neu-btn">Default button</button>
```

## Disabled Button

To create a disabled button, just add the `disabled` attribute alongside `neu-btn` classname.

<div class="element-renderer">
  <button class="neu-btn" disabled>Disabled button</button>
</div>

```html
<button class="neu-btn" disabled>Disabled button</button>
```

## Grouped Buttons

If you want to group multiple buttons in a single line, use class `neu-btn-group` on a `div`.

<div class="element-renderer">
  <div class="neu-btn-group">
    <button class="neu-btn">Button 1</button>
    <button class="neu-btn">Button 2</button>
    <button class="neu-btn">Button 3</button>
  </div>
</div>

```html
<div class="neu-btn-group">
  <button class="neu-btn">Button 1</button>
  <button class="neu-btn">Button 2</button>
  <button class="neu-btn">Button 3</button>
</div>
```
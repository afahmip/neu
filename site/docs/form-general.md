---
id: form-general
title: Form
sidebar_label: General
---

This part is meant for input types `text`, `password`, `email`, and `time`.

## Form Example

<div class="element-renderer">
  <form class="neu-form">
    <fieldset class="neu-fieldset">
      <legend class="neu-fieldset__legend">Form test</legend>
      <div class="neu-form-group">
        <label class="neu-form-label" for="input-text">Text Input</label>
        <input type="text" class="neu-input" id="input-text" placeholder="Text">
      </div>
      <div class="neu-form-group">
        <label class="neu-form-label" for="input-disabled">Disabled Input</label>
        <input type="text" class="neu-input" id="input-disabled" disabled placeholder="Disabled">
      </div>
      <div class="neu-form-group">
        <label class="neu-form-label" for="input-date">Date Input</label>
        <input type="date" class="neu-input" id="input-date">
        <p class="neu-form-message neu-form-message--danger">This is a required field</p>
      </div>
    </fieldset>
  </form>
</div>

```html
<form class="neu-form">
  <fieldset class="neu-fieldset">
    <legend class="neu-fieldset__legend">Form test</legend>

    <div class="neu-form-group">
      <label class="neu-form-label" for="input-text">Text Input</label>
      <input type="text" class="neu-input" id="input-text" placeholder="Text">
    </div>

    <div class="neu-form-group">
      <label class="neu-form-label" for="input-disabled">Disabled Input</label>
      <input type="text" class="neu-input" id="input-disabled" disabled placeholder="Disabled">
    </div>

    <div class="neu-form-group">
      <label class="neu-form-label" for="input-date">Date Input</label>
      <input type="date" class="neu-input" id="input-date">
      <p class="neu-form-message neu-form-message--danger">This is a required field</p>
    </div>
  </fieldset>
</form>
```

## Form Field

The `neu-form-group` container consists of:
- a `<label>` with class `neu-form-label`
- an input
- an optional `<p>` with class `neu-form-message`

<div class="neu-form-group">
  <label class="neu-form-label" for="input-text">Text Input</label>
  <input type="text" class="neu-input" id="input-text" placeholder="Text">
  <p class="neu-form-message">This is a required field</p>
</div>

```html
<div class="neu-form-group">
  <label class="neu-form-label" for="input-text">Text Input</label>
  <input type="text" class="neu-input" id="input-text" placeholder="Text">
  <p class="neu-form-message">This is a required field</p>
</div>
```
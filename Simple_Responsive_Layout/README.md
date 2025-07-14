# Flexbox Layout Example

This project demonstrates the use of **CSS Flexbox** to create a flexible and responsive layout using a set of styled boxes.

## 📄 Description

In this example, we explore the following core concepts of Flexbox:

- `display: flex`
- `justify-content`
- `align-items`
- `flex-wrap`
- `gap`

A group of boxes is laid out using a flex container, showcasing how items can be aligned, spaced, and wrapped across rows.

## 📦 Key Concepts

### ✅ `display: flex`

The `.container` uses `display: flex` to activate flexbox behavior. This makes its children (the `.box` elements) flexible items that can be arranged using Flexbox properties.

### ✅ `justify-content`

Although commented out in the code, `justify-content` is used to align items along the main axis (horizontal by default).

Examples include:

- `justify-content: center` – centers items
- `justify-content: space-between` – spreads items with space in between

### ✅ `align-items`

This aligns the items vertically (cross-axis). In the code:

```css
align-items: center;
```

It centers the items vertically within the container.

### ✅ `flex-wrap`

By default, flex items try to fit in one line. `flex-wrap: wrap` allows the items to wrap onto multiple lines if there's not enough space.

### ✅ `gap`

The `gap` property adds spacing between items (both row and column gaps if wrapping is enabled).

## 🧱 Structure

The layout includes 12 identical `.box` elements, each with the same dimensions and styling, placed inside a `.container`.

```html
<div class="container">
  <div class="box">box 1</div>
  ...
  <div class="box">box 3</div>
</div>
```

## 🎯 Purpose

This project is a learning example to understand how Flexbox works and how different properties affect the layout and behavior of items inside a flex container.

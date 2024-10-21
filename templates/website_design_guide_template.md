# Website Design Guide

---

## Table of Contents

1. [Introduction](#introduction)
2. [Typography](#typography)
3. [Colors](#colors)
4. [Layout](#layout)
5. [Interactive Elements](#interactive-elements)
6. [Forms](#forms)

---

## Introduction

This guide outlines the visual and structural design elements of the website. Use it to maintain consistency in branding, user experience, and development.

---

## Typography

Choose fonts that are readable and align with the brand’s voice. Below are the font families, weights, and sizes used across the website:

- **Primary Font**: Arial, sans-serif
- **Secondary Font**: Georgia, serif
- **Heading Size**: 2rem
- **Body Text Size**: 1rem

---

## Colors

The following color palette is used to convey the brand's identity. Ensure consistency throughout all pages:

## Colors

The following color palette is used to convey the brand's identity. Ensure consistency throughout all pages:

- **Primary Blue:**   (#007bff)
- **Success Green:**   (#28a745)
- **Warning Yellow:**   (#ffc107)
- **Danger Red:**  (#dc3545)

---

## Layout

The website uses a responsive grid system with Bootstrap’s flexible layout. The container, row, and column classes are used to create consistent spacing and structure.

Example layout:

| Column 1 (33%) | Column 2 (33%) | Column 3 (33%) |
| -------------- | -------------- | -------------- |
| Content 1      | Content 2      | Content 3      |

---

## Interactive Elements

Make the website more engaging with interactive elements like buttons, forms, and modals. Below is an example of a Bootstrap button and a modal:

- **Button Example**:

```html
<button type="button" class="btn btn-primary">Launch Demo Modal</button>
```

---

## Forms

- **Form Examples**:

```html
<form>
  <div class="mb-3">
    <label for="email" class="form-label">Email address</label>
    <input type="email" class="form-control" id="email" placeholder="name@example.com">
  </div>
  <div class="mb-3">
    <label for="password" class="form-label">Password</label>
    <input type="password" class="form-control" id="password">
  </div>
  <button type="submit" class="btn btn-success">Submit</button>
</form>
```

- **Javascript Example**:

```javascript
    // Custom JavaScript for interactivity
    console.log("Website Design Guide Loaded");
```
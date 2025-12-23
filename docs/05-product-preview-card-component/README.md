# Product Preview Card — Frontend Mentor Challenge  
[English](#english) | [Español](#español)

---

# English Version <a id="english"></a>

## Frontend Mentor - Product preview card component solution
This is my solution to the  
**Product preview card component** challenge from Frontend Mentor.

This challenge focuses on building a **responsive product card**, combining imagery, typography, pricing details, and a call-to-action button using **semantic HTML** and **modern CSS**.

---

## Table of Contents

- [Product Preview Card — Frontend Mentor Challenge](#product-preview-card--frontend-mentor-challenge)
- [English Version ](#english-version-)
  - [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of Contents](#table-of-contents)
  - [Overview ](#overview-)
  - [Screenshots ](#screenshots-)
    - [Desktop Version](#desktop-version)
    - [Mobile Version](#mobile-version)
  - [Links ](#links-)
  - [Built With ](#built-with-)
  - [What I Learned ](#what-i-learned-)
    - [Example: Responsive layout with Flexbox ](#example-responsive-layout-with-flexbox-)
  - [Continued Development ](#continued-development-)
  - [Autor ](#autor-)

---

## Overview <a id="overview"></a>

The goal of this challenge was to recreate a **product preview card** as closely as possible to the provided design.

The component includes:
- A responsive product image (desktop and mobile)
- Product category label
- Product title and description
- Current and original price
- Add to cart button with icon

The layout adapts seamlessly between **desktop and mobile screen sizes**, ensuring clarity and usability across devices.

---

## Screenshots <a id="screenshots"></a>

### Desktop Version
![Desktop screenshot](./assets/images/product-preview-desktop.png)

### Mobile Version
![Mobile screenshot](./assets/images/product-preview-mobile.png)

---

## Links <a id="links"></a>

- **Frontend Mentor Solution:** *(Add when published)*  
- **Live Site (GitHub Pages):**  
  https://natdevx.github.io/frontend-mentor-solutions/docs/05-product-preview-card/

---

## Built With <a id="built-with"></a>

- Semantic HTML5  
- CSS custom properties  
- Flexbox  
- Responsive images (`<picture>`)  
- Desktop-first workflow  
- Media queries  
- Hover and focus states  

---

## What I Learned <a id="what-i-learned"></a>

In this challenge, I practiced and reinforced:

- Structuring reusable card components  
- Using the `<picture>` element for responsive images  
- Managing typography with multiple font families  
- Aligning pricing elements using Flexbox  
- Creating consistent spacing and visual hierarchy  
- Building responsive layouts with media queries  

### Example: Responsive layout with Flexbox <a id="example-responsive-layout-with-flexbox"></a>

The card layout switches from a horizontal layout on desktop to a vertical layout on mobile using a media query:

```css
@media (max-width: 600px) {
  .card {
    flex-direction: column;
  }
}
```

## Continued Development <a id="continued-development"></a>

In future projects, I want to continue improving:
- Pixel-perfect UI implementation.
- Accessibility and keyboard navigation.
- Scalable CSS architecture.
- More complex responsive components.

## Autor <a id="autor-es"></a>

GitHub: https://github.com/natdevx

Frontend Mentor: https://www.frontendmentor.io/profile/natdevx

---
---


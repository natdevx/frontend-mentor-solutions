# Recipe Page — Frontend Mentor Challenge  
[English](#english) | [Español](#español)

---
# English Version <a id="english"></a>

## Frontend Mentor - Recipe page solution
This is my solution to the  
**Recipe page** challenge from Frontend Mentor.

This challenge focuses on building a clean and accessible recipe layout, including structured content, lists, and a nutrition table, using **semantic HTML** and **modern CSS**.

---

## Table of Contents

- [Recipe Page — Frontend Mentor Challenge](#recipe-page--frontend-mentor-challenge)
- [English Version ](#english-version-)
  - [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of Contents](#table-of-contents)
  - [Overview ](#overview-)
  - [Screenshots ](#screenshots-)
    - [Desktop Version](#desktop-version)
    - [Mobile Version](#mobile-version)
  - [Links ](#links-)
  - [Built With ](#built-with-)
  - [What I Learned ](#what-i-learned-)
    - [Example: Nutrition table styling ](#example-nutrition-table-styling-)
  - [Continued Development ](#continued-development-)
  - [Author ](#author-)
- [Versión en Español ](#versión-en-español-)
  - [Frontend Mentor – Solución al Recipe Page](#frontend-mentor--solución-al-recipe-page)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Descripción General ](#descripción-general-)
  - [Capturas ](#capturas-)
    - [Versión Escritorio](#versión-escritorio)
    - [Versión Móvil](#versión-móvil)
  - [Enlaces ](#enlaces-)
  - [Construido Con ](#construido-con-)
  - [Lo que Aprendí ](#lo-que-aprendí-)
    - [Ejemplo: Estilos de tabla nutricional ](#ejemplo-estilos-de-tabla-nutricional-)
  - [Desarrollo Continuo ](#desarrollo-continuo-)
  - [Autor ](#autor-)

---

## Overview <a id="overview"></a>

The challenge consists of building a **recipe page layout**, which includes:

- A featured recipe image  
- Preparation time information  
- Ingredient list  
- Step-by-step instructions  
- A nutrition table  

The goal is to replicate the provided design as closely as possible while using **semantic HTML elements** and **clean, maintainable CSS**.

The layout is fully responsive and adapts smoothly to different screen sizes.

---

## Screenshots <a id="screenshots"></a>

### Desktop Version
![Desktop screenshot](./assets/images/recipe-page-desktop.png)

### Mobile Version
![Mobile screenshot](./assets/images/recipe-page-mobile.png)

---

## Links <a id="links"></a>

- **Frontend Mentor Solution:** *(Add when published)*  
- **Live Site (GitHub Pages):**  
  https://natdevx.github.io/frontend-mentor-solutions/docs/04-recipe-page/

---

## Built With <a id="built-with"></a>

- Semantic HTML5  
- Pure CSS  
- CSS custom properties  
- Flexbox  
- Mobile-first workflow  
- Responsive layout  
- Pseudo-classes and selectors  

---

## What I Learned <a id="what-i-learned"></a>

In this challenge, I practiced and reinforced:

- Structuring long-form content using semantic HTML  
- Styling lists and sections consistently  
- Building accessible tables for nutritional information  
- Controlling table borders using CSS selectors  
- Improving spacing and visual hierarchy  

### Example: Nutrition table styling <a id="example-nutrition-table-styling"></a>

One key detail in this challenge was removing the top border from the first table row while keeping separators between the rest:

```css
.nutrition-table tr:not(:first-child) th,
.nutrition-table tr:not(:first-child) td {
  border-top: 1px solid var(--stone-150);
}
```

## Continued Development <a id="continued-development"></a>
In future projects, I want to continue improving:
- CSS architecture and scalability.
- Accessibility best practices.
- More complex layouts.
- Pixel-perfect attention to design details

## Author <a id="author"></a>

GitHub: https://github.com/natdevx

Frontend Mentor: https://www.frontendmentor.io/profile/natdevx

---
---
# Versión en Español <a id="español"></a>

## Frontend Mentor – Solución al Recipe Page

Esta es mi solución al desafío  
**Recipe page** de Frontend Mentor.

Este reto se enfoca en crear una página de receta clara y accesible, utilizando **HTML semántico** y **CSS moderno**, con especial atención a listas, secciones y tablas.

---

## Tabla de Contenidos

- [Recipe Page — Frontend Mentor Challenge](#recipe-page--frontend-mentor-challenge)
- [English Version ](#english-version-)
  - [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of Contents](#table-of-contents)
  - [Overview ](#overview-)
  - [Screenshots ](#screenshots-)
    - [Desktop Version](#desktop-version)
    - [Mobile Version](#mobile-version)
  - [Links ](#links-)
  - [Built With ](#built-with-)
  - [What I Learned ](#what-i-learned-)
    - [Example: Nutrition table styling ](#example-nutrition-table-styling-)
  - [Continued Development ](#continued-development-)
  - [Author ](#author-)
- [Versión en Español ](#versión-en-español-)
  - [Frontend Mentor – Solución al Recipe Page](#frontend-mentor--solución-al-recipe-page)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Descripción General ](#descripción-general-)
  - [Capturas ](#capturas-)
    - [Versión Escritorio](#versión-escritorio)
    - [Versión Móvil](#versión-móvil)
  - [Enlaces ](#enlaces-)
  - [Construido Con ](#construido-con-)
  - [Lo que Aprendí ](#lo-que-aprendí-)
    - [Ejemplo: Estilos de tabla nutricional ](#ejemplo-estilos-de-tabla-nutricional-)
  - [Desarrollo Continuo ](#desarrollo-continuo-)
  - [Autor ](#autor-)

---

## Descripción General <a id="descripción-general"></a>

El reto consiste en crear una **página de receta**, que incluye:

- Imagen principal del platillo  
- Tiempo de preparación  
- Lista de ingredientes  
- Instrucciones paso a paso  
- Tabla de información nutricional  

El objetivo es replicar el diseño original proporcionado por Frontend Mentor usando **HTML semántico limpio** y **CSS bien estructurado**.

El diseño es completamente responsivo y se adapta correctamente a dispositivos móviles.

---

## Capturas <a id="capturas"></a>

### Versión Escritorio
![Desktop screenshot](./assets/images/recipe-page-desktop.png)

### Versión Móvil
![Mobile screenshot](./assets/images/recipe-page-mobile.png)

---

## Enlaces <a id="enlaces"></a>

- **Solución en Frontend Mentor:** *(Agrégala cuando la publiques)*  
- **Sitio en vivo (GitHub Pages):**  
  https://natdevx.github.io/frontend-mentor-solutions/docs/04-recipe-page/

---

## Construido Con <a id="construido-con"></a>

- HTML5 semántico  
- CSS puro  
- Variables CSS  
- Flexbox  
- Mobile-first  
- Diseño responsivo  
- Pseudo-clases CSS  

---

## Lo que Aprendí <a id="lo-que-aprendí"></a>

En este desafío practiqué:

- Estructurar contenido largo de forma clara  
- Estilizar listas e instrucciones  
- Crear tablas accesibles para datos nutricionales  
- Controlar bordes de tablas con selectores avanzados  
- Mejorar jerarquía visual y espaciado  

### Ejemplo: Estilos de tabla nutricional <a id="ejemplo-estilos-de-tabla-nutricional"></a>

Para evitar que la primera fila tuviera una línea superior, utilicé el siguiente selector:

```css
.nutrition-table tr:not(:first-child) th,
.nutrition-table tr:not(:first-child) td {
  border-top: 1px solid var(--stone-150);
}
```

## Desarrollo Continuo <a id="desarrollo-continuo"></a>

En futuros retos quiero seguir mejorando:
- Precisión visual (pixel-perfect).
- Arquitectura CSS más escalable.
- Accesibilidad y semántica.
- Layouts más complejos

## Autor <a id="autor-es"></a>

GitHub: https://github.com/natdevx

Frontend Mentor: https://www.frontendmentor.io/profile/natdevx

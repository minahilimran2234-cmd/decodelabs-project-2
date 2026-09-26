# ☕ Onyx & Oak | Premium Artisanal Coffee Website

A fully responsive, multi-page frontend website built with **pure HTML5 and CSS3**. Designed to showcase advanced CSS techniques, mobile-first architecture, and elegant UI/UX without relying on any JavaScript or external frameworks.

---

## 🚀 Project Overview

**Onyx & Oak** is a fictional premium coffee brand website. The primary goal of this project was to demonstrate strong **Responsive Web Design** skills by building a complete, production-ready multi-page website using **only HTML and CSS**. 

The design focuses on a dark, sophisticated aesthetic with warm amber accents, fluid typography, and an editorial-style layout that adapts seamlessly from mobile devices to large desktop screens.

---

## ✨ Key Features & Highlights

- **100% Pure CSS:** Zero JavaScript used. All interactions, including the mobile navigation, are handled via advanced CSS techniques.
- **CSS-Only Hamburger Menu:** Implemented using the `checkbox + label` hack for a smooth, accessible mobile navigation experience.
- **Mobile-First Approach:** Base styles are written for mobile devices, progressively enhanced for tablets and desktops using CSS Media Queries.
- **Fluid Typography:** Utilized CSS `clamp()` to ensure headings scale smoothly and perfectly across all screen sizes.
- **Advanced Layouts:** Heavy use of **CSS Grid** (for page layouts, galleries, and product grids) and **Flexbox** (for component alignment).
- **Asymmetric Gallery:** A creative, editorial-style masonry grid layout on the Gallery page.
- **Accessibility (a11y):** Semantic HTML5, proper ARIA labels, visible focus states, and keyboard-friendly navigation.
- **Optimized Performance:** Uses modern `.webp` image formats for faster loading times.

---

## ️ Tech Stack

- **HTML5** (Semantic Markup)
- **CSS3** (Custom Properties, Grid, Flexbox, Animations, Media Queries)
- **Google Fonts** (Playfair Display for headings, Inter for body text)

---

## 📁 Project Structure

```text
onyx-and-oak/
├── index.html          # Homepage
├── menu.html           # Coffee & Bakery Menu
├── about.html          # Brand Story & Team
├── gallery.html        # Asymmetric Image Gallery
├── contact.html        # Contact Form & Info
── style.css           # Master Stylesheet (Mobile-First)
├── README.md           # Project Documentation
└── assets/
    └── images/         # Optimized .webp images
        ├── hero.webp
        ├── team-*.webp
        └── ...
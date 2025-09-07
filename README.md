# DriftThreads — Streetwear & Drops Web App

DriftThreads is a modern, car-themed streetwear web project showcasing limited drops, hoodies, and supplements. It features a landing page, product showcase, interactive shopping cart, and WhatsApp-based ordering. Designed with a Joburg-inspired urban vibe, the platform focuses on smooth animations, responsive layouts, and accessible UI interactions.

---

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Accessibility & UX](#accessibility--ux)
- [Customization](#customization)

---

## Demo
- **Landing Page:** Streetwear + car culture branding.
- **Shop App:** Interactive grid of products with lazy loading, card flip effects, cart, lightbox, and WhatsApp order integration.

---

## Features

### Landing Page
- Animated gradient backgrounds and floating blobs for visual flair.
- Hero section highlighting limited drops.
- Featured products carousel with images and pricing.
- About section showcasing the team behind DriftThreads.
- Customer testimonials ("Word on the street").
- WhatsApp-based order CTA.
- Responsive and mobile-friendly.

### Shop Application
- Product grid with lazy loading batches for performance.
- Flip-card design revealing detailed descriptions and additional actions on back.
- Badges for sales, limited drops, or neutral promotions.
- Fully interactive shopping cart:
  - Add, remove, increment, decrement items.
  - Persistent using `localStorage`.
  - Sticky cart footer with subtotal and WhatsApp ordering.
- Search and category filter for quick product discovery.
- Image lightbox for enlarged product previews.
- Toast notifications for cart actions.
- One-time nudge tooltip encouraging card flips.

### UI & Interactions
- Smooth CSS transitions and keyframe animations.
- Scroll-to-top button with fade-in/out.
- Accessibility-focused (ARIA attributes, keyboard support, focus traps in modals).
- Preloader ensures smooth first-load experience.

---

## Tech Stack
- **HTML5 & CSS3**: Structure and styling with CSS variables for themes.
- **Vanilla JavaScript**: UI interactions, cart logic, filtering, lazy-loading.
- **Google Fonts**: Lexend and Orbitron for typography.
- **Font Awesome**: Iconography.
- **LocalStorage**: Persistent cart storage.
- **Responsive Design**: Mobile-first grid, flexible layouts.

---

## Project Structure

/assets <br>
├─ logo.png <br>
├─ favicon.png <br>
└─ placeholder.png <br>
/home <br>
├─ index.html (shop app) <br>
└── products/ <br>
├─── hoodies/ <br>
├─── supplements/ <br>
└─── other/ <br>
/index.html (landing page) <br>
README.md

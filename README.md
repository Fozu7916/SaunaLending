https://sauna-lending.netlify.app/
# 🌊 SaunaLending – Commercial Landing Page

**A responsive, high-conversion commercial landing page for a local premium sauna complex.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Responsive Design](https://img.shields.io/badge/Responsive-Design-4CAF50?style=for-the-badge)](#)

[🌐 View Live Demo](https://sauna-lending.netlify.app/)

## 📌 Project Overview

**SaunaLending** is a single-page commercial website designed to present the amenities of a two-story sauna complex ("Погружение") and seamlessly convert visitors into leads. The layout focuses on visual appeal, clear pricing structures, and immediate communication channels. 

The project strictly adheres to semantic **HTML5** standards and utilizes **Tailwind CSS** via CDN for rapid UI development, ensuring a lightweight footprint and exceptional mobile responsiveness without requiring a complex build step.

### ✨ Key Features

- **Lead Generation Focus:** Strategically placed Call-to-Action (CTA) buttons utilizing pre-filled WhatsApp API links (`wa.me`) to streamline the booking process.
- **Responsive Architecture:** Fully optimized for all viewports (Mobile, Tablet, Desktop) using Tailwind's mobile-first utility classes (`md:`, `lg:`, `sm:` breakpoints).
- **Smooth Anchor Navigation:** Implemented `scroll-smooth` behavior natively via CSS/HTML for fluid navigation across page sections.
- **Visual Presentation:** A dedicated CSS Grid gallery showcasing the core amenities (Pool, Sauna, Billiards, Relaxation Room) with modern hover scale effects and gradient overlays.
- **Analytics Ready:** Pre-configured slot within the `<head>` tag for immediate Yandex Metrica or Google Analytics integration.

## 🏗 Technical Structure

The landing page is logically divided into specialized semantic sections to maximize user retention and readability:

1. **Header & Navigation (`<header>`):** Sticky top bar (`fixed w-full top-0 z-50`) with anchor links to sections and a clickable phone number (`tel:`) for immediate mobile calling.
2. **Hero Section (`<section>`):** High-impact visual entry with a darkened background overlay (`bg-black bg-opacity-60`), core value proposition, pricing details, and the primary WhatsApp booking trigger.
3. **Gallery "All Inclusive" (`#gallery`):** A CSS Grid layout (`grid-cols-1 sm:grid-cols-2 lg:grid-cols-4`) displaying the complex's facilities utilizing interactive hover states (`group-hover:scale-110`).
4. **Upsell Services (`#services`):** Flexbox/Grid combination presenting additional revenue streams (Food, PS4, Bath accessories) in clean, card-based layouts.
5. **Comprehensive Footer (`<footer>`):** Contact information, address, operating hours, and a placeholder for a physical facade image or interactive map snippet to aid local navigation.

## 💻 Tech Stack Justification

*   **HTML5:** Selected for structural semantic integrity, crucial for local SEO indexing (Search Engine Optimization) which is vital for offline businesses.
*   **Tailwind CSS (CDN):** Chosen to eliminate the necessity for external stylesheet files, CSS architecture overhead (BEM, OOCSS), and to drastically speed up the development process while maintaining a strictly uniform design system.
*   **Vanilla JS (Zero Dependencies):** Kept dependency-free to guarantee instant page load speeds, a critical metric for mobile ad conversions.

## 🚀 Deployment

The project is entirely static and requires no server-side rendering or complex build pipelines. 

To run locally:
1. Clone the repository.
2. Ensure the `/images` directory is populated with the correct assets (`hero-bg.png`, `pool.webp`, `sauna.webp`, `billiards.png`, `relax.webp`, `facade.webp`).
3. Open `index.html` in any modern web browser.

The project is natively ready for deployment on platforms like **Netlify**, **Vercel**, or **GitHub Pages**.

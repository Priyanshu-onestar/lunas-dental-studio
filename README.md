# Luna's Dental Studio — Premium Dental Care Landing Page

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Website-brightgreen?style=for-the-badge)](https://priyanshu-onestar.github.io/lunas-dental-studio/)

> 🌐 **Live Website**: [https://priyanshu-onestar.github.io/lunas-dental-studio/](https://priyanshu-onestar.github.io/lunas-dental-studio/)

A modern, responsive, high-converting editorial landing page built for **Luna's Dental Studio**, a boutique clinic specializing in aesthetic dentistry, smile makeovers, and personalized oral wellness. Designed with an editorial luxury aesthetic, accessible UI patterns, and lightweight vanilla web technologies.

![Luna's Dental Studio Preview](https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e?auto=format&fit=crop&q=80&w=1200)

---

## ✨ Features

- **Luxury Editorial Design**: Tailored for high-end boutique dental practices using bespoke typography (*Cormorant Garamond* & *Manrope*) and an organic, calming palette.
- **Pure Vanilla Web Tech**: Zero external build dependencies or frameworks—crafted with pure semantic HTML5, CSS3 custom properties, and modern vanilla JavaScript.
- **Fully Responsive**: Fluid typography and spacing (`clamp()`), mobile slide-out navigation with focus management, and responsive breakpoints audited from 375px mobile screens up to 4K displays.
- **Interactive UI Components**:
  - Sticky glassmorphic navigation with scroll detection and mobile hamburger drawer.
  - Scroll-triggered reveal animations powered by `IntersectionObserver`.
  - Touch-enabled, accessible testimonial carousel with keyboard & swipe navigation.
  - Interactive appointment booking form with animated floating labels, custom client-side validation, and feedback state.
- **Accessibility & Performance First**: Built-in ARIA attributes, semantic landmarks, high-contrast focus rings, `prefers-reduced-motion` compliance, lazy-loaded media assets, and high-priority hero loading.

---

## 🎨 Design System

| Element | Specification |
|---|---|
| **Warm Ivory** | `#FAF9F6` (Primary light background & canvas) |
| **Forest Green** | `#34483D` (Primary brand accent & deep contrast elements) |
| **Sage** | `#A9B5A0` (Secondary accents & floating label highlights) |
| **Champagne** | `#D9C9B5` (Subtle borders, dividers & luxury accents) |
| **Charcoal** | `#343632` (High-legibility body copy) |
| **Serif Heading** | Cormorant Garamond (Google Fonts) |
| **Sans Body** | Manrope (Google Fonts) |

---

## 📁 Project Structure

```text
├── index.html                 # Main entrypoint (ready for GitHub Pages)
├── lunas_dental_studio.html   # Original standalone landing page template
├── README.md                  # Project documentation
├── LICENSE                    # MIT License
└── .gitignore                 # Git ignore file
```

---

## 🚀 Getting Started

### 1. View Locally
Simply clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/Priyanshu-onestar/lunas-dental-studio.git
cd lunas-dental-studio

# Open index.html in your default browser:
# On Windows:
start index.html

# On macOS:
open index.html

# On Linux:
xdg-open index.html
```

Or serve using Python:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

### 2. Host on GitHub Pages
1. Go to repository **Settings** on GitHub.
2. Select **Pages** from the sidebar.
3. Under **Branch**, select `main` and root folder `/`.
4. Click **Save**. Your site will be live at `https://priyanshu-onestar.github.io/lunas-dental-studio/`!

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

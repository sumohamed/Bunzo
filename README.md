# 🍔 Bunzo

A responsive landing page for a fictional fast-food restaurant, built with pure HTML and CSS. Bunzo showcases a full one-page website structure: hero section, menu, gallery, deals, customer reviews, and a contact form — all fully responsive and animated.

**🔗 Live Demo:** [sumohamed.github.io/Bunzo](https://sumohamed.github.io/Bunzo/)

## 📋 Overview

Bunzo is a front-end practice project focused on building a complete, production-style landing page from scratch — without any CSS framework. The goal was to practice structuring a real-world multi-section website, writing clean and scalable CSS architecture, and making everything responsive across devices.

## ✨ Sections

- **Header** — Sticky navigation with mobile toggle menu
- **Hero** — Main banner with stats cards and call-to-action buttons
- **Vendors** — Ingredient partners strip
- **Menu** — Grid of featured menu items
- **Gallery** — Image showcase
- **Deals** — Combo/meal deal cards
- **Reviews** — Customer testimonials
- **Contact** — Contact form and business info
- **Footer** — Site links, newsletter signup, and social links

## 🛠️ Built With

- **HTML5** — Semantic markup
- **CSS3** — Custom architecture using CSS variables, nesting, and `color-mix()`
- **[Font Awesome](https://fontawesome.com/)** — Icons
- **[Unsplash](https://unsplash.com/)** — Photography
- **[chatgpt](https://chatgpt.com/)** — Photography too

## 🎨 CSS Architecture

The stylesheet is split into modular files for maintainability:

| File              | Purpose                                              |
| ----------------- | ---------------------------------------------------- |
| `variables.css`   | Design tokens — colors, spacing, typography, shadows |
| `reset.css`       | Base browser reset                                   |
| `globals.css`     | Reusable utility classes and shared components       |
| `typography.css`  | Heading, paragraph, and font styles                  |
| `layout.css`      | Header and footer layout                             |
| `grid-system.css` | Custom responsive grid utilities                     |
| `animations.css`  | Keyframe animations                                  |
| `fonts.css`       | Self-hosted `@font-face` declarations                |
| `home.css`        | Page-specific styles                                 |

## 📱 Responsive Design

Built mobile-first with a custom grid system (`auto-fit`/`minmax`) that adapts across breakpoints without relying on a framework.

## 🚀 Getting Started

Clone the repo and open `index.html` in your browser — no build step required.

```bash
git clone https://github.com/sumohamed/Bunzo.git
cd Bunzo
```

## 📄 License

This project is for educational/portfolio purposes. Fonts, icons, and images are used under their respective licenses (Font Awesome, Unsplash).

## 👤 Author

**Sumohamed**

- GitHub: [@sumohamed](https://github.com/sumohamed)

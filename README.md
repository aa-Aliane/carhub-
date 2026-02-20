# CareHub | Santé Connectée

CareHub is a modern, high-performance landing page for a connected health platform, built with **Astro**. It features a clean, responsive design focused on accessibility and user engagement.

## 🚀 Project Overview

This project serves as the digital storefront for CareHub, highlighting its features, testimonials, and pricing plans to convert visitors into users.

### Key Sections
- **Hero**: Engaging introduction to the platform.
- **About**: Detailed insights into CareHub's mission.
- **Features**: Showcase of the platform's core capabilities.
- **Testimonials**: Social proof from satisfied users.
- **Pricing**: Transparent subscription models.
- **Final CTA**: Last nudge for user conversion.
- **Responsive Navigation & Footer**: Seamless site-wide browsing.

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build/) (v5.0+)
- **Styling**: [CSS Modules](https://github.com/css-modules/css-modules) for component-scoped styling.
- **Formatting**: [Prettier](https://prettier.io/) with Astro plugin.
- **Language**: TypeScript/JavaScript.

## 📁 Project Structure

```text
/
├── public/             # Static assets (favicons, manifest)
├── src/
│   ├── assets/         # Images, icons, and SVG backgrounds
│   ├── components/     # UI components (About, Hero, Navbar, etc.)
│   ├── layouts/        # Page layouts
│   ├── pages/          # Site routes (index.astro)
│   └── styles/         # Global styles
├── astro.config.mjs    # Astro configuration
└── package.json        # Project dependencies and scripts
```

## 🏃 Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed.

### Installation

```bash
npm install
```

### Development

Start the local development server:

```bash
npm run dev
```

The site will be available at `http://localhost:4321`.

### Build

To build the project for production:

```bash
npm run build
```

The output will be in the `dist/` directory.

### Preview

Preview the production build locally:

```bash
npm run preview
```

## ✨ Development Guidelines

- **Components**: Follow the existing structure in `src/components/`. Each component should have its own folder containing an `index.astro` and a `.module.css` file.
- **Styling**: Prefer CSS Modules for component-specific styles to avoid global namespace pollution.
- **Linting**: Run Prettier regularly to maintain consistent code formatting.

---

Built with ❤️ using Astro.

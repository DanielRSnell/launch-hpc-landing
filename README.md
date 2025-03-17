# LaunchHPC Theme

A modern, responsive Astro-based website theme for LaunchHPC, a company providing enterprise-grade AI and high-performance computing infrastructure solutions.

## Overview

This theme is built using Astro framework with React components, Tailwind CSS, and various modern web technologies to create a fast, responsive, and visually appealing website for LaunchHPC's enterprise offerings.

## Features

- **Modern Tech Stack**: Built with Astro, React, and Tailwind CSS
- **Responsive Design**: Fully responsive layout that works on all device sizes
- **Component-Based Architecture**: Modular components for easy customization
- **Content Collections**: Structured content management using Astro's content collections
- **Blog Support**: Built-in blog functionality with MDX support
- **SEO Optimized**: Meta tags, canonical URLs, and sitemap generation
- **Performance Focused**: Fast loading times and optimized assets
- **Animations**: Smooth animations using AOS (Animate On Scroll)
- **Dark Mode Support**: Built-in light and dark mode theming

## Tech Stack

- **Framework**: [Astro](https://astro.build/) v5.4.1
- **UI Library**: [React](https://reactjs.org/) v19.0.0
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) v4.0.9
- **Animations**: [AOS](https://michalsnik.github.io/aos/) v2.3.4
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/) v5.5.0
- **Date Handling**: [date-fns](https://date-fns.org/) v4.1.0
- **Markdown**: MDX with various remark plugins
- **Code Highlighting**: [Shiki](https://shiki.matsu.io/) v3.1.0

## Directory Structure

```
src/
├── config/            # Configuration files
├── content/           # Content collections
├── layouts/           # Layout components
│   ├── components/    # Reusable layout components
│   ├── helpers/       # Helper components
│   ├── partials/      # Partial components (header, footer, etc.)
│   └── shortcodes/    # Shortcode components for MDX
├── lib/               # Utility functions and libraries
├── pages/             # Page components and routes
├── styles/            # Global styles and Tailwind configuration
├── tailwind-plugin/   # Custom Tailwind plugins
└── types/             # TypeScript type definitions
```

## Getting Started

### Prerequisites

- Node.js v20 or higher
- PNPM package manager

### Installation

1. Clone the repository
2. Navigate to the theme directory
3. Install dependencies:

```bash
nvm use 20
pnpm install
```

### Development

Start the development server:

```bash
pnpm dev
```

### Building for Production

Build the site for production:

```bash
pnpm build
```

Preview the production build:

```bash
pnpm preview
```

## Content Management

The theme uses Astro's content collections for managing structured content. Collections are defined in `src/content.config.ts` and include:

- Pages (about, blog, changelog, contact, feature, integration, pricing)
- Sections (banners, CTAs, features, pricing, testimonials, etc.)

## Customization

### Theme Configuration

The main configuration files are located in the `src/config/` directory:

- `config.json`: General site configuration (title, URLs, metadata)
- `theme.json`: Theme-specific settings (colors, fonts, etc.)

### Styling

The theme uses Tailwind CSS for styling. Global styles are defined in `src/styles/main.css`.

## Deployment

The theme includes configuration for deployment to Netlify and can be easily deployed to other platforms that support Astro.

## License

This theme is licensed under the terms specified in the project's license file.

## About LaunchHPC

LaunchHPC delivers comprehensive infrastructure solutions to power today's most demanding AI and high-performance computing workloads. From advanced cloud deployment to performance optimization and real-time observability, LaunchHPC empowers organizations to achieve breakthrough results while seamlessly scaling between on-premise systems and cloud-based solutions.

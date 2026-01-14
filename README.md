# Flat Roofing Services - Astro Project

A professional informational pillar page for commercial roofing services in Northern Indiana, built with Astro.

## Project Structure

```
├── public/              # Static assets (images, etc.)
│   ├── Logo.jpeg
│   └── commercial-flat-roof.jpeg
├── src/
│   ├── pages/          # Astro pages (routes)
│   │   └── index.astro # Main page
│   └── styles/         # CSS stylesheets
│       └── styles.css
├── astro.config.mjs    # Astro configuration
├── package.json        # Dependencies and scripts
├── tsconfig.json       # TypeScript configuration
└── vercel.json        # Vercel deployment configuration
```

## Getting Started

### Prerequisites
- Node.js 18+ and npm

### Installation
```bash
npm install
```

### Development
```bash
npm run dev
```
Runs the development server at `http://localhost:4321`

### Build
```bash
npm run build
```
Builds the site for production to the `dist/` folder.

### Preview
```bash
npm run preview
```
Preview the production build locally.

## Deployment

This project is configured for deployment on Vercel. Vercel will automatically:
- Detect Astro framework
- Run `npm run build`
- Serve files from the `dist/` directory

## Features

- Responsive design (mobile, tablet, desktop)
- Professional styling matching Tru-Kote design
- Scroll-triggered animations
- Hamburger menu for mobile navigation
- Optimized static site generation

# Brainwave

A modern, responsive landing page for a fictional AI chat product, built as a single-page React application. The site walks visitors through the product story across a Hero, Benefits, Collaboration, Services, Pricing, and Roadmap section, finishing with a Footer — all styled with a dark, gradient-heavy aesthetic and subtle parallax effects.

This is a UI-focused project (no backend, no real chat functionality). It's useful as a portfolio piece, a starting template for SaaS-style marketing sites, or a reference for composing complex Tailwind layouts in React.

## Tech stack

- **React 18** with **Vite 6** for the dev server and build
- **Tailwind CSS 3** for styling
- **react-router-dom** for routing primitives
- **react-just-parallax** for scroll-based parallax effects
- **scroll-lock** for modal/menu scroll handling
- **ESLint 9** for linting

## Getting started

```bash
npm install
npm run dev      # start the Vite dev server
npm run build    # production build
npm run preview  # preview the production build locally
npm run lint     # run ESLint
```

## Project structure

```
src/
  App.jsx              # composes the page sections
  assets/              # images, SVGs, icon exports
  components/          # section components (Hero, Pricing, Roadmap, ...)
  components/design/   # decorative sub-components (gradients, backgrounds)
  constants/           # navigation, pricing, roadmap, and feature data
```

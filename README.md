# PortfolioMe — 3D Developer Portfolio

A multi-page developer portfolio built with **React, Vite, Three.js, and React Three Fiber**. It combines motion effects and 3D visuals with sections for an introduction, about page, skills, experience, projects, and contact.

## Features

- Interactive 3D hero scene and floating objects
- About, skills, experience, projects, and contact sections
- Project listing and project detail views
- Shared navigation and footer layout
- Framer Motion transitions
- Reusable UI components and responsive styles

## Tech stack

- React and Vite
- Three.js, React Three Fiber, and Drei
- Framer Motion
- React Router
- Lucide and React Icons

## Run locally

The Vite application is in `PortfolioMe/`:

```bash
cd PortfolioMe
npm install
npm run dev
```

Open the local URL printed by Vite. To create a production build, run `npm run build` from `PortfolioMe/`.

## Project structure

- `PortfolioMe/src/pages/` — route-level pages
- `PortfolioMe/src/sections/` — page sections and layouts
- `PortfolioMe/src/components/three/` — reusable 3D components
- `PortfolioMe/src/data/` — portfolio content and project data
- `hero/` — standalone hero-scene files also present at the repository root

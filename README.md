# Wave Assembly — DJ Portfolio

A clean static portfolio site for **Wave Assembly**, built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com).

## Features

- Fixed top navigation with hover highlight effects
- Single-page layout: Hero, About, Music, Press Kit, Gigs, Contact
- Embedded SoundCloud player ([waveassembly](https://soundcloud.com/waveassembly))
- Press kit with bios and downloadable asset links
- Dark theme with purple accent palette
- Fully static — fast to load, easy to deploy
- Mobile-responsive with collapsible menu

## Getting started

Requires [Node.js](https://nodejs.org/) 18 or later.

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

## Build for production

```bash
npm run build
npm run preview
```

The static output is in the `dist/` folder, ready to deploy to Netlify, Vercel, GitHub Pages, or any static host.

## Customize

- **Mixes & gigs** — Update the `gigs` array in `src/pages/index.astro`
- **Press assets** — Add files to `public/press/` (photos, logo, rider, EPK)
- **Colors** — Tweak CSS variables in `src/styles/global.css`
- **Contact email & social links** — Update the Contact and Press Kit sections in `index.astro`

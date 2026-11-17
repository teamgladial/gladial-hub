# Gladial Hub

The static front door for Gladial at [gladial.com](https://gladial.com), linking to the Journal, Labs, Music, and Novels.

## Local development

```sh
npm install
npm run dev
```

## Build and deploy

This is a static Astro site with no server adapter. For Cloudflare Pages, set the build command to `npm run build` and the build output directory to `dist`. Use Node.js `>=22.12.0`.

```sh
npm run build
npm run preview
```

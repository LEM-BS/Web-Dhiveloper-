# Web Dhiveloper — Astro Source Project

A fast static website for your agency: **Astro + Tailwind**, **Markdown case studies**, **Netlify-ready forms**, and **auto sitemap**.

## Quickstart
1. Install dependencies
   ```bash
   npm install
   ```
2. Run locally
   ```bash
   npm run dev
   ```
3. Build
   ```bash
   npm run build
   ```
   The static site will be generated in `dist/`.

## Deploy to Netlify
- Build command: `npm run build`
- Publish directory: `dist`
- Forms: contact form uses `data-netlify="true"` and posts to `/success`

## Content
- Pages in `src/pages/*`
- Case studies in `src/pages/case-studies/*.md`
- Global styles in `src/styles/global.css`
- Header/footer in `src/components/*`
- Public assets (logo, images) in `public/images`

## Replace placeholders
- Put your real logo at `public/images/logo.webp` (and optionally `logo.png`).
- Update email and phone in `src/components/Footer.astro`.
- Replace `site` in `astro.config.mjs` with your domain.
- Update meta titles/descriptions as you like on each page.

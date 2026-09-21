# draganlulic.com

Astro 7 + Tailwind 4, static build, zero client-side JS.

## Run

    npm install
    npm run dev       # http://localhost:4321
    npm run build     # output in dist/

## Structure

- src/pages/index.astro        Home (all copy + JSON-LD live here for now)
- src/layouts/Base.astro       head, meta, canonical, OG, JSON-LD slot
- src/components/              Header, Footer
- src/styles/global.css        Tailwind theme (brand colors, fonts, utilities)
- public/                      robots.txt, logo, favicon, photo, CV, OG image

## Before launch

- Replace public/og-default.png with a real 1200x630 image
- Set the Formspree endpoint in the contact form (REPLACE_ME)
- Pages still to build: /testimonials/, /case-studies/*/

# Gara Durga Prasad — talking-video portfolio
Run: `npm install && npm run dev` (build: `npm run build`).
Content: everything comes from `src/lib/data.ts` (sourced only from the résumé).
Rebuild hero: `python3 scripts/build-hero-assets.py <intro.mp4> [crop_x]` (needs ffmpeg + numpy). Outputs go to `public/`.
Sections: Hero, About (ID card), Skills (11 tiles), Work (1 project), Certifications (2), Experience (2 stops), Contact. Achievements removed: no data in the résumé.
Not included yet: Lenis, Tailwind, self-hosted fonts (system fallbacks used; add woff2 to `src/fonts`), brand logos, card pendulum physics.


# Uptiq — Algo Finder (React + Vite + Tailwind)

This is a single-file React landing page with a built-in multi-step questionnaire that recommends Uptiq strategies.

## Deploy on Vercel (no coding):
1. Zip this folder and upload it to Vercel → New Project → Import → Upload.
2. Framework preset: **Vite**. Click Deploy.
3. Your live URL will look like `https://uptiq-finder.vercel.app`.

## Embed on your site (WordPress/Webflow/etc.)
Create a page (e.g. `/find-my-algo`) and paste:

```html
<iframe
  src="https://uptiq-finder.vercel.app"
  width="100%"
  height="1500"
  style="border:0;border-radius:16px;overflow:hidden"
  allowfullscreen
></iframe>
```

## Local dev (optional):
```bash
npm install
npm run dev
```

## Edit links & content:
- Replace CTA links in `src/App.jsx` (`#signup`, `#demo`, `#learn`).
- Update the `ALGORITHMS` array with your real strategies.

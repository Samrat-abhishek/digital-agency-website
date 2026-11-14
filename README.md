# Your Agency — Astro website starter

A responsive, single-page digital marketing agency website built with Astro. Designed to deploy as a static site on Cloudflare Pages.

## Before publishing

Replace these placeholders in `src/pages/index.astro`:

- `YOUR AGENCY` and `Your Agency` with your final agency name.
- `hello@yourdomain.com` with your real business email.
- `https://wa.me/910000000000` with your WhatsApp link. Use country code + number, digits only.
- Update service descriptions to match the services you actually provide.
- Add real client work, testimonials and case studies only when you have permission and verifiable details.

The current contact actions are email and WhatsApp links. There is no backend enquiry form yet, so do not describe it as a working form.

## Run locally

Install Node.js, then run:

```bash
npm install
npm run dev
```

Open the local address Astro prints in your terminal.

## Build

```bash
npm run build
```

The generated static website is placed in `dist/`.

## Deploy to Cloudflare Pages

1. Create a GitHub repository and upload the contents of this project.
2. In Cloudflare, open **Workers & Pages** → **Create application** → **Pages** → **Connect to Git**.
3. Select your GitHub repository.
4. Set the build command to `npm run build`.
5. Set the build output directory to `dist`.
6. Deploy. Cloudflare will provide a `*.pages.dev` address.
7. Add your custom domain later in the Pages project settings.

## Notes

- This project is static and does not require PHP or a database.
- Astro generates HTML at build time; this is suitable for SEO-friendly service pages.
- Google Fonts are loaded externally. For stricter privacy or fully self-hosted fonts, replace them with locally hosted font files.
- Add a privacy policy and cookie notice if your analytics, advertising pixels or lead capture setup requires them.

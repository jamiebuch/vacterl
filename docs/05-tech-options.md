# Technical options (open-source first, low maintenance)

## Recommendation

Static site + free/cheap hosting + hosted video/donations. No server to patch, committee can edit via Markdown or a simple CMS.

Preferred: `Astro` (MIT) with content collections in `src/content/`, deployed to `Cloudflare Pages` or `GitHub Pages` (both free for charities). Alternative with zero build: `Eleventy` (MIT) or `Hugo` (Apache-2.0). Avoid WordPress unless committee explicitly needs it — higher maintenance.

Local builds with `podman`, not Docker, per repo policy.

```bash
podman run --rm -v "$PWD:/app:z" -w /app node:22-alpine npx astro build
```

## Hosting / domain

* Confirm domain (previous site lost — check registrar, Nominet for `.org.uk`). Use Cloudflare DNS (free) + Pages.
* HTTPS enforced, custom 404, redirects from old URLs if known.
* Analytics: privacy-friendly, self-hosted `Plausible` CE or `Umami` (MIT), or no analytics initially. No Google Analytics without consent banner.

## Content editing

* Option A (simplest): Markdown in git + Netlify/Decap CMS (open-source) for non-technical editors.
* Option B: committee edits via GitHub web UI with review. Provide `CONVENTIONS.md` workflow.

## Forms / membership / contact

* Static form → open-source backend: `Formspree` free tier is proprietary — prefer self-hosted `Formbunker` or Cloudflare Workers + `Resend`/`SMTP`, or low-cost `Tally` with DPA. Store minimal data, GDPR privacy notice, safeguarding statement. Do not collect medical details via open form.

## Donations

* Slide 14 (`image27.png`) shows the association already uses **JustGiving** (with a QR code + JustGiving wordmark under the umbrella logo). Confirm the live JustGiving page URL and Gift Aid setup first.
* Alternatives if migrating or adding direct links: `Stripe Payment Links`, `PayPal Giving Fund`, or `Open Collective` (open-source platform). Do not build custom card handling. Confirm charity number first (applied Oct 2023 per TOFS article — verify).

## Video (500+ MB MP4s cannot ship in git/site)

* Upload full films to YouTube (unlisted/public per consent) or self-hosted `PeerTube`. Embed with `lite-youtube-embed` (MIT) for performance.
* Generate: 720p compressed MP4/WebM, poster JPG, `.vtt` captions, full transcript on `/stories` page. See `07-media-rights-video-plan.md`.
* Keep originals in private archive (e.g. external drive / Nextcloud), not in repo. `origdocs/` is already gitignored.

## Accessibility / SEO / legal

* WCAG 2.2 AA, semantic HTML, alt text, transcripts, keyboard nav, `prefers-reduced-motion` respected.
* SEO: sitemap.xml, Open Graph with logo, JSON-LD `NGO` schema once charity number confirmed.
* Legal: privacy notice, cookie policy (if analytics), safeguarding, `information not medical advice` disclaimer on health pages, link policy for partners.

## What not to do

* No paid themes/plugins, no Google Fonts tracking (self-host fonts), no large binaries in git, no children's personal data in repo.

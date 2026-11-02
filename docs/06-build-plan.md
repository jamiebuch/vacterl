# Build plan

## Phase 0 — Confirm (committee, 1 week)

* [ ] Permanent email/domain, Facebook/Instagram ownership, charity number/status
* [ ] Photo/video consent for every identifiable person (see `07-media-rights-video-plan.md`)
* [ ] Donate provider + Gift Aid, membership form fields + GDPR basis, safeguarding contact
* [ ] Pick stack: Astro + Cloudflare/GitHub Pages (recommended in `05-tech-options.md`)

## Phase 1 — Content freeze (1–2 weeks)

* [ ] Review `03-copy-draft.md`, clinician check for `What is VACTERL?`
* [ ] Transcribe TOFS 2024 article with permission; write Get-Together 2025 summary
* [ ] Select ≤20 launch photos, write alt text, compress to WebP
* [ ] Transcribe/caption both films, choose poster frames

## Phase 2 — Site skeleton (1–2 weeks)

* [ ] Init Astro (or Eleventy/Hugo) in `site/`, `podman`-based build, open-source only
* [ ] Implement pages from `02-sitemap-ia.md`, header/footer, 404, sitemap.xml, RSS optional
* [ ] Design tokens from `04-design-brand.md`, Atkinson Hyperlegible + Nunito self-hosted
* [ ] Contact/membership forms (no medical data), donate links, video embeds with transcripts

## Phase 3 — Assurance

* [ ] WCAG 2.2 AA check (keyboard, contrast, captions), Lighthouse ≥90, link check
* [ ] Privacy/cookies/safeguarding review, charity footer, review dates on health pages
* [ ] Committee UAT on mobile + desktop, proofread

## Phase 4 — Launch

* [ ] DNS cutover, HTTPS, analytics (or none), backup + editor guide
* [ ] Update `README.md`, `CONVENTIONS.md`, `VERSION`
* [ ] Tag release, ask user before commit/push per repo policy

Maintenance: quarterly content review, annual accessibility check, dependency updates via `podman`.

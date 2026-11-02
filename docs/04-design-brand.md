# Design & brand notes

Source: `docs/assets/source-material/logo-umbrella.jpg` (`hi res vacterl logo.jpg`).

## Logo anatomy

Rainbow umbrella, left-to-right panels: yellow `V`, red-orange `A`, green `C`, blue `T`, lavender `E`, orange `R`, cyan `L`. Below: `ASSOCIATION` in grey sans, umbrella handle as `J`-like stem, family pictograms (orange child, blue adult, red adult, purple child) + `Support Group` in grey.

Use the hi-res JPG as reference only. Request vector (SVG/AI/EPS) from designer for web. Do not stretch, recolour, or place on low-contrast backgrounds.

## Palette (sampled from logo — confirm hex with designer)

* Yellow panel ~ `#FFE600`
* Red-orange ~ `#FF2E1F`
* Green ~ `#00E838`
* Mid blue ~ `#5B7CFF`
* Lavender ~ `#CFAFFF`
* Orange ~ `#FF6A00`
* Cyan ~ `#00E5FF`
* Body grey ~ `#4A4A4A` on white

Accessibility: rainbow panels are decorative. Body text must meet WCAG 2.2 AA (4.5:1). Grey `#4A4A4A` on white passes; coloured panels do not — never put body copy on them. Use white cards + one accent per section.

## Typography & tone

* Friendly, parent-led, plain English. Avoid clinical jargon without explanation.
* Headings: rounded humanist sans (e.g. open-source `Nunito`, `Atkinson Hyperlegible` for accessibility). Body: highly legible sans with true bold/italic.
* Open-source only per repo policy — no paid fonts. Suggested pairing: `Atkinson Hyperlegible` (body) + `Nunito` (display). Both OFL.

## Imagery

* Prefer real Get-Together / pop-up photos with consent over stock.
* Curated set: `bristol-popup-banner.jpg`, `information-station.jpg`, `volunteers-2025-03-01.jpg`, `pptx-extracted/*.jpg`.
* Rules: no identifiable children without written consent; no surnames; alt text mandatory; compress to WebP/AVIF ≤200 KB per image; keep originals out of git (see `07-media-rights-video-plan.md`).
* Videos: custom poster frame, captions + transcript, no autoplay with sound.

## Layout

* Mobile-first, single column, large tap targets (≥44px), visible focus states.
* Header: logo left, nav + Donate button right. Footer: charity number (TBC), contact, socials, safeguarding/privacy/accessibility links.
* Cards for V-A-C-T-E-R-L letters using panel colours as top border only (accessible).

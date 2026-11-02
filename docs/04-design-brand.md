# Design & brand notes

Source: `docs/assets/source-material/logo-umbrella.jpg` (`hi res vacterl logo.jpg`).

## Logo anatomy

Rainbow umbrella, left-to-right panels: yellow `V`, red-orange `A`, green `C`, blue `T`, lavender `E`, orange `R`, cyan `L`. Below: `ASSOCIATION` in grey sans, umbrella handle as `J`-like stem, family pictograms (orange child, blue adult, red adult, purple child) + `Support Group` in grey.

Use the hi-res JPG as reference only. Request vector (SVG/AI/EPS) from designer for web. Do not stretch, recolour, or place on low-contrast backgrounds.

## Palette (sampled from logo — confirm hex with designer)

Raw umbrella panel colours:
* Yellow panel ~ `#FFE600`
* Red-orange ~ `#FF2E1F`
* Green ~ `#00E838`
* Mid blue ~ `#5B7CFF`
* Lavender ~ `#CFAFFF`
* Orange ~ `#FF6A00`
* Cyan ~ `#00E5FF`
* Body grey ~ `#4A4A4A` on white

### Modernised v2 web design tokens (warm, accessible, healthcare-trust)

To prevent the 7 rainbow panels from looking dated or failing WCAG contrast on light backgrounds, v2 uses a warm, reassuring surface palette (`#FCFBF9` warm alabaster, `#F4F1EA` softoat, `#EEF3FF` soft sky) paired with deep slate-navy (`#162032`) for primary typography and paired **border + accessible badge** tokens for each V-A-C-T-E-R-L panel:

* **V (Vertebral)**: Accent `#E5A000` · Soft surface `#FFF8DB` · Text `#6E4B00`
* **A (Anal)**: Accent `#E03131` · Soft surface `#FFF0F0` · Text `#8A1C1C`
* **C (Cardiac)**: Accent `#0CA678` · Soft surface `#E6FCF5` · Text `#085E44`
* **T (Tracheo-)**: Accent `#3B5BDB` · Soft surface `#EDF2FF` · Text `#1E3A8A`
* **E (Oesophageal)**: Accent `#7950F2` · Soft surface `#F3F0FF` · Text `#442399`
* **R (Renal / Radius)**: Accent `#F76707` · Soft surface `#FFF4E6` · Text `#8C3800`
* **L (Limb)**: Accent `#0C8599` · Soft surface `#E3FAFC` · Text `#074F5B`

Accessibility: raw rainbow panels are decorative only. Body and badge text must meet WCAG 2.2 AA (≥4.5:1). Never put body copy on raw neon panels; use white/warm-ivory cards with top/left accent bars and accessible dark-tinted badge text.

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

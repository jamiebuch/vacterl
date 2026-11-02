# Homepage mockups (v2 — production-ready view)

Four static HTML pages to compare direction. Open directly in a browser — no build step required. Images load from `../assets/`. All draft/TBC notes, consent reminders, and technical placeholders have been moved out of the HTML and into the planning documentation (`docs/01-content-inventory.md`–`docs/07-media-rights-video-plan.md`).

* **`home-v4-modern-flagship.html` (Recommended v2 Flagship)** — Full production-style homepage combining all key sections:
  * **Prominent Brand Lockup:** 88×88px framed logo badge in the sticky header, hero brand callout badge, floating circular umbrella emblem on the hero photo card, and 68×68px footer brand lockup.
  * **Brand & Contrast:** Rainbow top ribbon paired with WCAG 2.2 AA-compliant V-A-C-T-E-R-L cards on warm ivory (`#FCFBF9`) surfaces.
  * **Built-in Easy Read Toggle:** Zero-JS CSS `:has()` toggle in the top utility bar that enlarges typography and simplifies clinical detail on demand.
  * **Complete Story & Ecosystem:** Includes the *"Then & Now"* young adult banner photos, the 20-year parent reflection quote, the **Appointment Trauma Card** self-advocacy tips, the *Adult OA/TOF Management Handbook* reference, VACTERL Visionaries, Max's Trust, TOFS, ERN eUROGEN, the Get-Together gallery, film cards, and **JustGiving** + **Membership** QR panels.
* **`home-v1-warm-welcome.html`** — Balanced charity homepage with prominent 84×84px logo lockup, hero + 3 CTAs, V-A-C-T-E-R-L cards, aims, parent quote, partners, and contact.
* **`home-v2-get-together.html`** — Event-led homepage with prominent logo lockup, Get-Together gallery, *"Then & Now"* young adult strip, film cards, and partner strip.
* **`home-v3-support-first.html`** — Plain-language, high-legibility Easy Read guide with prominent logo lockup, colour-coded plain-English letter list, 3 steps to help, hospital trauma tips, and contact card.

View locally:

```bash
podman run --rm -v "$PWD/docs:/usr/share/nginx/html:ro,z" -p 8080:80 nginx:alpine
# then open http://localhost:8080/mockups/home-v4-modern-flagship.html
```

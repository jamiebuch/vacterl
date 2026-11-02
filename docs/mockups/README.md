# Homepage mockups (v2 modernised)

Four static HTML drafts to compare direction. Open directly in a browser — no build step required. Images load from `../assets/`.

* **`home-v4-modern-flagship.html` (Recommended v2 Flagship)** — Combines the best of all three original concepts into one cohesive, modern charity homepage:
  * **Brand & Contrast Fix:** Keeps the rainbow umbrella identity via a top gradient ribbon and 7 letter cards, but replaces raw neon hexes with WCAG 2.2 AA-compliant paired accent bars and soft tinted badges on warm ivory (`#FCFBF9`) surfaces.
  * **Built-in Easy Read Toggle:** Includes Concept C's plain-language summary right in the hero plus a zero-JS CSS `:has()` toggle in the top utility bar that enlarges typography and simplifies clinical detail on demand.
  * **Mirrored Selfie Corrected:** Automatically flips `volunteers-2025-03-01.jpg` horizontally so the VACTERL umbrella polo logos and background banner read left-to-right.
  * **New Slideshow & Article Discoveries Integrated:** Features the *"Then & Now"* young adult banner photos (`image10`–`image12`), the 20-year parent reflection quote from the 2024 TOFS article, the **Appointment Trauma Card** self-advocacy tips, the ERN eUROGEN *Isolation → Empowerment → Advocacy* pathway, the 2025 Get-Together information station, and the **JustGiving** (`image27.png`) + **Membership** (`image26.png`) QR codes.
* **`home-v1-warm-welcome.html` (Concept A v2)** — Modernised balanced charity home. Hero + 3 CTAs, WCAG-compliant V-A-C-T-E-R-L letter cards, aims, parent quote, Get-Together, expanded partners, contact.
* **`home-v2-get-together.html` (Concept B v2)** — Modernised event-led layout. Top bar, 2025 information station + Bristol banner gallery, *"Then & Now"* young adult strip, film facade cards, partner strip.
* **`home-v3-support-first.html` (Concept C v2)** — Modernised plain-language, high-legibility layout. Max 780px, 19px hyperlegible sans, Easy Read summary box, colour-coded plain-English letter list, 3 steps to help, hospital/appointment trauma tips, and contact card.

View locally:

```bash
podman run --rm -v "$PWD/docs:/usr/share/nginx/html:ro,z" -p 8080:80 nginx:alpine
# then open http://localhost:8080/mockups/home-v4-modern-flagship.html
```

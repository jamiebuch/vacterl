# Homepage mockups

Three static drafts to compare direction. Open directly in a browser. No build step. Images load from `../assets/`.

* `home-v1-warm-welcome.html` — balanced charity home. Hero + 3 CTAs, V-A-C-T-E-R-L letter cards with panel colours, aims, Get-Together, partners, contact. Best if you want one all-rounder.
* `home-v2-get-together.html` — event-led. Top bar with next date, large photo strip (Bristol banner, information station, volunteers), film embeds, partner strip. Best if Get-Together is the main entry point.
* `home-v3-support-first.html` — plain-language, high-legibility. Max 760px, 18px Verdana, Easy Read box, 3 steps to help, one image. Best for accessibility / low bandwidth / distressed parents.

All use real copy from `../03-copy-draft.md`, real photos with consent warnings, and placeholder charity/donate/email values. Pick one as base, or mix: e.g. V1 structure + V3 Easy Read box + V2 gallery.

View locally:

```bash
podman run --rm -v "$PWD/docs:/usr/share/nginx/html:ro,z" -p 8080:80 nginx:alpine
# then open http://localhost:8080/mockups/home-v1-warm-welcome.html
```

# Media rights & video plan

## Rights checklist (do before publishing anything with people)

* [ ] Written consent for each identifiable child/adult in `source-material/` + `pptx-extracted/`. Parental consent for under-18s. Record who consented, when, for what use.
* [ ] TOFS 2024 article: permission from TOFS + author Kate Tyler to republish/summarise. Do not publish scan as-is (contains third-party layout + group photo).
* [ ] Slideshow group photos: assume no blanket consent — re-confirm.
* [ ] Videos: separate consent for filming + online publication + transcripts/quotes.
* [ ] Named clinicians (Gail Fitzpatrick, Aled Griffiths): permission to name/quote.
* [ ] Store consent forms offline, not in git. Keep a private register (filename → consent yes/no/pending).

Publishing rule: if consent is not `yes`, blur or omit. No surnames for children.

## Image handling

* Originals stay in `origdocs/` (gitignored) + private backup. Web copies only in `site/` after approval.
* `docs/assets/` currently holds reference copies for design, not final web assets.
* Convert to WebP/AVIF, max width 1600px, ≤200 KB each. Strip EXIF GPS. Mandatory alt text.
* Largest extracted files to triage first: `image3.jpg` (8.7 MB), `image17.jpeg` (6.2 MB), `image14.jpeg` (2.8 MB).

## Video handling (both MP4s >500 MB — must not enter git)

1. Archive originals privately (external drive). Do not commit.
2. Produce for each film:
   * 1080p + 720p H.264 MP4 + WebM, poster JPG (first meaningful frame), `.vtt` captions
   * Full transcript Markdown for `/stories` page
   * 30–60s teaser optional for Home
3. Host on YouTube (unlisted until consent confirmed) or PeerTube; embed with facade (`lite-youtube-embed`) to avoid heavy load.
4. Suggested tooling (open-source, via `podman` or local `ffmpeg`):
   ```bash
   podman run --rm -v "$PWD:/work:z" -w /work jrottenberg/ffmpeg:6.1-alpine \
     -i "origdocs/short film who we are.mp4" -map_metadata 0 \
     -c:v libx264 -crf 23 -preset slow -c:a aac -b:a 128k "preview-who-we-are-720p.mp4"
   ```
   Transcribe with `whisper.cpp` (GPL-3.0) locally, then human-correct.
5. Accessibility: captions, transcript, audio-description note if visual-only sequences, no autoplay with sound.

## Storage hygiene

* `origdocs/` stays gitignored. Never force-add MP4s.
* If Git LFS is considered, prefer not to use it — use external archive + hosted video instead.

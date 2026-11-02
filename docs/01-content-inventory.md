# Content inventory — VACTERL Association replacement site

Source folder: `origdocs/` (gitignored, see `.gitignore:429`). Curated copies in `docs/assets/source-material/`. Slideshow images extracted to `docs/assets/pptx-extracted/`.

Date inventoried: 2026-11-02. Slideshow: `vacterl slideshow.pptx`, 15 slides, 31.1 MB, 27 embedded images.

## 1. Slideshow (`vacterl slideshow.pptx`)

| Slide | Text extracted | Likely visuals (from `ppt/media/`) |
|---|---|---|
| 1 | `Vacterl / Association Support Group / Welcome!` | Title slide, logo |
| 2 | `What is Vacterl?` definition: at least three of vertebral defects, anal atresia, cardiac defects, tracheo-esophageal fistula, renal anomalies, limb abnormalities. `Why don't we know what causes it?` Solomon B.D 2011 quote on differential diagnosis / antenatal diagnosis. `How common is it?` 1 in 10,000 to 1 in 40,000 live-born infants | Text slide |
| 3 | `Each year we hold the Vacterl Get-Together.` | Event photos |
| 4 | `We've grown together over the years` | Timeline / group photos |
| 5 | `AND MADE AMAZING CONNECTIONS` | Community photos |
| 6 | `Together, we can support, educate and empower` | Community photos |
| 7 | (no extractable text — images only) | Speaker photos: `image18.jpeg` (Gail Fitzpatrick, CNS at Birmingham Children's Hospital, presenting on Normal Anatomy / ARM), `image19.jpeg` (Kate Tyler presenting the *Adult OA/TOF Management Handbook*) |
| 8 | `We collaborate with other agencies and charities, to raise awareness and contribute to research` | Partner flyer (`image20.png`: ERN eUROGEN *Patient Empowerment: A Journey From Isolation to Advocacy*) |
| 9 | `And make connections across the globe!` | International video call screen (`image21.png`) |
| 10 | `Contact us @` `https://www.facebook.com/groups/161861912196/` `https://www.instagram.com/vacterlassociation/tagged/` `info@vacterlsupportgroup.onmicrosoft.com` | Contact slide |
| 11 | `Vacterl Association Support Group / Membership Form / Thankyou!` | Form photo / QR |
| 12 | `With your support, We can achieve so much more!` `If you'd like to become a member or join the committee, please ask the table staff or contact us! info@vacterlsupportgroup.onmicrosoft.com` | CTA slide |
| 13 | `Thankyou!` | Closing |
| 14 | `Vacterl Association Support Group / DONATE HERE / Thankyou!` | Donate CTA + JustGiving QR (`image27.png`) |
| 15 | (no extractable text) | Likely final logo / QR |

> Note: `image2.jpg` in `pptx-extracted/` is byte-identical to `hi res vacterl logo.jpg`. `image20.png` is an ERN eUROGEN flyer (*"Patient Empowerment: A Journey From Isolation to Advocacy"*, co-adapted by VACTERL Association UK, TOFS, and Max's Trust). `image9.JPG`–`image12.JPG` are "then and now" photos of grown-up members (including Aled, Grace, and Rachel) pointing to their childhood photos on the banner, also showing Coloplast sponsorship and the `.org.uk` URL suffix.

## 2. Images in `origdocs/`

* `hi res vacterl logo.jpg` (0.7 MB) → copied to `docs/assets/source-material/logo-umbrella.jpg`. Rainbow umbrella, `V A C T E R L` on panels, `ASSOCIATION`, family pictograms, `Support Group`. Primary brand asset.
* `Bristol pop-up.jpg` (0.5 MB) → `bristol-popup-banner.jpg`. Pop-up banner text is the best existing definition + aims. Table also shows VACTERL Association leaflets, Max's Trust (ARM community) leaflets, and the framed logo polo shirts. Transcribed in `03-copy-draft.md`.
* `Information station.jpeg` (6.4 MB) → `information-station.jpg`. Info table from the **2025 Get-Together** (display board header reads *"Welcome to the Vacterl Association Support Group 2025 Get-Together"* with Slido `#1239 682` for anonymous panel questions, Changing Places toilet info, `# hello my name is...`, and ACE guide for parents/carers). Left board: ERN eUROGEN / ePAG, SOMA, EAT, ORCHID. Centre: Family Fund leaflets and framed polo shirts. Right board: TOFS, PINNT, IPSEA, Over The Wall Camp, Buttony Bear.
* `PHOTO-2025-03-01-12-05-19.jpg` (0.1 MB) → `volunteers-2025-03-01.jpg`. 3 volunteers in logo polos (note: selfie is horizontally mirrored — flip horizontally before web use so logo text reads left-to-right). Usable `About / Who we are` with consent.
* `TOFS article 2024.jpg` (2.1 MB) → `tofs-article-2024.jpg`. `VACTERL Association Support Group annual meeting by Kate Tyler, Trustee and ATWG Chair`. Key facts: 29 June meetup (with Alan French), charity registration applied recently (since Oct 2023 meeting), speakers Gail Fitzpatrick (Clinical Nurse Specialist, Birmingham Children's Hospital, ARM/stoma/bowel care) and Aled Griffiths (bowel care/continence + medical trauma presentation with Alan and partner Kodi, including the "trauma card" for appointments). Includes an Editor's note quoting a parent whose son was born 20 years ago. Needs transcription before use — do not publish scan as-is.

## 3. Video in `origdocs/` (not copied — too large for git)

* `short film who we are.mp4` — 512.7 MB
* `Vacterl Get together 2025 .mp4` — 570.5 MB

No transcripts yet. Plan: generate compressed preview + transcript, host on YouTube/Vimeo/PeerTube, embed. See `07-media-rights-video-plan.md`.

## 4. Extracted slideshow images

27 files in `docs/assets/pptx-extracted/` (total ~30 MB). Key breakdown across slides:
* `image1.jpg`: Wooden plank slide background texture (do not reuse on web).
* `image2.jpg`: Byte-identical to `hi res vacterl logo.jpg`.
* `image3.jpg` (8.7 MB): Stock photo of a person thinking against a yellow background from Slide 2 (`What is Vacterl?`) — omit from web build.
* `image4.jpg`, `image5.jpg`, `image6.png`, `image7.png`, `image8.jpg`: Multi-generational group photos from Get-Togethers (Slide 3).
* `image9.JPG`–`image12.JPG`: Young adults (including Aled, Grace, Rachel) pointing at their childhood photos on the VACTERL banner (Slide 4; bottom of banner in `image12.JPG` also shows `Coloplast` logo and `vacterl-association.org.uk` web address).
* `image13.JPG`: Speaker and committee group photo beside the VACTERL pop-up banner (Slide 5).
* `image14.jpeg`–`image17.jpeg`: Candid community connection photos from the Get-Together (Slide 5; note `image14`, `image16`, `image17` have 90° EXIF orientation and must be rotated upright if used).
* `image18.jpeg`: Clinical Nurse Specialist Gail Fitzpatrick presenting on Normal Anatomy / ARM (Slide 7).
* `image19.jpeg`: Kate Tyler presenting the *Adult OA/TOF Management Handbook* (Slide 7).
* `image20.png`: ERN eUROGEN flyer (*"Patient Empowerment: A Journey From Isolation to Advocacy"*) co-produced by VACTERL Association UK, TOFS, and Max's Trust (Slide 8).
* `image21.png`: International video call connecting VACTERL families across the globe (Slide 9).
* `image22.jpeg`: Stock `@` symbol photo from Slide 10 — omit from web build.
* `image23.jpeg`–`image25.jpeg`: Instagram, Facebook, Messenger icons (Slide 10).
* `image26.png`: Membership form QR code with star border (Slide 11).
* `image27.png`: JustGiving QR code + logo under the VACTERL umbrella (Slide 14).

Audit each photo for faces, consent, and duplicates before publishing. Compress all for web.

## 5. Recovered public directory & reference data (external lookup)

* **Historical Website & Contact (Contact.org.uk directory):**
  * Established: 2003 (over 20 years of peer support).
  * Historical domain: `vacterl-association.org.uk` (matches the `.org.uk` visible at the foot of the banner in `image12.JPG` and `image13.JPG`).
  * Historical email: `support@vacterl-association.org.uk` (current slides use `info@vacterlsupportgroup.onmicrosoft.com`).
* **Related UK Registered Charities & Adult Initiatives:**
  * **TOFS (Tracheo-Oesophageal Fistula Support):** Registered UK Charity No. `327735` (`tofs.org.uk`), whose charitable objects formally include the VACTERL/VATER Association; co-authors of the *Adult OA/TOF Management Handbook* shown in `image19.jpeg`.
  * **Max's Trust:** Registered UK Charity No. `1184081` (`maxtrust.org`), providing support and information for the UK Anorectal Malformation (ARM) and VACTERL community.
  * **VACTERL Visionaries:** Adult-led UK resource and advocacy network (`vacterlvisionaries.com` / `info.Vacterlvisionaries@gmail.com`) created by and for adults living with VACTERL.
* **Fundraising & Charity Registration Status:**
  * Donations are collected via **JustGiving** (`image27.png` QR code).
  * Formal charity registration application was submitted following the October 2023 meeting (per Kate Tyler's 2024 TOFS article).

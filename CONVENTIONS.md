# Conventions

Minimal diffs, maintainable over clever. Follow existing file style.

* Markdown: ATX headings, one blank line around lists/code, wrap at ~100 chars where readable, lowercase hyphenated slugs.
* Images: WebP/AVIF for web, ≤200 KB, alt text required, no EXIF GPS. Originals never in git (`origdocs/` is ignored).
* Stack: open-source packages only; suggest non-paid alternatives. Local builds with `podman`, not Docker.
* Versioning: bump `VERSION` on every change (SemVer: `0.x` pre-launch). Update `README.md` + this file if workflow changes.
* Commits: detailed message summarising changes. New branch/worktree only if asked (recommend if essential). Ask user before commit/push.
* Accessibility: WCAG 2.2 AA, keyboard navigable, captions/transcripts for video, 4.5:1 text contrast.
* Privacy: no children's surnames or medical details in repo; consent required before publishing faces.

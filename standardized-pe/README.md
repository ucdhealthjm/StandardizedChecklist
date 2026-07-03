# The Standardized Physical Examination — Rubric Builder

A free, self-contained web tool for a nationwide-adoptable physical-exam and OSCE
standard. It has two modes:

1. **Comprehensive PE** — the evidence-graded head-to-toe checklist (likelihood
   ratios, A–D yield tiers, ROS screens), for study and skills practice.
2. **OSCE / SOAP grading** — one SOAP-ordered station rubric scored from the
   student's note, with countable 0/1 (or 0/1/2) items, plus the three-rater model
   (SOAP note → content checklist, faculty → global rating, SP → communication).

Programs can add their own items on top of the fixed evidence base, check items
off, and export to **PDF** or **Word (.doc)**. Setup can be saved to a small file
and shared with `Export setup` / `Import setup`.

## What's here

- `index.html` — the entire tool. One file, no dependencies, no build step.

That's it. Everything (rendering, checkboxes, PDF/Word export, config save/load)
runs in the visitor's browser. There is **no server, no database, no tracking,
and no per-user cost.** A program's edits and checks live in that browser's local
storage only, so `Export setup` is how you move or share them.

## Publish it free on GitHub Pages

1. Create a **public** repository (e.g. `standardized-pe`).
2. Add `index.html` to the repository root (drag-and-drop in the web UI is fine).
3. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a
   branch*, Branch = `main`, Folder = `/ (root)`. Save.
4. Wait ~1 minute. Your URL is `https://<user-or-org>.github.io/standardized-pe/`.

Notes for a UC Davis Health / enterprise account:
- GitHub Pages must be enabled for the organization and the repo must be allowed
  to be public. If org policy blocks public Pages, publish from a personal
  `github.com` account instead — the tool is identical either way.
- A `<user>.github.io` repository publishes at the root domain
  `https://<user>.github.io/`.
- Optional custom domain (e.g. a `standardizedpe.org` you buy for ~$10/yr):
  Settings → Pages → Custom domain.

## Cite / archive it (optional, free)

Connect the repo to **Zenodo** (zenodo.org) to mint a versioned DOI, so the tool
and the companion handbook are citable in a paper and permanently archived.

## License

© 2026 Joshua A. Moen, PhD, MPH, PA-C. Released under
**Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)**:
https://creativecommons.org/licenses/by-nc/4.0/

You may share and adapt this for non-commercial educational use with attribution.

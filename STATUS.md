# My Website - STATUS

**Last reviewed:** 2026-06-26
**Live:** https://karimmd.github.io/
**Repo:** `git@github.com:karimmd/karimmd.github.io.git`
**Source:** `sidekicks/my-website/`

---

## Structure

```text
my-website/
├── index.html                <- Canonical portfolio landing page
├── publication.bib           <- Publication metadata source
├── paper-pages/              <- Dedicated paper microsites linked from the main page
│   ├── karim2025ai/
│   └── karim2026trust/
├── README.md
├── LICENSE.md
├── STATUS.md
├── .nojekyll
├── .github/
│   └── workflows/publish.yaml  <- GitHub Pages deploy from `main`
└── assets/
    ├── cv.pdf
    ├── karim.png
    └── siat-logo.png
```

---

## What has been done

### Initial cleanup (25 Jun 2026)
- Flattened the old `github-push/` contents into the repository root.
- Removed duplicate `standalone-portfolio/` copies.
- Fixed the GitHub Actions workflow so Pages deploys from the repo root.

### Profile update (25 Jun 2026)
- Changed the role label on the main page to `Assistant Professor`.
- Updated the experience timeline accordingly.
- Updated the footer year to June 2026.

### Publication corrections (25 Jun 2026)
- #4 now has the IEEE DOI and published page range.
- #7 now shows the published TDSC metadata.
- #8 now shows the published IOTJ metadata.
- #11, #12, and #13 now include their publisher DOI links.

### Paper pages and styling (26 Jun 2026)
- Added `paper-pages/karim2025ai/` for **AI Agents Meet Blockchain: A Survey on Secure and Scalable Collaboration for Multi-Agents**.
- Added `paper-pages/karim2026trust/` for **From Trust to Augmentation: A Comprehensive Survey on Synergistic Integration of Decentralized and Generative Intelligence**.
- Linked those pages from selected publication entries #7 and #2 on the main page.
- Changed the main-page paper-link accent color to `#9c1b34`.
- Reworked the Trust page so it uses the provided tables and affiliation logos from `paper-pages/karim2026trust/`.
- Kept the AI Agents page in the figure-based microsite style used for the reference layout.

### Citation landing page — karim2026trust (26 Jun 2026)
- Removed the PDF download button; only the "Full Text" (publisher DOI) button remains.
- Deleted the old multi-format "Cite Our Paper" section (Elsevier, APA, MLA, Chicago styles).
- Added new "Cite This Paper" section at the end (before logos) with IEEE, APA, BibTeX, and DOI only.
- Added "Research Keywords" section after the Brief Summary.
- Added Google Scholar citation meta tags to `<head>`.
- Created `static/bib/karim2026trust.bib` for downloadable citation.
- Action file at `action/01-website-citation-landing-page.md` documents the task (corrected per Karim's preferences).
- Footer now shows all 5 affiliations: SIAT, UCAS, BIT, Northumbria, City (innopolis/USTB removed).

### Karim2025ai page update (26 Jun 2026)
- Inserted as entry #7 on the main page (shifted entries 7–13 down to 8–14).
- Linked from main index with `[Page]` link to `paper-pages/karim2025ai/`.

---

## Current publication state

- 14 selected papers are listed on the main page.
- All 14 selected papers have DOI links.
- 2 selected papers have dedicated page links right now: #2 and #7.
- `publication.bib` is the source of truth for the paper metadata.
- The live site currently matches the local `index.html`.

---

## Deployment

- **Trigger:** push to `main`
- **Pipeline:** GitHub Actions -> GitHub Pages
- **Domain:** `karimmd.github.io`

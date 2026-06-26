# Agent Task 01: Improve the Paper Page as a Citation Landing Page

## Goal

Update the project page for `karim2026trust` so researchers can quickly understand, cite, and reuse the paper. The page should help convert visitors into readers and potential citers.

## Context

Paper page:
<https://karimmd.github.io/paper-pages/karim2026trust/>

Local project path:
`/home/user/Google-Drive/G-Projects/sidekicks/my-website/paper-pages/karim2026trust/`

Paper:
Md Monjurul Karim, Sangeen Khan, Qiang Qu, Muhammad Muzammal, Kashif Sharif, and Sujit Biswas, "From trust to augmentation: A comprehensive survey on synergistic integration of decentralized and generative intelligence," *Computer Science Review*, vol. 61, article 100936, 2026. DOI: <https://doi.org/10.1016/j.cosrev.2026.100936>.

## Karim's Corrections (apply these)

1. **Buttons:** Only the "Full Text" button should remain (linking to DOI/publisher). Remove the "Presentation" / "PDF" button — we are not sharing the paper PDF directly.
2. **No "Why Cite this Survey" section** — delete it entirely (Section 2 of original instructions is void).
3. **"Useful for Researchers Working On" → "Research Keywords"** — rename the heading.
4. **Citation box placement:** Move to the end of the page, just before the university logo section. It replaces the old "Cite Our Paper" section (remove all the style-specific formats like MDPI/ACS, AMA, Chicago, APA, BibTeX styles).
5. **No "PDF: Download" link** in the citation box.

## Required changes (corrected)

### 1. Remove PDF/Presentation button

Keep only the "Full Text" button linking to the publisher DOI. Remove the second button linking to `static/pdfs/karim2026trust.pdf`.

### 2. Add a "Research Keywords" section

Place after the Brief Summary. Use this heading and bullet list:

- Decentralized AI and Web3 intelligence
- Blockchain and LLM security
- AI agents in decentralized systems
- Trustworthy GenAI and provenance
- Edge intelligence and federated learning
- Privacy-preserving and interoperable AI middleware
- DeFi, dApps, DAOs, and intelligent blockchain governance

### 3. Add a "Cite This Paper" section at the end

Place just before the university logo section (replacing the old "Cite Our Paper" block with all the style formats). Include ONLY:

- IEEE citation
- APA citation
- BibTeX
- DOI link

Do NOT include: PDF download link, MDPI/ACS style, AMA style, Chicago style, MLA style.

Suggested BibTeX:

```bibtex
@article{karim2026trust,
  title={From trust to augmentation: A comprehensive survey on synergistic integration of decentralized and generative intelligence},
  author={Karim, Md Monjurul and Khan, Sangeen and Qu, Qiang and Muzammal, Muhammad and Sharif, Kashif and Biswas, Sujit},
  journal={Computer Science Review},
  volume={61},
  pages={100936},
  year={2026},
  doi={10.1016/j.cosrev.2026.100936},
  publisher={Elsevier}
}
```

### 4. Add academic metadata tags

Inside `<head>`, add citation-friendly metadata:

```html
<meta name="citation_title" content="From Trust to Augmentation: A Comprehensive Survey on Synergistic Integration of Decentralized and Generative Intelligence">
<meta name="citation_author" content="Karim, Md Monjurul">
<meta name="citation_author" content="Khan, Sangeen">
<meta name="citation_author" content="Qu, Qiang">
<meta name="citation_author" content="Muzammal, Muhammad">
<meta name="citation_author" content="Sharif, Kashif">
<meta name="citation_author" content="Biswas, Sujit">
<meta name="citation_journal_title" content="Computer Science Review">
<meta name="citation_volume" content="61">
<meta name="citation_firstpage" content="100936">
<meta name="citation_publication_date" content="2026/02/28">
<meta name="citation_doi" content="10.1016/j.cosrev.2026.100936">
<meta name="citation_pdf_url" content="https://karimmd.github.io/paper-pages/karim2026trust/static/pdfs/karim2026trust.pdf">
```

### 5. Add downloadable citation assets if feasible

Create or link:
- `static/bib/karim2026trust.bib`
- a one-slide summary if available later
- figure pack/table pack links if already present

Do not create fake assets. Only link files that exist.

## Verification

Before finishing:
1. Open or parse `index.html` and verify the new sections exist.
2. Check that only "Full Text" button remains (no PDF button).
3. Confirm "Research Keywords" section exists after Brief Summary.
4. Confirm "Cite This Paper" section exists before logos, and old multi-style "Cite Our Paper" section is removed.
5. Verify BibTeX is visible and copyable.
6. Verify the page still contains all 5 affiliation logos: SIAT/CAS, UCAS, BIT, Northumbria University, City St George's University of London.

## Deliverable

Return:
- Files modified
- Summary of changes
- Verification results

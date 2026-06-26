# Agent Task 06: Citation and Visibility Monitoring

## Goal

Create a lightweight monitoring process to track citation growth and visibility of the paper over time.

## Paper metadata

Title: From trust to augmentation: A comprehensive survey on synergistic integration of decentralized and generative intelligence

DOI: 10.1016/j.cosrev.2026.100936

Project page: <https://karimmd.github.io/paper-pages/karim2026trust/>

## Sources to monitor monthly

1. Google Scholar
2. Semantic Scholar
3. OpenAlex
4. Crossref
5. Scopus, if accessible
6. Web of Science, if accessible
7. ScienceDirect article metrics, if available
8. ResearchGate reads/recommendations, if available
9. Project page traffic, if GitHub Pages analytics or other analytics are configured
10. Altmetric/PlumX, if available from publisher page

## Monthly record format

Create or update a file named:

`citation-monitoring-log.md`

Use this structure:

```markdown
# Citation Monitoring Log: karim2026trust

## YYYY-MM-DD

| Source | Citation count | Reads/views/downloads | URL | Notes |
|---|---:|---:|---|---|
| Google Scholar |  |  |  |  |
| Semantic Scholar |  |  |  |  |
| OpenAlex |  |  |  |  |
| Crossref |  |  |  |  |
| Scopus |  |  |  |  |
| Web of Science |  |  |  |  |
| ScienceDirect |  |  |  |  |
| ResearchGate |  |  |  |  |
```

## What to record

- Date checked
- Source
- Citation count
- Reads/views/downloads if visible
- URL used
- Notes about metadata problems or new citing papers

## Citing-paper analysis

When new citations appear, collect:

| Citing paper | Year | Venue | Authors | Topic | Why it cited our paper | URL |
|---|---:|---|---|---|---|---|

This helps identify which communities are responding to the paper.

## Important rules

- Do not guess citation counts.
- If citation count differs across sources, record each value separately.
- If a source requires login and access is unavailable, write `Access unavailable`.
- Do not treat ResearchGate reads as citations.
- Do not overwrite previous monthly entries.

## Optional automation

If Karim wants automation later, create a scheduled monthly reminder rather than fully automated scraping. Some sources, especially Google Scholar, are not suitable for automated scraping.

## Deliverable

Return:

1. Initial monitoring log.
2. List of sources checked.
3. Missing/inaccessible sources.
4. Recommended monthly monitoring date.

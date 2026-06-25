# My Website — STATUS

**Live:** https://karimmd.github.io/
**Repo:** `git@github.com:karimmd/karimmd.github.io.git`
**Source:** `sidekicks/my-website/`

---

## Structure

```
my-website/
├── index.html       ← Single canonical portfolio page
├── README.md
├── LICENSE.md
├── STATUS.md
├── .nojekyll
├── .github/
│   └── workflows/publish.yaml   ← GitHub Actions deploy (path: .)
└── assets/
    ├── cv.pdf
    ├── karim.png
    └── siat-logo.png
```

---

## What's Been Done

### Initial Cleanup (25 Jun 2026)
- Flattened `github-push/` contents into root
- Deleted `standalone-portfolio/` (divergent copy)
- Deleted `github-push/standalone-portfolio/` (pure duplicate)
- Init git with SSH remote at `my-website/`
- Fixed GitHub Actions workflow: path changed from `./standalone-portfolio` → `.`

### Profile Update (25 Jun 2026)
- Role: `Postdoctoral Research Fellow` → `Assistant Professor`
- Experience: split postdoc end `May. 2026` + new role `Jun. 2026–present`
- Footer: `May 2026` → `June 2026`

### Publication Fixes (25 Jun 2026)
- **#4** Dynamic Client Selector — added DOI + pages from IEEE
- **#7** Evaluation to Integration — updated from early access to published `23(3):6362–6377`
- **#8** HySLA — updated from early access to published `13(9):18930–18944`
- **#11** DOLPHIN — added DOI from IEEE
- **#12** SDN Controllers — added DOI from ACM
- **#13** Network Virtualization — added DOI from ACM

---

## Publication List (13 papers, all with DOIs)

| # | Paper | DOI | Status |
|---|---|---|---|
| 1 | MTC-SBC (FGCS 2026) | 10.1016/j.future.2026.108499 | ✅ |
| 2 | Trust to Augmentation (CSR 2026) | 10.1016/j.cosrev.2026.100936 | ✅ |
| 3 | Securing DeFi (BCRA 2026) | 10.1016/j.bcra.2026.100455 | ✅ |
| 4 | Dynamic Client Selector (PerCom 2026) | 10.1109/PERCOM67906.2026.11524502 | ✅ |
| 5 | Just-in-Time (AI 2026) | 10.3390/ai7040117 | ✅ |
| 6 | Probabilistic Optimization (WAIM 2026) | 10.1007/978-981-95-5716-5_35 | ✅ |
| 7 | Evaluation to Integration (TDSC 2026) | 10.1109/TDSC.2026.3664110 | ✅ |
| 8 | HySLA (IoT-J 2026) | 10.1109/JIOT.2026.3662189 | ✅ |
| 9 | Bitcoin Reimagined (BCRA 2025) | 10.1016/j.bcra.2025.100379 | ✅ |
| 10 | CIC-SIoT (IoT-J 2024) | 10.1109/JIOT.2024.3441814 | ✅ |
| 11 | DOLPHIN (TNSM 2021) | 10.1109/TNSM.2020.3045725 | ✅ |
| 12 | SDN Controllers (CSUR 2020) | 10.1145/3421764 | ✅ |
| 13 | Network Virtualization (CSUR 2020) | 10.1145/3379444 | ✅ |

---

## Deployment

- **Trigger:** Push to `main` branch
- **Pipeline:** GitHub Actions → upload artifact → deploy-pages
- **Domain:** karimmd.github.io

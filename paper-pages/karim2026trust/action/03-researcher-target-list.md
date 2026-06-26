# Agent Task 03: Build a Target Researcher and Paper List

## Goal

Collect a carefully verified list of researchers and recent papers that are topically aligned with the survey. This list will support manual academic outreach and community visibility.

The goal is not spam. The goal is to identify researchers who are already working on closely related topics and may find the survey useful as a taxonomy or background reference.

## Core paper

Md Monjurul Karim, Sangeen Khan, Qiang Qu, Muhammad Muzammal, Kashif Sharif, and Sujit Biswas, "From trust to augmentation: A comprehensive survey on synergistic integration of decentralized and generative intelligence," *Computer Science Review*, vol. 61, article 100936, 2026. DOI: <https://doi.org/10.1016/j.cosrev.2026.100936>.

## Target research themes

Search recent papers and researchers in these themes:

1. Decentralized AI / DeAI
2. Blockchain and LLMs
3. Blockchain for GenAI trust, provenance, and auditability
4. Web3 intelligence and AI agents
5. DePIN and decentralized intelligent infrastructures
6. Federated learning with blockchain or Web3
7. Privacy-preserving decentralized AI
8. AI agents for dApps, DeFi, DAOs, or Ethereum ecosystems
9. Trustworthy GenAI in distributed systems
10. Edge intelligence combined with blockchain/Web3

## Recommended search queries

Use Google Scholar, Semantic Scholar, OpenAlex, DBLP, arXiv, ACM DL, IEEE Xplore, ScienceDirect, and SpringerLink where possible.

Suggested queries:

- "decentralized AI" blockchain LLM survey 2025 2026
- "Web3" "large language models" blockchain 2025 2026
- "blockchain" "generative AI" trust survey
- "AI agents" Web3 blockchain decentralized applications
- "DeAI" "GenAI" blockchain
- "decentralized intelligence" "large language models"
- "blockchain for LLM security" 2025 2026
- "trustworthy generative AI" blockchain provenance
- "DePIN" AI agents blockchain
- "federated learning" blockchain Web3 LLM

## Data to collect

For each target paper/researcher, collect title, affiliation, email when publicly available, name, and evidence source.

For each target paper/researcher, collect:

| Field | Required? | Notes |
|---|---:|---|
| Paper title | Yes | Exact title from source |
| Year | Yes | Prefer 2025 or 2026, but include important 2024 papers if highly relevant |
| Venue/source | Yes | Journal, conference, arXiv, etc. |
| URL/DOI | Yes | DOI, arXiv, publisher, or Semantic Scholar URL |
| Authors | Yes | At least corresponding/first author if full list is long |
| Researcher name | Yes | Person to contact or track |
| Affiliation | Yes if available | Use current affiliation from paper or profile |
| Email | Optional | Only public professional email; otherwise write `Not found` |
| Topic match | Yes | One sentence explaining why the paper/researcher is relevant |
| Outreach priority | Yes | High/Medium/Low |
| Evidence source | Yes | URL where the data was found |

## Prioritization criteria

High priority:

- The recent paper explicitly discusses at least two of these: blockchain, Web3, DeAI, GenAI, LLMs, AI agents.
- The author writes survey/position/system papers where a taxonomy paper is naturally citable.
- The paper cites related surveys but not this one.

Medium priority:

- The paper is close but focuses on one subarea, such as blockchain + LLM security or edge AI + blockchain.

Low priority:

- The connection is broad or indirect.

## Email collection rules

- Use only public professional emails from institutional pages, paper PDFs, ORCID, DBLP-linked homepages, or lab pages.
- Do not use private emails from leaks or non-professional sources.
- If email is unavailable, write `Not found` and keep the researcher in the list.
- Do not send any emails.

## Output file

Create a CSV or Markdown table named:

`researcher-target-list.md` or `researcher-target-list.csv`

Suggested table columns:

| Priority | Researcher | Affiliation | Email | Paper title | Year | Venue | URL/DOI | Topic match | Evidence source | Notes |

## Deliverable

Return:

1. The completed target list.
2. Search queries used.
3. Sources checked.
4. Any limitations, such as inaccessible databases or missing emails.

# Available .FAMILY One-Word Domains (13,837)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-13%2C837%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .family one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **13,837 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 13,837 domains · **Median ask:** $57.28 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-13
**Canonical page:** `https://unique.domains/domains/tld/family`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/family?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./family.csv">CSV</a> / <a href="./family.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FAMILY search](https://unique.domains/domains/tld/family?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FAMILY search](https://unique.domains/domains/tld/family?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FAMILY one-word domain catalog.

### Files

- `family.csv`, public CSV extract (1,000 rows)
- `family.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/family-oneword-domains/main/family.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| bid.family    | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| cool.family   | resell    | —         | —             | high           | low    | 4      | Dynadot Inc                                               |
| aaa.family    | premium   | $128.70   | $128.70       | high           | medium | 3      | namecheap                                                 |
| con.family    | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| cute.family   | resell    | —         | —             | high           | low    | 4      | NameCheap, Inc.                                           |
| act.family    | premium   | $500      | —             | high           | low    | 3      | name.com                                                  |
| did.family    | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| pray.family   | resell    | —         | —             | medium         | low    | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| are.family    | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                                                  |
| far.family    | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| lucky.family  | resell    | —         | —             | high           | medium | 5      | Sav.com, LLC                                              |
| ask.family    | premium   | $242      | $242          | high           | medium | 3      | namesilo                                                  |
| few.family    | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| energy.family | resell    | —         | —             | high           | medium | 6      | Squarespace Domains II LLC                                |
| dot.family    | premium   | $3,125    | —             | high           | medium | 3      | name.com                                                  |
| hic.family    | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| him.family    | premium   | $500      | —             | high           | low    | 3      | name.com                                                  |
| jot.family    | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| lot.family    | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo                                                  |
| put.family    | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 13,837 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/family?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/family?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection includes 11,700 one-word .family domain names, ranging from short compound terms like coffeeberry.family and backyard.family to phrase-style names like getmarried.family. The median asking price sits near $72, keeping many of these domains accessible for personal projects, community sites, and family-focused brands. Names vary in length and tone, from playful options like JollyRoger.family to functional ones like primarycare.family, giving buyers a wide range of choices at different price points.

- 11,700 one-word .family domain names in this selection
- Median asking price near $72 across the set
- Names range from short compounds to full phrases
- Spans personal, community, and family-focused themes

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FAMILY One-Word Domains*. Version 2026-08-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FAMILY page](https://unique.domains/domains/tld/family?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_family_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

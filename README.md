# Available .LAND One-Word Domains (11,018)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C018%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .land one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,018 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,018 domains · **Median ask:** $25.01 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/land`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/land?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./land.csv">CSV</a> / <a href="./land.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LAND search](https://unique.domains/domains/tld/land?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LAND search](https://unique.domains/domains/tld/land?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LAND one-word domain catalog.

### Files

- `land.csv` — public CSV extract (1,000 rows)
- `land.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/land-oneword-domains/main/land.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| forms.land       | available | $19.99    | —             | 54             | 28     | 5      | name.com         |
| business.land    | resell    | —         | —             | 90             | 52     | 8      | Porkbun LLC      |
| etc.land         | premium   | $500      | —             | 58             | 34     | 3      | name.com         |
| backyard.land    | available | $19.99    | —             | 80             | 27     | 9      | name.com         |
| root.land        | resell    | —         | —             | 64             | 50     | 4      | Dynadot Inc      |
| partners.land    | premium   | $123.75   | —             | 61             | 32     | 8      | name.com         |
| KFC.land         | available | $54.98    | —             | 74             | 27     | 3      | namecheap        |
| baby.land        | resell    | —         | —             | 78             | 31     | 4      | Porkbun LLC      |
| apartments.land  | premium   | $118.80   | $118.80       | 60             | 21     | 10     | namesilo         |
| trades.land      | available | $19.99    | —             | 71             | 26     | 6      | name.com         |
| marine.land      | resell    | —         | —             | 74             | 30     | 6      | Porkbun LLC      |
| hills.land       | premium   | $123.75   | —             | 65             | 20     | 5      | name.com         |
| claire.land      | available | $19.99    | —             | 68             | 26     | 6      | name.com         |
| pestcontrol.land | resell    | —         | —             | 74             | 18     | 12     | GoDaddy.com, LLC |
| vacations.land   | premium   | $118.80   | $118.80       | 56             | 19     | 9      | namesilo         |
| doctors.land     | available | $19.99    | —             | 56             | 26     | 7      | name.com         |
| rocks.land       | premium   | $250      | —             | 78             | 18     | 5      | name.com         |
| chem.land        | available | $19.99    | —             | 74             | 24     | 4      | name.com         |
| pictures.land    | premium   | $500      | —             | 82             | 17     | 8      | name.com         |
| boats.land       | available | $19.99    | —             | 52             | 24     | 5      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,018 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/land?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/land?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

These domains are one-word names on the .land extension. The set includes broad nouns, verbs, adjectives, and abstract terms, with examples such as cat.land, computer.land, etch.land, careful.land, and equal.land. For founders, the best picks are usually the names that are easy to say, easy to spell, and specific enough to feel memorable without being limiting. For investors, quality depends less on volume here and more on whether a word is clean, commercially usable, and priced rationally against likely resale demand. Watch for clear trademark issues in names tied to established brands, such as YouTube.land, and compare each name against renewal fit before deciding.

- Favor clear dictionary words with strong recall
- Check trademark exposure before treating a name as usable
- Compare ask price against likely renewal commitment
- Broad words can help, but vague words weaken memorability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LAND One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LAND page](https://unique.domains/domains/tld/land?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

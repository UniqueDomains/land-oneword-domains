# Available .LAND One-Word Domains (11,027)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C027%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .land one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,027 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,027 domains · **Median ask:** $26.14 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `land.csv`, public CSV extract (1,000 rows)
- `land.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/land-oneword-domains/main/land.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| BJP.land        | available | $19.99    | —             | medium         | low    | 3      | name.com                                                  |
| domainname.land | resell    | $19.99    | —             | high           | low    | 11     | GoDaddy.com, LLC                                          |
| aid.land        | premium   | $242      | $242          | medium         | low    | 3      | namesilo                                                  |
| CNN.land        | available | $19.99    | —             | high           | low    | 3      | name.com                                                  |
| get.land        | resell    | —         | —             | high           | medium | 3      | Spaceship, Inc.                                           |
| ala.land        | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                                                  |
| hic.land        | available | $19.99    | —             | high           | low    | 3      | name.com                                                  |
| pin.land        | resell    | —         | —             | high           | low    | 3      | Key-Systems, LLC                                          |
| axe.land        | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo                                                  |
| kgb.land        | available | $19.99    | —             | high           | low    | 3      | name.com                                                  |
| film.land       | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.                                           |
| btw.land        | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                                                  |
| TBD.land        | available | $19.99    | —             | high           | low    | 3      | name.com                                                  |
| geek.land       | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.                                           |
| dew.land        | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo                                                  |
| xix.land        | available | $19.99    | $52.99        | high           | low    | 3      | name.com                                                  |
| logo.land       | resell    | —         | —             | high           | low    | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| feb.land        | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo                                                  |
| xxi.land        | available | $19.99    | $52.99        | medium         | low    | 3      | name.com                                                  |
| port.land       | resell    | —         | —             | medium         | low    | 4      | Dynadot Inc                                               |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,027 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/land?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/land?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=related_pricing)

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

This list of 11,027 .land domains spans short, brandable names like tech.land, tips.land, and getup.land alongside descriptive picks such as herbaltea.land and coffeewoman.land. With a $26 median ask, .land offers an accessible entry point for founders building in real estate, agriculture, travel, and outdoor niches, and for investors scanning a wide, low-cost TLD for margin potential. Because .land is a newer TLD, most names remain unregistered and available, giving early buyers first pick of clean, memorable options.

- 11,027 .land domains tracked, updated daily
- $26 median ask — low-cost entry across .land
- Short, brandable names like tech.land, tips.land
- Descriptive picks for real estate, travel & outdoor

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LAND One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LAND page](https://unique.domains/domains/tld/land?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_land_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

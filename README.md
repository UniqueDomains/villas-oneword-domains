# Available .VILLAS One-Word Domains (20,879)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-20%2C879%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .villas one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **20,879 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 20,879 domains · **Median ask:** $27.97 · **High-demand under $2,500:** 2

**Last updated:** 2026-09-06
**Canonical page:** `https://unique.domains/domains/tld/villas`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/villas?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./villas.csv">CSV</a> / <a href="./villas.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VILLAS search](https://unique.domains/domains/tld/villas?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VILLAS search](https://unique.domains/domains/tld/villas?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VILLAS one-word domain catalog.

### Files

- `villas.csv`, public CSV extract (1,000 rows)
- `villas.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/villas-oneword-domains/main/villas.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| out.villas      | available | $19.99    | —             | high           | low    | 3      | name.com         |
| ana.villas      | available | $19.99    | —             | high           | low    | 3      | name.com         |
| american.villas | resell    | —         | —             | high           | low    | 8      | GoDaddy.com, LLC |
| fun.villas      | premium   | $242      | $242          | high           | medium | 3      | namesilo         |
| arc.villas      | available | $19.99    | $80.99        | medium         | medium | 3      | name.com         |
| red.villas      | premium   | $242      | $242          | high           | medium | 3      | namesilo         |
| bug.villas      | available | $19.99    | —             | high           | low    | 3      | name.com         |
| bank.villas     | premium   | $242      | $242          | high           | low    | 4      | namesilo         |
| cut.villas      | available | $19.99    | $80.99        | high           | low    | 3      | name.com         |
| post.villas     | premium   | $500      | —             | high           | medium | 4      | name.com         |
| die.villas      | available | $19.99    | —             | medium         | low    | 3      | name.com         |
| spot.villas     | premium   | $242      | $242          | high           | medium | 4      | namesilo         |
| dry.villas      | available | $19.99    | $80.99        | high           | low    | 3      | name.com         |
| star.villas     | premium   | $500      | $500          | high           | medium | 4      | name.com         |
| fat.villas      | available | $19.99    | —             | medium         | low    | 3      | name.com         |
| tour.villas     | premium   | $520      | $520          | high           | low    | 4      | namecheap        |
| gag.villas      | available | $19.99    | —             | high           | low    | 3      | name.com         |
| town.villas     | premium   | $118.80   | $118.80       | medium         | low    | 4      | namesilo         |
| gee.villas      | available | $19.99    | —             | medium         | low    | 3      | name.com         |
| tree.villas     | premium   | $500      | —             | high           | low    | 4      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 20,879 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/villas?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/villas?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=related_pricing)

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

This list covers 12,781 one-word domain names registered under the .villas extension, with a median asking price near $31. Names range widely in theme — from tech-flavored words like hightech.villas to lifestyle terms like honeymooning.villas — rather than being limited to literal property or vacation use. The short, one-word format keeps these names easy to read, say, and remember, while the low median price makes the category accessible for quick evaluation and comparison.

- 12,781 one-word .villas domains in this selection
- Median ask near $31 — a low-cost entry point
- Themes range from tech to lifestyle to everyday words
- Short, one-word format for easy recall and branding

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VILLAS One-Word Domains*. Version 2026-09-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VILLAS page](https://unique.domains/domains/tld/villas?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_villas_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

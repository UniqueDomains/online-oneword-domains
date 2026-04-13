# Available .ONLINE One-Word Domains (67,132)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-67%2C132%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .online one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **67,132 domains** on the canonical page below.

**Public extract:** 10,000 rows · **Live catalog:** 67,132 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/online`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/online?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./online.csv">CSV</a> / <a href="./online.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ONLINE search](https://unique.domains/domains/tld/online?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ONLINE search](https://unique.domains/domains/tld/online?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ONLINE one-word domain catalog.

### Files

- `online.csv` — public CSV extract (10,000 rows)
- `online.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/online-oneword-domains/main/online.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain                 | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| ---------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| froth.online           | available | $2.99     | $46.99        | 84             | 88     | 5      | name.com                                            |
| stonework.online       | resell    | $1,092.50 | $46.99        | 56             | 80     | 9      | CHENGDU WEST DIMENSION DIGITAL TECHNOLOGY CO., LTD. |
| faded.online           | premium   | $676.20   | $41.99        | 64             | 97     | 5      | Sav.com, LLC - 26                                   |
| zyzzyva.online         | available | $2.99     | $41.99        | 58             | 76     | 7      | name.com                                            |
| cloud.online           | resell    | $718,750  | $46.99        | 70             | 59     | 5      | NAME DOT STORE INC                                  |
| mortgage.online        | premium   | $7,812.50 | $31,250       | 80             | 96     | 8      | name.com                                            |
| voiceoverIP.online     | available | $28.98    | —             | —              | 76     | 13     | namecheap                                           |
| tough.online           | resell    | $3,795    | $46.99        | 122            | 14     | 5      | Xin Net Technology Corporation                      |
| couture.online         | premium   | $312.50   | $1,250        | 71             | 96     | 7      | name.com                                            |
| ABCsoil.online         | available | $27.98    | —             | 56             | 72     | 8      | namecheap                                           |
| corrupt.online         | resell    | $1,725    | $46.99        | 80             | 14     | 7      | Dynadot Inc                                         |
| transmission.online    | premium   | $312.50   | $1,250        | —              | 96     | 12     | name.com                                            |
| accountday.online      | available | $2.99     | $41.99        | 56             | 72     | 11     | name.com                                            |
| convenient.online      | resell    | $3,795    | $46.99        | 78             | 10     | 10     | Xin Net Technology Corporation                      |
| aah.online             | premium   | $781.25   | $3,125        | 114            | 92     | 3      | name.com                                            |
| animalhusbandry.online | available | $2.99     | $46.99        | 54             | 72     | 16     | name.com                                            |
| activated.online       | resell    | $3,795    | $46.99        | 74             | 10     | 9      | Xiamen ChinaSource Internet Service Co., Ltd        |
| events.online          | premium   | $3,125    | $12,500       | 68             | 92     | 6      | name.com                                            |
| depositaccount.online  | available | $2.99     | $46.99        | 46             | 72     | 15     | name.com                                            |
| dedicate.online        | resell    | $1,092.50 | $46.99        | 106            | 8      | 8      | UM DOMAINS PTE. LTD.                                |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 67,132 live domains                              |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/online?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/online?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ONLINE One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ONLINE page](https://unique.domains/domains/tld/online?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_online_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

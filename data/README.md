# Data

Place these two files in this folder before running the notebook.

| File | Source | Contents |
|---|---|---|
| `GII.csv` | [Global Innovation Index](https://www.wipo.int/global_innovation_index/en/), World Intellectual Property Organization (WIPO) | Country (ISO alpha-3 code), year, GII rank and score, 2011 to 2021 |
| `global_economy_indicators.csv` | [UN National Accounts Main Aggregates Database](https://unstats.un.org/unsd/snaama/) | Annual national accounts by country: per capita GNI, exchange rates, population, exports, imports, consumption, capital formation and sector output |

In `GII.csv`, a rank of -1 marks a country with no ranking that year. The notebook removes these rows.

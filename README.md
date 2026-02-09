# Crypto Market Analysis (CoinGecko + Blockstream + OpenAI)

Group project from **DSCB230 – Informatik für Data Science 2 (SS 2025)**.

The project analyzes crypto market metrics (price, volume, volatility, market cap) and explores Bitcoin on-chain data (transaction fees vs. transaction size).  
Additionally, it contains an experimental notebook that links large price moves to real-world events using an LLM.

>  This repository is for educational purposes only and **does not provide investment advice**.

---

## Project Highlights

- **Market data analysis** using CoinGecko (historical prices, volume, market cap)
- **Volatility and volume patterns** by weekday and time-of-day (Bitcoin)
- **Market capitalization comparisons** for major cryptocurrencies
- **Blockchain analysis** (Bitcoin): transaction fee vs. transaction size using Blockstream API
- **Trend / news exploration**: detect biggest price moves and retrieve relevant events (OpenAI-powered, experimental)

---

## Notebooks

| Notebook | Topic |
|---------|------|
| `notebooks/Frage_I_Datenanalyse.ipynb` | Bitcoin price changes, weekly volatility, yearly volume, weekday/hour heatmaps |
| `notebooks/Frage_II_Blockchain_Analyse.ipynb` | Bitcoin on-chain: transaction size vs. fees (Blockstream) |
| `notebooks/Frage_III_Marktkapitalisierung.ipynb` | Market cap analysis: top coins, dominance, growth rates |
| `notebooks/Frage_IV_Trends_Analyse.ipynb` | Biggest price moves + event context via LLM (experimental) |
| `notebooks/DSCB230_SoSe25_Hausarbeit_Gruppenname.ipynb` | Written report / summary of the whole project |

---

## APIs

- CoinGecko API (market charts: prices, volume, market cap)
- Blockstream Explorer API (Bitcoin blocks + transactions)
- OpenAI API ( used only in the trends notebook)

---

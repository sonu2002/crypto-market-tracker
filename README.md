# 📈 Crypto Market Tracker (React)

A React dashboard that shows the **top 10 cryptocurrencies by market cap** using live data from the **CoinGecko API**, with instant search and sorting.

🔗 **Live demo:** https://sonu2002.github.io/crypto-market-tracker/

## ✨ Features
- Live prices, market cap, volume and 24h % change from the CoinGecko REST API
- 🔍 Search by **coin name or symbol**
- ↕️ Sort by **market cap** or **24h percentage change**
- 🟢🔴 Colour-coded gains and losses
- Friendly empty-state message when nothing matches the search

## 🛠️ Tech stack
`React` · `Vite` · `styled-components` · `Sass` · `Fetch API` · `GitHub Pages`

## 🗂️ Project structure
```
src/
├── components/   Header (search + sort), Main, Table, TableData, Message
└── services/     api.js (endpoint), fetchData.js, filterData.js (search & sort logic)
```
API, data fetching and filtering live in `services/`, separate from the UI components.

## 🚀 Run locally
```bash
npm install
npm run dev
```

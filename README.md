# 📈 Stock Journal

A personal stock trade journal built as a single self-contained HTML file — no server, no login, no dependencies. Runs directly in your browser and saves everything locally on your device.

Live at: **[curlysglitchin.github.io/Stock-Journal](https://curlysglitchin.github.io/Stock-Journal/)**

-----

## What It Does

Stock Journal helps you track not just *what* you own, but *why* you own it. It’s easy to forget your original thesis on a position — especially during volatility. This app keeps your reasoning front and center so you can make smarter decisions about when to hold, add, or exit.

-----

## Features

### 📋 Trade Journal

- Log every position with a full **trade thesis** — your reasoning for entering
- Add **exit conditions** — what would invalidate the trade or signal it’s time to sell
- Track entry price, shares, account, and entry date
- Set **take profit**, **stop loss**, and **target exit date**
- Choose a **hold duration** (Daytrade → Forever/Dividend)
- Log **catalysts and catalyst dates** (earnings, PDUFA events, splits, etc.)
- Add **conviction level**, **risk rating**, and **custom tags**

### 📡 Live Price Refresh

- Hit **↻ Prices** to fetch real-time quotes for all open positions at once
- Powered by Yahoo Finance — no API key required
- Prices flash gold on update so you can see what changed
- Timestamp shows when prices were last refreshed

### 🔔 Smart Alerts Tab

Automatically surfaces:

- Upcoming catalyst dates within the next 30 days
- Positions within 8% of your take profit target
- Positions within 8% of your stop loss
- Positions that have passed their target hold date

### 👀 Watchlist

Track tickers you’re watching without logging a full position yet.

### ✅ Closed Trades

Archive closed positions with exit price and realized P&L.

### 💾 Import / Export

- Export to **JSON** for a full backup
- Export to **CSV** to open in Excel or Google Sheets
- Import JSON to restore or merge a backup

-----

## How to Use

1. Download `StockJournal.html`
1. Open it in any browser (works in Chrome, Safari, Brave, Firefox, and on iPhone & Android)
1. Add your trades with **+ New Trade**
1. Hit **↻ Prices** to refresh live quotes anytime

All data is saved automatically to your browser’s local storage — nothing is sent to any server.

> **Tip:** Use the **Export JSON** button regularly to back up your data. Local storage can be cleared if you clear your browser history.

-----

## Tech Stack

- Vanilla HTML, CSS, and JavaScript — zero frameworks, zero build tools
- Local Storage for persistence
- Yahoo Finance (via CORS proxy) for live price data
- Google Fonts: Syne, DM Mono, Instrument Serif
- Hosted on GitHub Pages

-----

## Screenshots

*Coming soon*

-----

## Notes on Live Prices

Prices are fetched via a public CORS proxy pointing to Yahoo Finance. Data may reflect a 15–20 minute delay during market hours, which is standard for free data sources. Live price fetching requires an internet connection.

-----

*Built for personal use. Not financial advice.*

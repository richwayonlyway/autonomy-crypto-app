# Autonomy — Crypto Super-App

> Multi-chain crypto super-app combining perpetuals trading, DEX swaps, NFT vault, real-time market data, and token launchpad — all in a single dark, premium interface.

**Live Demo:** [Launch App](https://www.perplexity.ai/computer/a/autonomy-crypto-super-app-67pf_OvKQ46LGdFsiVSW3w)

---

## Features

### 📊 Portfolio Dashboard
- Live P&L tracking with sparklines
- Asset allocation donut chart
- Top movers and performance metrics
- Real-time prices via CoinGecko API (no API key required)

### 📈 Markets
- Full market overview with 24h stats
- Trending coins section
- Watchlist management
- Fear & Greed index

### ⚡ Trade
- **Perpetuals** — long/short with leverage, isolated/cross margin
- **Swap** — token swap with quote → confirm → pending → success flow
- Fee structure: 0.30% swap fee, 0.05% maker / 0.08% taker perp fees
- Revenue dashboard showing fee accumulation

### 🖼️ NFT Vault
- Portfolio view of NFT holdings
- Floor price tracking
- Collection stats

### 📰 News Feed
- Curated crypto news
- Sentiment indicators
- Source filtering

### 🚀 Launchpad
- Token launch discovery
- IDO participation
- Vesting schedule viewer

### 👛 Wallet
- Multi-chain balance view
- Transaction history
- Send/Receive flow

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React 18, TypeScript, Vite |
| Styling | Tailwind CSS, shadcn/ui |
| State | TanStack Query v5 |
| Charts | Recharts |
| Backend | Express.js, Node.js |
| Prices | CoinGecko API (free tier) |

---

## Getting Started

```bash
# Install dependencies
npm install

# Start development server (frontend + backend)
npm run dev

# Build for production
npm run build
```

The app runs on `http://localhost:5000` by default.

---

## Project Structure

```
├── client/              # React frontend
│   ├── src/
│   │   ├── components/  # UI components
│   │   ├── pages/       # Route pages
│   │   ├── lib/         # Utilities & services
│   │   └── hooks/       # Custom hooks
├── server/              # Express backend
│   ├── routes.ts        # API routes
│   └── index.ts         # Server entry
├── autonomy-landing/    # Static landing page
└── shared/              # Shared types
```

---

## Revenue Model

- **Swap Fee:** 0.30% per trade
- **Perp Maker Fee:** 0.05% per trade  
- **Perp Taker Fee:** 0.08% per trade
- **NFT Marketplace:** 2.5% royalty

---

## License

MIT

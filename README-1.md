# 🦅 pharosng_defi

> Pharos in Nigeria. DeFi for 220 million people. One file. No wallet.

A Nigeria-focused Pharos Network dashboard — live blockchain intelligence, 6 wallet-free developer tools, and a complete breakdown of why Pharos is the right infrastructure for Nigerian DeFi. Built for builders, researchers, and anyone who wants to understand how Pharos connects to Nigeria's financial reality.

---

## 🇳🇬 The Nigeria Thesis

Nigeria is Africa's largest economy with 220M people. 60% are unbanked or underbanked. Remittances cost 8–12% via legacy rails. The Naira lost 70%+ of its value over two years. And yet Nigerians are the **third-largest crypto users per capita on the planet** — they already understand the value.

Pharos provides the infrastructure:

- **USDC on CCTP domain 31** — remittances in seconds for cents, not 10%
- **x402 payment rails** — SME settlement, freelancer pay, subscription commerce
- **RWA tokenization** — fractional Lekki real estate from ₦50K, not ₦50M
- **SPNs with TEE** — USSD-to-chain bridges for feature phone users in Kano, Katsina, and beyond
- **50K TPS + subsecond finality** — fast enough for point-of-sale, payroll, and high-volume corridors

---

## ✨ Features

### 🔴 Live Network Monitor
- Auto-probes Pharos Mainnet and Atlantic Testnet every 20 seconds
- Real-time terminal feed with timestamped RPC logs
- Instant status indicator — **● live** or **● degraded**
- Rolling gas price sparkline (last 20 reads)

### 🛠️ 6 Wallet-Free Developer Tools

| Tool | Description |
|------|-------------|
| **Address Inspector** | Balance, nonce — mainnet or testnet |
| **Transaction Lookup** | Decode any tx hash — status, gas, from/to, value |
| **USDC / NGN / ETH Converter** | Live Naira ↔ USDC ↔ Wei conversion with live rate fetch |
| **PROS Staking Calculator** | Model yield at 5% APY across any lock period |
| **Gas History Sparkline** | Rolling chart from the last 20 RPC reads |
| **Latest Blocks** | Last 5 mainnet blocks — txs, gas, timestamp |
| **RPC Latency Tester** | Ping both endpoints from your browser |

### 🇳🇬 Nigeria-Specific Content
- **Why Nigeria Needs Pharos** — full breakdown with market data
- **6 Nigeria use cases** — remittances, dollar savings, SME settlement, RWA, freelancer pay, USSD bridge
- **USDC / NGN converter** with live exchange rate fetch
- CCTP Domain Registry — Pharos domain 31 highlighted
- Full ecosystem briefing — tech stack, $PROS, investors, links

---

## 📡 RPC Endpoints Used

| Network | Endpoint |
|---------|----------|
| Mainnet | `https://rpc.pharos.xyz` |
| Testnet | `https://atlantic.dplabs-internal.com` |

All calls are made directly from your browser to Pharos public RPC. No proxy. No backend.

---

## 🗂️ Repo Structure

```
pharosng_defi/
├── pharosng_defi.html   # The entire dashboard — open this
├── README.md            # You are here
├── LICENSE              # MIT
└── CONTRIBUTING.md      # How to contribute
```

---

## 🚀 Usage

**Local:** Clone and open `pharosng_defi.html` in any browser. Zero setup.

```bash
git clone https://github.com/YOUR_USERNAME/pharosng_defi.git
cd pharosng_defi
open pharosng_defi.html
```

**GitHub Pages:** Push to `main`, enable Pages from repo Settings → Pages → deploy from `main`. Your dashboard is live at a public URL instantly.

---

## 📊 Chain Stats (at publish)

| Metric | Value |
|--------|-------|
| Target TPS | 50,000 |
| Unique Testnet Addresses | 131M+ |
| Cumulative Transactions | 1.26B |
| Total Funding | $52M |
| CCTP Domain | 31 |
| Nigerian Population | 220M |
| Crypto Adoption Rank | #3 globally |

---

## 🏗️ Built With

- Vanilla HTML / CSS / JS — zero frameworks, zero dependencies
- [Cabinet Grotesk](https://fonts.google.com/specimen/Cabinet+Grotesk) + [Epilogue](https://fonts.google.com/specimen/Epilogue) + [DM Mono](https://fonts.google.com/specimen/DM+Mono)
- Pharos public JSON-RPC
- open.er-api.com for live USD/NGN rate (optional, graceful fallback)
- Web Crypto API (hash tools)

---

## 🤝 Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## 📄 License

MIT — see [LICENSE](./LICENSE).

---

*🦅 Built for Nigeria · Pharos Pacific Ocean Mainnet · May 2026 · valg*

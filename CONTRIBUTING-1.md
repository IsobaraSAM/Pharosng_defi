# Contributing to pharosng_defi

Thanks for wanting to contribute. This project is deliberately simple — one HTML file, no build toolchain, no framework. Keep it that way.

---

## 🧭 Core Philosophy

- **One file.** Everything lives in `pharosng_defi.html`. No splitting.
- **No dependencies.** Vanilla HTML/CSS/JS only. No npm, no bundler, no React.
- **Wallet-free.** Every tool must work without a connected wallet.
- **Nigeria-relevant.** New features should serve Nigerian users — remittances, NGN conversion, SME tools, offline/low-bandwidth contexts.
- **Live data only.** Tools use Pharos public RPC or work offline (like the converter). No mocked data.

---

## 🐛 Reporting Bugs

Open an issue with:
1. What you expected
2. What happened instead
3. Browser and OS
4. Steps to reproduce

If an RPC endpoint is down, check [PharosScan](https://www.pharosscan.xyz) first — it's likely a network-side issue.

---

## 💡 Good Feature Ideas

- New Nigeria-specific financial tools (e.g. Naira inflation calculator, remittance fee comparator)
- USSD simulation / offline-first tool modes
- NGN stablecoin tracker when one launches on Pharos
- Additional RPC analytics tools
- Improved mobile responsiveness for low-end Android devices
- Multi-language support (Yoruba, Hausa, Igbo)

## ❌ Not a Good Fit

- Wallet connection (breaks the core premise)
- Backend or server-side code
- External API dependencies beyond the open exchange rate API already used
- Frameworks or build tools

---

## 🛠️ Making Changes

### Setup

No setup. Clone and open in browser.

```bash
git clone https://github.com/YOUR_USERNAME/pharosng_defi.git
cd pharosng_defi
open pharosng_defi.html
```

### Workflow

1. Fork the repo
2. `git checkout -b feat/your-feature`
3. Make changes in `pharosng_defi.html`
4. Test in Chrome + Firefox, and on mobile if possible
5. Open a PR with clear description

### Code Style

- Use existing CSS variables (`--gr`, `--oc`, `--ng`, `--em`, etc.)
- New tools follow the `tool-block` pattern with `tool-head`, `tool-desc`, inputs, and `.out` output
- JS: `const`/`let`, async/await, try/catch — match existing style
- Always add a `.copy-btn` to output boxes
- Add Nigeria-relevant context to tool descriptions where applicable

### Adding a New Tool

1. Add HTML in the tools grid
2. Write the JS function with async/try-catch and output via innerHTML
3. Update the tool count in `.tb-count`
4. Add a row to the tools table in `README.md`

---

## ✅ PR Checklist

- [ ] Tested in Chrome and Firefox
- [ ] Mobile-tested (or flagged if not)
- [ ] No new external dependencies
- [ ] Follows existing code and design style
- [ ] Tool count updated if applicable
- [ ] README updated if needed
- [ ] Nigeria-relevance considered

---

## 📄 License

By contributing, you agree your work will be licensed under MIT.

---

*🦅 Built for Nigeria · valg*

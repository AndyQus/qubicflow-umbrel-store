# QubicFlow — Umbrel Community App Store

Self-hosted wallet tracker and tax reporting tool for the [Qubic](https://qubic.org) blockchain network.

![Dashboard](qfstore-qubicflow/gallery/1.png)

---

## Install on your Umbrel

1. Open your Umbrel device → **App Store**
2. Tap the **⋮** menu → **Community App Stores**
3. Add this URL:
   ```
   https://github.com/AndyQus/qubicflow-umbrel-store
   ```
4. Find **QubicFlow** in the Community section and install

---

## Features

### Live Dashboard
Monitor all your Qubic wallets in real time. Incoming and outgoing events are displayed by hour, day, epoch, month and year as new ticks are confirmed on the network.

![Statistics](qfstore-qubicflow/gallery/2.png)

### Multi-Wallet Support
Add unlimited wallets and label them as Private or Business. Filter any view by wallet, owner or function.

### Tax Reporting Engine
Generate accurate tax reports for 14 countries:
`DE` `AT` `CH` `US` `GB` `AU` `CA` `FR` `NL` `IT` `ES` `PT` `SE` `NO`

Choose your cost-basis method — **FIFO, LIFO, HIFO or AVCO** — and let QubicFlow calculate taxable gains, tax-free gains and income automatically. Country-specific holding-period exemptions (e.g. Germany's 1-year rule) are applied automatically.

![Tax Report](qfstore-qubicflow/gallery/3.png)

### Export Formats
- **CoinTracking CSV** — import directly into CoinTracking.info
- **Steuerberater CSV** — semicolon-separated format for German tax advisors
- **PDF Tax Report** — generated on your device, no external service needed

### Privacy by Design
All data stays on your Umbrel. Wallet addresses are masked in the UI by default. No telemetry, no cloud, no external accounts required.

---

## Requirements

- Umbrel OS (any device: Umbrel Home, Raspberry Pi, Linux VM)
- Internet access for Qubic network data

---

## Support

Found a bug or have a question? [Open an issue](https://github.com/AndyQus/qubicflow-umbrel-store/issues)

---

## Developer

Made by AndyQus

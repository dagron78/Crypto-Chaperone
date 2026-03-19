# Crypto Chaperone

A single-file crypto dashboard and transaction inspector that runs entirely in your browser — no install, no build step.

## Features

- **TX Inspector** — Analyze EVM and Solana transactions by hash, with risk scoring and contract verification checks
- **Token Approvals** — View and revoke token approvals for a wallet
- **Portfolio** — Track wallet holdings across ETH, Arbitrum, and Solana
- **Stake / Unstake** — Interface for staking protocols
- **Yield Vaults** — Browse DeFi yields via DeFiLlama
- **Token Swap** — Swap UI
- **Lend / Borrow** — Lending protocol interface
- **AI Advisor** — On-chain intelligence panel
- **Chain support** — Ethereum, Arbitrum, Solana

## Usage

Just open `index.html` in any browser. No server required.

```
open index.html
```

## API Keys

Some features (Etherscan lookups, RPC endpoints) require API keys. Configure them in the **API Keys** settings panel inside the app.

## Built With

- Vanilla HTML/CSS/JS — zero dependencies
- IBM Plex Mono & IBM Plex Sans fonts (Google Fonts)
- DeFiLlama API for yield data

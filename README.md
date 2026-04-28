# BaseGambit# ♟ BaseGambit

> **Play Chess. Build Streaks. Own Progress.**

BaseGambit is a mobile-first chess mini-app built for the Base blockchain ecosystem. Play chess, complete daily tasks, earn XP, and simulate onchain actions — all in a single browser file with no setup required.

---

## 🎮 Live Demo

👉 [Play BaseGambit](https://Harkiem.github.io/basegambit/)

---

## ✨ Features

- **Full Chess Engine** — all legal moves, castling, en passant, pawn promotion, check & checkmate
- **AI Opponent** — Easy (random), Medium (capture-priority), Hard (minimax + alpha-beta)
- **Local Multiplayer** — pass & play on the same device
- **Wallet Connect** — simulated Coinbase Wallet / MetaMask / WalletConnect (Base-ready architecture)
- **Onchain Actions** — simulated tx flow: Save Win, Claim Reward, Mint Badge, Register Username
- **Daily Tasks** — check-in, play a match, win, capture pieces, make moves
- **XP & Streaks** — 14 ranks from Pawn I to King, daily streak tracking
- **Leaderboard** — mock leaderboard with live XP integration
- **Mobile-first** — works perfectly on phones and desktop

---

## 🔗 Built on Base

BaseGambit is designed for the Base ecosystem with wallet architecture ready for:

- Base Mainnet (Chain ID: `8453`)
- Base Sepolia Testnet (Chain ID: `84532`)

Real wallet integration can be enabled by connecting `window.ethereum.request()` in the Wallet Logic section of the source.

---

## 🚀 Getting Started

No installation needed. Just open the file in any browser:

```bash
# Clone the repo
git clone https://github.com/Harkiem/basegambit.git

# Open in browser
open index.html
```

Or simply visit the live link above.

---

## 🛠 Tech Stack

| Layer | Tech |
|---|---|
| Frontend | Vanilla HTML, CSS, JavaScript |
| Storage | localStorage |
| Chain | Base (Mainnet + Sepolia) |
| Wallet | Coinbase Wallet / MetaMask / WalletConnect |
| Hosting | GitHub Pages |

---

## 🗺 Roadmap

- [ ] Real wallet integration (Base Mainnet)
- [ ] Onchain win recording (smart contract)
- [ ] NFT chess piece skins (ERC-1155)
- [ ] Stake matches (low gas wagering)
- [ ] Challenge friends onchain
- [ ] Seasonal ranked ladder
- [ ] Clan battles
- [ ] Puzzle mode

---

## 📁 Project Structure

```
basegambit/
├── index.html       # Full app — chess engine, UI, wallet logic, AI
└── README.md        # This file
```

---

## 📄 License

MIT — free to use, modify, and build on.

---

*Built with ♟ for the Base ecosystem*

<div align="right">
  <!-- Idiomas: -->
  <a title="Português" href="README_ptbr.md">🇧🇷 Português</a>
</div>

# Hand of Lettuce 🥬

**Hand of Lettuce** is a decentralized Web3 game built on Solana blockchain where two players bet on who can HODL their HOL tokens the longest without selling.

---

## Features ✨

- **HODL Challenge** 🎯: Players compete to hold tokens without selling
- **First to Sell Loses** ❌: First player to transfer/sell tokens loses the game
- **Smart Contract Escrow** 🔒: All funds are held and distributed automatically by smart contract
- **Multiple Bet Amounts** 💰: Configurable (default: 30, 50, 100, 300, 500, 1000 tokens)
- **Dynamic Duration System** ⏱️: Configurable durations based on bet amount
- **Treasury System** 🏦: Platform fees accumulate in treasury to fund draw bonuses

---

## Technologies Used 🛠️

### Blockchain
- **Solana** ⚡: High-performance blockchain for smart contracts
- **Anchor Framework** ⚓: Framework for Solana program development
- **SPL Token** 🪙: Solana's native token standard
- **Web3.js** 🌐: JavaScript library for blockchain interaction

### Frontend
- **React 18** ⚛️: JavaScript framework for interactive user interfaces
- **Styled Components** 💅: CSS-in-JS for component styling
- **Anchor Client** 🔗: JavaScript client for Anchor program interaction
- **Solana Wallet Adapter** 👛: Multi-wallet integration for Solana

### Smart Contract
- **Rust** 🦀: Programming language for Solana contract development
- **Anchor** ⚓: Framework that simplifies Solana program development
- **Token Program** 💎: Solana's native program for token operations

---

## Game Mechanics 🎮

### Game Economics
- **Loser Penalty**: 30% of bet amount
- **Winner Reward**: 25% of loser's penalty
- **Platform Fee**: 5% of loser's penalty
- **Draw Bonus**: 5% bonus for both players if both HODL to end

### Game Flow
1. **Creation**: Player creates game and deposits tokens
2. **Joining**: Second player joins the game
3. **Active**: Contract monitors token transfers
4. **Completion**: First to transfer tokens loses automatically

---

## Authors 👥

- **@miltonvo** 👨‍💻: Main developer and responsible for project architecture

---

## Demonstration 📺

| ![Game Lobby](assets/1.png) | ![Create Game](assets/2.png) | ![Join Game](assets/3.png) |
| *Game Lobby* | *Create Game* | *Join Game* |
| ![Active Game](assets/4.png) | ![Game Status](assets/5.png) | ![Winner Screen](assets/6.png) |
| *Active Game* | *Game Status* | *Winner Screen* |
| ![Wallet Connection](assets/7.png) | ![Transaction History](assets/8.png) | ![Leaderboard](assets/9.png) |
| *Wallet Connection* | *Transaction History* | *Leaderboard* |

### Video Demonstration 🎥

🔗 **Clickable content below** ⬇️

[![Watch the video](assets/thumb.png)](https://youtu.be/4m1MJPwiGX0)

---

📄 Full case study on the MV Dev Solutions website: [https://mvdevsolutions.com.br/en/projects/hand-of-lettuce-web3-hodl-game-on-solana](https://mvdevsolutions.com.br/en/projects/hand-of-lettuce-web3-hodl-game-on-solana)

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

| ![Image 1](assets/1.png) | ![Image 2](assets/2.png) | ![Image 3](assets/3.png) |
|:------------------------:|:------------------------:|:------------------------:|
| ![Image 4](assets/4.png) | ![Image 5](assets/5.png) | ![Image 6](assets/6.png) |
| ![Image 7](assets/7.png) | ![Image 8](assets/8.png) | ![Image 9](assets/9.png) |

### Video Demonstration 🎥

🔗 **Clickable content below** ⬇️

[![Watch the video](assets/thumb.jpg)](https://youtu.be/4m1MJPwiGX0)
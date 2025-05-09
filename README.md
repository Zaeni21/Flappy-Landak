# Flappy Landak

Flappy Landak adalah game Web3 berbasis browser dengan integrasi onchain leaderboard. Pemain dapat bermain dalam dua mode: **offchain** atau **onchain**, dan mencatat skor tertinggi mereka langsung ke blockchain!

## Fitur

- **Connect Wallet**: Mendukung EVM wallet seperti MetaMask dan OKX Wallet.
- **Play Offchain**: Main tanpa interaksi blockchain.
- **Play Onchain**: Skor tercatat ke leaderboard onchain.
- **Submit Score**: Kirim skor ke smart contract.
- **Leaderboard**: Lihat Top 10 pemain terbaik.
- **Mint Skin**: (Opsional) Tambahkan NFT skin custom untuk karakter landak kamu.

## Cara Main

1. Buka website: [https://ikiepep.vercel.app](https://ikiepep.vercel.app)
2. Klik **Connect Wallet** untuk mulai mode onchain.
3. Pilih **Play Onchain** atau **Play Offchain**.
4. Capai skor tertinggi dan klik **Submit Score** saat game over.
5. Lihat nama kamu di leaderboard!

## Smart Contract

- **Network**: Monad Testnet
- **Contract Address**: `0x...` (isi dengan address leaderboard kamu)
- **Fungsi Penting**:
  - `submitScore(uint256 score)`
  - `getTopPlayers()`

## Reward Sistem

Top 10 pemain setiap minggu akan mendapatkan hadiah token:

| Rank | Reward |
|------|--------|
| 1    | 20%    |
| 2    | 15%    |
| 3    | 13%    |
| 4    | 11%    |
| 5    | 10%    |
| 6    | 9%     |
| 7    | 7%     |
| 8    | 6%     |
| 9    | 5%     |
| 10   | 4%     |

> Distribusi dilakukan manual oleh tim atau via smart contract.

## Tech Stack

- HTML5 Canvas
- JavaScript + Ethers.js
- TailwindCSS
- Solidity (Leaderboard Contract)
- Deployed on Vercel

## Dev & Kontribusi

Feel free to fork or pull request!

---

Built by [@JAWIRNFT](https://twitter.com/JAWIRNFT) with love for the Web3 gaming community.

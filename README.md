# CHESSChain — On-Chain Memory Game (React + Solidity + Lisk Sepolia)

Chess Flip is a blockchain-powered memory matching game built with React, Solidity, and deployed on the Lisk Sepolia Testnet.
Players connect their MetaMask wallet, pay 0.001 ETH to start a game, and flip cards to match 10 pairs of chess pieces.
Win or lose, players are rewarded automatically through the smart contract — creating verifiable, transparent, and trustless gameplay.

# Key Features

Wallet Integration

Connect with MetaMask

Supports Lisk Sepolia Testnet (Chain ID: 4202)

Handles on-chain interactions for starting games, recording moves, and claiming rewards

Game Mechanics

Pay 0.001 ETH to begin a session

Match 20 cards (10 pairs)

You have 4 lives (wrong matches reduce a life)

Winning reward: 0.002 ETH

Losing reward: 0.0005 ETH

The smart contract automatically processes and distributes rewards.

Smart Reward Handling

If a previous game ended and the reward was not claimed, a
"Forfeit Previous Game & Claim Reward" button appears

Ensures users always get pending rewards

Prevents gameplay conflicts and maintains secure one-game-at-a-time logic

Leaderboard and User Statistics

On-chain tracking of:

Wins

Losses

Number of games played

Total ETH spent

Total ETH rewarded

Leaderboard sorted by wins

All data is fully transparent and publicly verifiable.

Frontend and UI

Built with React and Tailwind CSS

Smooth card flip animation

Mobile responsive

Clear error handling for network mismatches, insufficient funds, or unclaimed rewards

Prerequisites

Node.js 14 or higher

MetaMask browser extension

Lisk Sepolia ETH (via Lisk Bridge or Superchain faucet)

Code editor such as VS Code

Git installed

Installation and Local Development
# Clone the repository
git clone https://github.com/Akanimoh12/Game-Onchain.git

cd Game-Onchain

# Install dependencies (if needed)
npm install

# Run the development server
npm run dev


Open http://localhost:5173/
 in your browser.


Smart Contract Address (Lisk Sepolia)

https://sepolia-blockscout.lisk.com/address/0xa6e4369468fC1dbB21B2A8C9AC4D0391EDb9Fb1F

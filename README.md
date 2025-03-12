# **Solana Arbitrage Trading Bot** 🚀  

A high-performance **on-chain & off-chain arbitrage bot** for Solana-based **DEXs**, designed to identify and execute profitable trades across multiple liquidity pools in real time.  

---

## **📂 Folder Structure**  

- `offchain/` → Off-chain arbitrage bot logic for scanning and executing opportunities  
- `swap/` → On-chain swap program for executing trades efficiently  
- `pools/` → Metadata for decentralized exchange (DEX) liquidity pools  
- `onchain/` → Analytical tools for tracking and optimizing on-chain arbitrage strategies  
- `mainnet/` → Forked **mainnet state** for simulating swap estimates before execution  

---

## **⚡ Features & Capabilities**  

✅ **Real-time Arbitrage Scanning** – Tracks price discrepancies across multiple Solana-based DEXs  
✅ **Automated Swap Execution** – Smart contract-powered on-chain execution with optimized slippage management  
✅ **Gas & Slippage Optimization** – Reduces transaction costs and maximizes profit margins  
✅ **Mainnet Fork Simulation** – Pre-tests trade execution in a forked environment before deploying real capital  
✅ **Multi-DEX Support** – Integrated with major Solana DEXs for maximum trading efficiency  

---

## **🛠️ Supported DEXs**  

### **Current Version** (Standard Arbitrage)  
🔹 Serum  
🔹 Aldrin  
🔹 Saber  
🔹 Mercurial  
🔹 Orca  

### **Advanced Version** (Enhanced Efficiency & More DEXs)  
🔹 Raydium  
🔹 Meteora  
🔹 Serum  
🔹 Aldrin  
🔹 Saber  
🔹 Mercurial  
🔹 Orca  

---

## **⚙️ Setup & Deployment**  

1. **Clone the Repository**  
 ```sh
 git clone https://github.com/Capybara003/Solana-Trading-bot-DEXs.git
 cd Solana-Trading-bot-DEXs
 ```
2. Install Dependencies
  ```sh
  npm install
  ```
3. Configure Environment Variables

Create a `.env` file and set your private key, RPC endpoints, and API keys
4. Run Arbitrage Scanner
  ```sh
  npm run start
  ```

5. Deploy On-Chain Swap Program (for Solana)
  ```sh
  solana program deploy swap/
  ```

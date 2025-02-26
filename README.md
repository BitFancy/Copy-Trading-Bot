# 🚀 **Solana Copy Trading Bot (Rust)**

Welcome to the **Solana Copy Trading Bot**! This bot enables real-time tracking of target wallets (whales) on the Solana blockchain and seamlessly replicates their trades. 🌟

---

## 🔥 **Features**

✅ **Real-time WebSocket Streaming** – Connects to Solana's blockchain using Helius Geyser RPC WebSocket to monitor transactions in real-time.  
✅ **Ultra-Fast Transaction Filtering** – Efficiently filters transactions within ~0.3ms for minimal latency.  
✅ **Automated Copy Trading** – Uses the Pump.fun program ID and Raydium module to mirror target transactions.  

---

## 🎯 **Example Transactions**

- **Source Transaction:** [View on Solscan](https://solscan.io/tx/2nNc1DsGxGoYWdweZhKQqnngfEjJqDA4zxnHar2S9bsAYP2csbLRgMpUmy68xuG1RaUGV9xb9k7dGdXcjgcmtJUh)
- **Copied Transaction:** [View on Solscan](https://solscan.io/tx/n2qrk4Xg3gfBBci6CXGKFqcTC8695sgNyzvacPHVaNkiwjWecwvY5WdNKgtgJhoLJfug6QkXQuaZeB5hVazW6ev)
- **Target Wallet:** `GXAtmWucJEQxuL8PtpP13atoFi78eM6c9Cuw9fK9W4na`
- **Copy Wallet:** `HqbQwVM2fhdYJXqFhBE68zX6mLqCWqEqdgrtf2ePmjRz`

---

## 🚀 **Getting Started**

Follow these steps to set up and run the bot:

### 📌 Prerequisites

- **Rust & Cargo** (Version 1.84.0 or later)
- **Solana Wallet** with access to **Helius Geyser RPC API**

### 📥 Installation

1️⃣ **Clone the Repository:**

```bash
git clone https://github.com/BitFancy/Copy-Trading-Bot-Rust
```

2️⃣ **Navigate & Build:**

```bash
cd copy-trading-bot
cargo build
```

3️⃣ **Configure Environment Variables:**

Update the `ENDPOINT` and `WSS_ENDPOINT` in your config:

```ts
const ENDPOINT = "https://mainnet.helius-rpc.com/?api-key=xxx";
const WSS_ENDPOINT = "wss://atlas-mainnet.helius-rpc.com/?api-key=xxx";
const TARGET = "YOUR_API_TOKEN";
```

4️⃣ **Run the Bot:**

```bash
cargo run
```

---

## 💬 **Need Help? Contact Me!**

If you have any questions, feel free to reach out via:

📩 **Telegram:** [@bitfancy](https://t.me/bitfancy)  
🎮 **Discord:** [@bitbanana717]

🌹 **You're always welcome!** 🌹


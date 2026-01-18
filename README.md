# 💡 Lumina - Crypto Dashboard & Smart Lamp

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/lumina-lamp?style=flat-square)
![GitHub language count](https://img.shields.io/github/languages/count/yourusername/lumina-lamp?style=flat-square)

A premium, interactive cryptocurrency dashboard featuring a 3D smart lamp visualization that changes color based on real-time market trends. Built with **Three.js** and live data from **CoinGecko** and **Alternative.me** APIs.

## ✨ Features

### 🔮 3D Smart Lamp Visualization
- Rotating Icosahedron geometry that reacts to market data
- **Green glow** = market up, **Red glow** = market down
- Premium wireframe aesthetic with pulsing core

### 🐋 Live Transaction Ticker
- Scrolling whale alerts showing large crypto movements
- Creates a sense of real-time blockchain activity

### 📊 Fear & Greed Index Gauge
- Beautiful semi-circular gauge showing market sentiment (0-100)
- Color-coded from Extreme Fear (red) to Extreme Greed (green)
- Data from Alternative.me API

### 📈 Price History Chart
- Interactive Chart.js line chart
- Toggle between **24h**, **7d**, and **30d** timeframes
- Gradient fill with smooth hover interactions

### 🌐 Top 15 Cryptocurrencies Dashboard
- Live prices with coin logos
- 7-day sparkline charts for each coin
- Click any coin to update the lamp and main chart

### 💼 Portfolio Calculator
- Add/remove your holdings
- Real-time total value calculation
- 24h profit/loss indicators
- **Persists across page refreshes** using localStorage

### 🎨 Premium Design
- Cyberpunk UI with glassmorphism effects
- Neon accents and deep dark mode
- Fully responsive (mobile + desktop)

## 📂 Project Structure

```
lumina-lamp/
├── index.html    # Main dashboard with all features
├── future.html   # "Vision 2030" concept page
└── README.md     # Documentation (you are here)
```

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Three.js | 3D lamp visualization |
| Chart.js | Price history charts |
| CoinGecko API | Crypto prices & market data |
| Alternative.me API | Fear & Greed Index |
| localStorage | Portfolio persistence |

## 🚀 How to Deploy on GitHub Pages

1. **Create a Repository**
   - Go to [GitHub.com/new](https://github.com/new) and name your repo (e.g., `lumina-lamp`).

2. **Upload Files**
   - Upload `index.html`, `future.html`, and this `README.md` to your repository.

3. **Activate GitHub Pages**
   - Go to your repository **Settings** tab.
   - Click **Pages** in the left sidebar.
   - Under **Build and deployment** > **Branch**, select `main` (or `master`) and `/root`.
   - Click **Save**.

4. **View Your Site**
   - After 1-2 minutes, refresh the Pages settings to see your live URL (e.g., `https://yourusername.github.io/lumina-lamp/`).

## 💰 Accepting Donations

The `index.html` file includes a **Support the Project** footer. To receive real crypto donations:

1. Open `index.html`.
2. Search for `ReplaceMe` in the footer section.
3. Replace the placeholder addresses with your **actual Bitcoin, Ethereum, and Solana wallet addresses**.

## 📡 API Rate Limits

| API | Limit | Notes |
|-----|-------|-------|
| CoinGecko | 10-30 calls/min | Free tier, no key required |
| Alternative.me | Generous | No auth required |

The site handles rate limiting gracefully with error messages.

## 🖥️ Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

---
*Created for the Future.* 🚀

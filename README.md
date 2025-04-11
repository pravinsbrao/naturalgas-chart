# NATURALGAS Auto Chart (Frontend)

## 🧾 What this does
- Shows 5-minute candlesticks for NATURALGAS using Yahoo Finance (via FastAPI backend)
- Highlights BUY signal if last candle is green and stronger than previous
- Fully static and deployable via GitHub + Vercel

## 🚀 Deploy Instructions

1. Create a GitHub repo and upload this `index.html`
2. Go to https://vercel.com/import
3. Select your GitHub repo and deploy
4. Done! You’ll get a public link like: https://your-chart.vercel.app

## 🔁 Backend Required
Ensure your backend proxy is deployed (like this):
https://natgas-proxy.onrender.com/natgas

Then, this chart will work 100% live. ✅

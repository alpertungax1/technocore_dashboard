# Technocore Close Call — Public Live Leaderboard 🏆

A sleek, standalone, real-time public leaderboard explorer for the **Technocore Close-1 Challenge** by Flop Labs.

## 🚀 Features
- **100% Client-Side & Serverless:** Zero backend required. Directly streams live referee data from `technocore.chat` with public CORS support.
- **Top 25 Official Rankings:** Live scores, ranks, and medals for the 1,000,000 FLOP prize pool (Places 1, 2, and 3).
- **DID Lookup & Search Bar:** Instantly search or filter by any `did:key:z6Mk...` address.
- **Hyperliquid NVDA Live Ticker:** Real-time reference price, referee mark, and limit bands.
- **Countdown to Lock Sweep:** Visual progress bar tracking sweep progress towards Sweep #2556 (Oct 4).
- **Autonomous Auto-Refresh:** Automatically refreshes live data every 10 seconds.
- **Privacy & Isolation:** Completely isolated from private trading bots. Zero keys, secrets, or internal server IPs exposed.

---

## ⚡ How to Deploy on Vercel (3 Easy Methods)

### Method 1: Vercel Dashboard (Fastest — 1 Minute)
1. Push this folder to a new GitHub repository (e.g. `technocore-close1-leaderboard`).
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Select your GitHub repository.
4. Click **"Deploy"** (Leave all build settings default — it's pure static HTML).
5. Done! Your site is live at `https://your-project.vercel.app`.

### Method 2: Vercel CLI (Direct from Terminal)
If you have Vercel CLI installed:
```bash
cd d:\bot\close-call-leaderboard
npx vercel
```
Follow the prompts (accept defaults). It deploys in under 5 seconds!

### Method 3: Drag & Drop (Vercel Drop)
1. Open [vercel.com/new](https://vercel.com/new).
2. Drag and drop the `close-call-leaderboard` folder directly into the browser.
3. Your live link is generated instantly.

---

## 🛠️ Local Testing
To preview locally in your browser:
- Double click `index.html`, or
- Run a quick local server:
  ```bash
  python -m http.server 3000
  ```
  and open `http://localhost:3000`.

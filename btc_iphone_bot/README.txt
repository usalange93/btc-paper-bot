BTC SIGNAL + PAPER BOT — iPHONE SETUP

WHAT YOU GET
- Single-file web app: index.html
- Coinbase public BTC/USD 5-minute and 15-minute completed candles
- EMA9/EMA21 + RSI14 signal, basic candle chart
- $50 starting paper cash, simulated spot buys/sells, configurable fees
- Optional automatic PAPER trades while the webpage is active
- CSV export; trades saved in browser localStorage
- NO real-money execution, NO prediction-market contract pricing

FREE IPHONE-ONLY HOSTING WITH GITHUB PAGES
1. In Safari, create a free account at https://github.com
2. Create a NEW PUBLIC repository named btc-paper-bot (do not add secrets).
3. On the repo page tap Add file > Upload files. Upload index.html from the Files app. Commit changes.
   (If mobile UI hides this, use Safari's Request Desktop Website.)
4. Open repository Settings > Pages. Under Build and deployment choose Deploy from a branch,
   Branch: main, Folder: /(root), then Save.
5. After deployment, visit https://YOUR-GITHUB-USERNAME.github.io/btc-paper-bot/
   (replace YOUR-GITHUB-USERNAME). The first deployment can take several minutes.
6. In Safari tap Share > Add to Home Screen to get an app-like shortcut.
7. Open the webpage, wait for Connected, then use Paper BUY / Paper SELL or toggle
   Auto paper trades ON. For a realistic comparison, set the fee per side to
   your actual trading venue's spot fee (default example 0.4%).

IMPORTANT
- Keep the Safari tab open and phone awake. iOS suspends background pages.
- This is not a reliable 24/7 bot or a push alert service.
- Github Pages is static hosting, NOT a server running a trading process.
- Coinbase public API availability/CORS can change. If the status reads Data unavailable,
  test on Safari while online and check the Coinbase Exchange API status.
- Spot simulator: DOWN means bearish signal, not a short position or a prediction contract.
- Simulated fills use last fetched price + 0.05% slippage on buy, -0.05% on sell,
  plus the entered fee on both sides. This does not model order-book depth, gaps,
  market outages, or prediction-contract settlement.
- This is an educational prototype, not an established profitable strategy.
- Your paper balance and history are device/browser-local, not synced or backed up.
- Public GitHub repositories expose your code; NEVER add API keys or passwords.

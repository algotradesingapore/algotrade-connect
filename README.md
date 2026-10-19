# AlgoTrade Connect (MT4 / MT5)

A free, read-only Expert Advisor for MetaTrader 4 and 5. It sends your trading results to your account on [algotrade.ltd](https://algotrade.ltd), so you can show a live track record on a public page without giving anyone your investor password.

## What it does

- **Read-only.** It never opens, changes or closes a trade. It can run on an investor (read-only) login.
- Uploads your full account history once.
- Then sends balance, equity, open positions and new closed deals: every 1 minute, every 60 minutes, once a day, or only when you press **Send now**.
- Only 3 inputs: **Login** (your algotrade.ltd username or email), **Password** (your algotrade.ltd password, not your broker password) and **Frequency**.
- Name, public or private, portfolio and leaderboard are set on your account page. New accounts start private.

## Get it

- Product page and free download (needs a free algotrade.ltd account): https://algotrade.ltd/algotrade-connect/
- Full setup guide: https://algotrade.ltd/algotrade-connect/guide/

## Quick setup

1. Download AlgoTrade Connect from your account page and install it.
2. Open any one chart of the account (any symbol, any timeframe).
3. Drag **AlgoTrade Connect** onto the chart and tick **Allow DLL imports**.
4. In **Inputs**, fill Login and Password. Frequency can stay at "Every 1 minute".
5. Click OK and make sure **Algo Trading** (MT4: **AutoTrading**) is on.

Runs on Windows (PC or VPS). It does not run on the MetaTrader phone app or in the Strategy Tester.

## Version

Current version: **1.15** (19 Oct 2026). Version history: https://algotrade.ltd/algotrade-connect/guide/#ver

---

AlgoTrade Pte. Ltd., Singapore · https://algotrade.ltd · hi@algotrade.ltd

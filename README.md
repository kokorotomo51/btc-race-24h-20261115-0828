# btc-race-24h-20261115-0828

[![make.fun · btc-race-24h-20261115-0828](https://make.fun/badge/btc-race-24h-20261115-0828.svg)](https://make.fun/bounty/btc-race-24h-20261115-0828?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261115-0828)
[![rank](https://make.fun/badge/btc-race-24h-20261115-0828/kokorotomo51/btc-race-24h-20261115-0828/rank.svg)](https://make.fun/bounty/btc-race-24h-20261115-0828/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261115-0828)
[![reward](https://make.fun/badge/btc-race-24h-20261115-0828/kokorotomo51/btc-race-24h-20261115-0828/reward.svg)](https://make.fun/bounty/btc-race-24h-20261115-0828?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261115-0828)

Build a bot that trades Coinbase Wrapped BTC (cbBTC) on 1-minute on-chain prices with $1,000 of paper money, so nothing is traded for real, for the highest net PnL on the 24 hours that start 15 minutes after the deadline: entries close 6 hours after the opening, the bots that made money on the dev window race live over those 24 hours, and $250 goes to the 10 highest net PnLs, 1st place to the highest, $60 for 1st; the house bots race but never take a place.

Long-only trend bot: it sits in cash through the grind and rides only confirmed up-moves. Entry needs all three — EMA(5) crossing above EMA(30), 20-bar return ≥ +25 bps, and the close breaking the 30-bar high. Exit on a 50 bps trailing stop, an EMA cross back down, or the 30-bar return falling to −20 bps, with a 45-bar cooldown after a losing exit. Dev-window net PnL +$31.10 (+3.11%), 5 trades, max drawdown 1.28% — the only bot above $0 among the kit's six baselines.

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=7bd7933c&utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261115-0828) · AI agents build software for cash rewards</sub>

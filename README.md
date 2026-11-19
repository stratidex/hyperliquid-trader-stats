# Hyperliquid trader statistics (updated daily)

How many Hyperliquid traders make money? Aggregate statistics of **Hyperliquid's public leaderboard**, computed every day by
[StratiDex](https://stratidex.io/stats) — share of accounts in profit and at a loss, median ROI, and how concentrated the profits are.
No addresses, only aggregates.

## Latest figures (2026-11-19)

- **63 % of active Hyperliquid traders lost money over the last 30 days** — 12,093 of 19,069 accounts that traded in that period.
- **The top 1 % took 83 % of all profits** over the last 30 days.
- The median active account returned **−15.8 %** over 30 days; 4.1 % doubled their money.
- Accounts in profit made $1.48 billion together over 30 days; accounts at a loss lost $1.29 billion.
- The leaderboard listed **48,003 accounts**; 2,355 were worth over $1 million (median account value: $348).

| Period | Active accounts | In profit | At a loss | Median ROI |
|---|---|---|---|---|
| 24 hours | 8,274 | 45 % | 52 % | −0.1 % |
| 7 days | 14,034 | 31 % | 61 % | −7.8 % |
| 30 days | 19,069 | 28 % | 63 % | −15.8 % |
| All time | 45,220 | 42 % | 56 % | −16.1 % |

## Files

- [`data/latest.json`](data/latest.json) — today's figures, all periods.
- [`data/history.csv`](data/history.csv) — one row per day, from 2026-11-17.
- The same figures, in ten languages, with a FAQ: **https://stratidex.io/stats**

## Method

Source: Hyperliquid's public leaderboard (`https://stats-data.hyperliquid.xyz/Mainnet/leaderboard`), read once a day — the same file the radar of
[StratiDex](https://stratidex.io), a Telegram bot for trading and copy trading on Hyperliquid, reads. An account is **active** over a period
when its traded volume is above zero; it is **in profit** or **at a loss** according to its PnL over that period, and its ROI is the one
Hyperliquid reports. The **median ROI** is that of the active accounts. The **top 1 %** is the 1 % of active accounts with the largest PnL;
its share is their profits over the sum of all positive PnL. The leaderboard lists the accounts Hyperliquid ranks publicly, not every
wallet that ever used the exchange.

## License and citation

Data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to reuse with attribution.

Cite as: *StratiDex, Hyperliquid trader statistics, 2026-11-19, https://stratidex.io/stats*

---

Want to follow the traders who win? [StratiDex](https://stratidex.io/traders) lists them every day from the same public data —
and [@stratidex_bot](https://t.me/stratidex_bot) copies one from Telegram, at your size.

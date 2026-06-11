================================================================================
CRYPTO POWER FLOW SIGNALS PACK - COMPLETE DATASET
================================================================================
OVERVIEW
================================================================================
This dataset contains 10 proprietary signal files tracking institutional and
smart-money positioning across the crypto market. Data is derived from on-chain
analysis, exchange order books, funding rate monitoring, and whale wallet tracking.
The pack is designed to surface where capital is moving BEFORE broader market
reaction, providing actionable alpha for active traders and fund managers.
================================================================================
FILE MANIFEST
================================================================================
1. whale_accumulation_72h.csv
   - Tracks wallets holding >$1M USD across 10 major tokens
   - Net flows, active addresses, accumulation scores (0-10 scale)
   - Update frequency: every 6 hours
2. funding_rate_divergences.csv
   - Perpetual swap funding rate anomalies across 6/12/24 hour windows
   - Positive divergence = funding cooling while price rises (short signal)
   - Negative divergence = funding heating while price falls (long signal)
3. liquidity_heatmap_stophunts.csv
   - Order book liquidity clusters with stop-hunt probability scores
   - Price levels with >$20M in clustered orders
   - Directional triggers and time estimates
4. token_unlock_schedule_14d.csv
   - Upcoming vesting unlocks with sell-pressure risk ratings
   - Includes recipient type (team/investors/ecosystem) and remaining vesting days
5. order_flow_fake_breakouts.csv
   - Spot vs futures order book imbalances
   - Identifies false breakouts where liquidity is positioned to trap traders
   - 70%+ confidence signals for reversal trades
6. top_wallets_position_changes.csv
   - Real-time tracking of 50+ institutional trading desks
   - Entry/exit actions with position sizes and unrealized P&L
   - Labels include Jump, Wintermute, GSR, Cumberland, DWF Labs
7. smart_money_rotation.csv
   - Capital flow direction between BTC, ETH, and high-beta alts
   - 12-hour rolling windows by trading session (Asia/London/NY)
   - Beta coefficients for rotation targets
8. short_squeeze_liquidation_clusters.csv
   - Clusters of short positions vulnerable to liquidation
   - Open interest + short density + squeeze potential score (1-10)
   - Estimated liquidatable amounts at trigger prices
9. exchange_inflow_outflow_anomalies.csv
   - Z-score anomalies (>2.5 standard deviations from 7-day mean)
   - 24-hour net flows by exchange (Binance, Coinbase, Bybit, etc.)
   - Sell-pressure forecasts with time estimates
10. highest_conviction_setups.csv
    - Top 10 ranked trade setups combining multiple signal confirmations
    - Entry zones, multiple targets, stop losses, risk-reward ratios
    - Key catalysts driving each setup
================================================================================
SIGNAL INTERPRETATION GUIDE
================================================================================
ACCUMULATION SCORES (0-10):
- 8-10: Extreme accumulation (multiple large wallets buying)
- 6-7.9: Moderate accumulation
- 4-5.9: Neutral
- 2-3.9: Moderate distribution
- 0-1.9: Extreme distribution
FUNDING DIVERGENCE TYPES:
- Positive divergence: Funding rate negative/falling → price rising → bullish reversal
- Negative divergence: Funding rate positive/rising → price falling → bearish reversal
- Confidence >80%: High probability move within 6-12 hours
LIQUIDITY STOP-HUNT PROBABILITY:
- 80-100%: Very high - expect sweep within 2-4 hours
- 60-79%: High - expect sweep within 4-8 hours
- 40-59%: Medium
- Below 40%: Low
SELL-PRESSURE RISK (unlocks):
- Extreme: >5% of circulating supply unlocking
- Very high: 3-5%
- High: 2-3%
- Medium: 1-2%
- Low: <1%
SHORT SQUEEZE SCORE:
- 9-10: Critical - cascading liquidations likely
- 7-8.9: High - squeeze probable
- 5-6.9: Moderate
- Below 5: Low
EXCHANGE FLOW Z-SCORE:
- >3.0: Major anomaly (top 1% of flows)
- 2.5-3.0: Significant anomaly
- 2.0-2.5: Minor anomaly
- <2.0: Normal variation
CONVICTION SCORES (top setups):
- 9-10: Highest conviction - multiple signals aligned
- 8-8.9: Strong conviction
- 7-7.9: Moderate conviction
- <7: Low conviction (not featured in top 10)
================================================================================
TOP 3 HIGHEST CONVICTION SETUPS (as of 2026-06-11)
================================================================================
1. PENDLE - Short Squeeze + Whale Accumulation
   - Entry: $4.00-4.08 | Targets: $4.45/$4.75 | Stop: $3.88
   - Conviction: 9.4/10 | R:R: 3.2:1 | Horizon: 24-48h
   - Catalysts: Extreme funding (-0.0112) + $9.8M whale entry + 91% stop-hunt probability
2. ARB - Capitulation Reversal
   - Entry: $1.04-1.08 | Targets: $1.18/$1.25 | Stop: $1.00
   - Conviction: 9.1/10 | R:R: 2.8:1 | Horizon: 48-72h
   - Catalysts: Positive funding divergence (89% confidence) + $67M exchange outflow + whale accumulation
3. SOL - Liquidation Cluster Up
   - Entry: $148-152 | Targets: $162/$170 | Stop: $146
   - Conviction: 8.8/10 | R:R: 2.5:1 | Horizon: 24-36h
   - Catalysts: $85M short liquidation cluster + positive funding divergence (81%) + Coinbase outflow
================================================================================
DISCLAIMER & RISK WARNINGS
================================================================================
This dataset is for INFORMATIONAL AND EDUCATIONAL PURPOSES ONLY.
- NOT financial advice, trading recommendations, or investment guidance
- Past signals do not guarantee future results
- Crypto markets are extremely volatile with risk of total loss
- Always conduct your own research (DYOR) before trading
- The creators assume no liability for trading losses incurred using this data
- Some data points are derived from third-party sources and may contain errors
- Signal confidence scores are statistical probabilities, not guarantees
No warranty is provided regarding accuracy, completeness, or timeliness of data.
================================================================================
DATA SOURCES & METHODOLOGY
================================================================================
Primary sources used to generate this dataset:
- On-chain wallet labeling (Arkham, Nansen, Dune Analytics)
- Exchange order book snapshots (Binance, Coinbase, Bybit, Kraken, OKX)
- Perpetual swap funding rates (Coinglass, Vela)
- Token unlock schedules (TokenUnlocks, CryptoRank)
- Open interest and liquidation data (Coinglass, Laevitas)
- Custom proprietary aggregation algorithms
Each signal file includes timestamps and is designed to be updated every 6-12 hours
for real-time trading applications.
================================================================================
CONTACT & SUPPORT
================================================================================
For data licensing inquiries, API access, or custom signal creation:
- Email: data@cryptopowerflows.io
- Telegram: @crypto_power_flows
- Website: https://cryptopowerflows.io
For technical support with CSV files or data formatting:
- support@cryptopowerflows.io
================================================================================
CHANGELOG
================================================================================
v1.0 (2026-06-11)
- Initial release
- 10 core signal files included
- 72-144 hour rolling window for all dynamic data
- Top 10 conviction setups ranked
================================================================================
END OF README
================================================================================
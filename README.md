# 🧠👑 Big Brain Ape — Fully Autonomous AI Trading Bot

> 🔗 **All links in one place:** [simzy420.github.io/Simzy420](https://simzy420.github.io/Simzy420/)


> **Macro-driven, liquidity-first, 18-month forward thinking.** Modeled after Stanley Druckenmiller's framework: capital preservation first, home runs second.

[![Mintlify Docs](https://img.shields.io/badge/docs-big-brain-ape-trading-bot.mintlify.app-7C3AED)](https://big-brain-ape-trading-bot.mintlify.app)
[![Substack](https://img.shields.io/badge/Substack-@BigBrainApe-FF6719)](https://bigbrainape.substack.com)
[![DegenClaw](https://img.shields.io/badge/DegenClaw-%231729-blue)](https://degen.virtuals.io)
[![Status](https://img.shields.io/badge/status-live-green)]()

---

## What Is Big Brain Ape?

Big Brain Ape is a fully autonomous AI trading bot that trades perpetual futures across **98 assets** on Hyperliquid — crypto, equities, commodities, currencies, and indices.

**No human input required.** The bot runs on a 12-hour cron schedule (8AM / 8PM MYT), analyzes global macro conditions, and executes trades independently via the ACP (Agent Commerce Protocol) CLI.

### Core Philosophy

The bot operates on the **Druckenmiller Framework**:

| Principle | Implementation |
|-----------|---------------|
| **Liquidity First** | Fed policy, global M2, stablecoin flows, credit conditions |
| **18-Month Forward View** | Never trades the present — visualizes 18 months out |
| **Concentration > Diversification** | 1-2 high-conviction positions, not 20 mediocre ones |
| **Capital Preservation** | Cut losers in hours, ride winners for weeks |
| **Position Sizing = 70-80%** | Direction matters less than HOW MUCH you bet |
| **Hedge Matrix Thinking** | Longs + small structural shorts that enable bigger longs |

### Tradeable Universe (98 Assets)

- **Crypto Perps** (~65): BTC, ETH, SOL, AVAX, LINK, DOGE, XRP, HYPE, and more
- **Equity Perps** (~31): NVDA, TSLA, META, AAPL, MSFT, AMZN, AMD, PLTR, COIN, HOOD, MSTR, and more
- **Commodities**: GOLD, SILVER, BRENTOIL, CL, NATGAS, COPPER, URANIUM
- **Currencies**: EUR, JPY, DXY
- **Indices**: SP500, JP225, KR200, XYZ100

### The Three Lenses

Every trade decision runs through three overlapping frameworks:

1. **Liquidity** — The primary timing tool. Fed policy, global M2, credit conditions, stablecoin flows
2. **Valuation** — Not for timing, but for assessing magnitude. How far can this move?
3. **Technicals** — For entry and exit precision. Discretionary chart reading in context of the macro thesis

### Self-Audit Protocol

Every single run, the bot answers six questions with a **fresh mind**:

1. **Fresh-Mind Check**: If I had zero positions right now, what would I buy?
2. **Structural View Check**: Has my 18-month view actually changed?
3. **Concentration Check**: Would Druckenmiller hold this many positions?
4. **Conviction-Sizing Check**: Does position size match stated conviction?
5. **Short Side / Hedge Matrix Check**: What's the tail risk to my longs?
6. **Rationalization Check**: Am I holding anything because of sunk cost or ego?

### Risk Rules

- ✅ Max leverage: 5x
- ✅ Max single position: 50% of capital (jugular phase only)
- ✅ Max portfolio drawdown: 20% → go to cash and reassess
- ✅ Minimum 3:1 risk/reward on every trade
- ❌ Never average down on losers
- ❌ Never chase a move
- ❌ Never trade without a macro thesis
- ❌ Never use leverage above 5x

---

## Architecture

```
┌─────────────┐    ┌──────────────┐    ┌─────────────────┐
│  Cron Timer │───▶│  Macro Gather│───▶│  Druckenmiller  │
│  8AM / 8PM  │    │  (Fed, M2,   │    │  Framework      │
│  MYT        │    │  DXY, news)  │    │  Analysis       │
└─────────────┘    └──────────────┘    └────────┬────────┘
                                                │
                   ┌──────────────┐    ┌────────▼──��─────┐
                   │  Forum Post  │◀───│  Trade Decision │
                   │  (DegenClaw) │    │  (Hold/Add/Cut/ │
                   └──────────────┘    │   New)           │
                                       └────────┬────────┘
                                                │
                                       ┌────────▼────────┐
                                       │  ACP CLI Execute│
                                       │  (Hyperliquid)  │
                                       └─────────────────┘
```

## Data Sources

- **FRED API**: Fed funds rate, M2 money supply, CPI, Treasury yields, credit spreads, VIX, unemployment
- **Binance API**: Crypto prices, funding rates
- **DeFiLlama**: TVL, stablecoin supply, DeFi yields
- **Alpha Vantage**: Stock prices, analyst ratings
- **CoinGecko**: Token prices and market data
- **Frankfurter API**: FX rates
- **Fear & Greedy Index**: Market sentiment
- **Firecrawl**: Web search for macro news and geopolitical developments

## Links

- 📖 [Documentation](https://big-brain-ape-trading-bot.mintlify.app)
- 📰 [Substack — Market Briefings](https://bigbrainape.substack.com)
- 🐦 [X/Twitter — @Big_Brain_Ape](https://x.com/Big_Brain_Ape)
- 🏆 [DegenClaw Arena — #1729](https://degen.virtuals.io)
- 📧 Contact: Big.Brain.Ape.Trading.Bot@gmail.com

## License

This is an autonomous trading bot. The code and strategy are proprietary. All trading is conducted via the ACP CLI on Hyperliquid perpetual futures.

---

*Big Brain Ape is a fully autonomous AI agent. It receives no human input between runs. All trades are executed programmatically based on the Druckenmiller macro framework.*

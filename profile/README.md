# QuantFeatures AI

**Research-ready interval-based quantitative features from raw tick-based or event-based market data.**

QuantFeatures develops high-performance interval-based quantitative indicators and market-data interval summary features for robust trading research, starting with cryptocurrency markets.

## What We Build

Our framework consists of approximately **20 modules containing 1000+ interval-based quantitative indicators and summary features**, derived from tick-based or event-based market data such as:

- Trades and transaction flow at tick-level
- Order-book depth and liquidity at snapshot or event-based
- Price and volatility dynamics
- Market microstructure
- Funding rates update and open interest snapshots
- Liquidations and derivatives activity

The computation framework has been developed and used in the leading professional quantitative research and trading environments.

## Our Offerings

### Historical Feature Datasets

Nearly 7 years of history, December 2019 to today, cleaned and systematically prepared the same way across venues and years. Historical and real-time features come from the same computation, so what you backtest is what you run in production.

Continuous history for Hyperliquid and Binance, at intervals from 30 seconds to 3 hours, available on request in two ways:

1. **Delivered datasets:** we source the tick data and deliver features at intervals from 10 minutes to 3 hours.
2. **Your own tick data:** if you license Tardis data, we compute features at any interval from 30 seconds to 1 hour.

### Client-Hosted Real-Time Feature Computation

A stateful computation engine designed to run on customers' own infrastructure using their licensed market-data feeds, supporting consistency between historical research and live computation.

## Sample Dataset and Documentation

Free showcase samples: hourly features for the first UTC day of each month on Binance, OKX, Bybit, and Hyperliquid, with full schemas and coverage. The hourly interval is for the samples only; full datasets use the interval you choose.

- **[QuantFeatures Sample Dataset](https://github.com/QuantFeatures/FeatureSamples)**: gzip-compressed Parquet files, methodology, and reading examples.
- **[Hugging Face datasets](https://huggingface.co/QuantFeatures)**: the same samples, one dataset per venue, loadable with `datasets` or pandas.
- **[Feature Catalog](https://github.com/QuantFeatures/FeatureCatalog)**: module and field definitions, timestamp semantics, and coverage.

## Partnerships

We are exploring partnerships with market-data providers and quantitative research platforms to distribute historical feature datasets and integrate client-hosted real-time computation.

Potential collaboration models include data licensing, co-branded feature products, and joint distribution.

**Contact:** [QuantFeatures@gmail.com](mailto:QuantFeatures@gmail.com)

## About

QuantFeatures builds on more than two decades of experience in quantitative trading, market microstructure, systematic research, and high-performance data processing.

*QuantFeatures is a trade name of ValueFuse LLC. References to data providers do not imply endorsement or an existing partnership. Research infrastructure, not trading recommendations or a promise of predictive performance.*

# QuantFeatures

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

Research-ready, interval-based market features generated from historical market data, with configurable intervals from 10 minutes to 3 hours; longer intervals are available on request.

### Client-Hosted Real-Time Feature Computation

A stateful computation engine designed to run on customers' own infrastructure using their licensed market-data feeds, supporting consistency between historical research and live computation.

## Sample Dataset and Documentation

Free hourly samples for Binance USDT spot and perpetual instruments, with full schemas and coverage.

- **[QuantFeatures Sample Dataset](https://github.com/QuantFeatures/FeatureSamples)**: gzip-compressed Parquet files, methodology, and reading examples.
- **[Hugging Face dataset](https://huggingface.co/datasets/QuantFeatures/binance-hourly-features)**: the same features as one Parquet file per module, loadable with `datasets` or pandas.
- **[Feature Catalog](https://github.com/QuantFeatures/FeatureCatalog)**: module and field definitions, timestamp semantics, and coverage.

## Partnerships

We are exploring partnerships with market-data providers and quantitative research platforms to distribute historical feature datasets and integrate client-hosted real-time computation.

Potential collaboration models include data licensing, co-branded feature products, and joint distribution.

**Contact:** [QuantFeatures@gmail.com](mailto:QuantFeatures@gmail.com)

## About

QuantFeatures builds on more than two decades of experience in quantitative trading, market microstructure, systematic research, and high-performance data processing.

*QuantFeatures is a trade name of ValueFuse LLC. References to data providers do not imply endorsement or an existing partnership. Research infrastructure, not trading recommendations or a promise of predictive performance.*

# GBPUSD 5m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-37_571_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full GBPUSD dataset on ork.ad**](https://ork.ad/)

**GBPUSD 5m OHLCV Forex historical data** — ultra high-quality 5m OHLCV for **British Pound / US Dollar**. 24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 5m OHLCV** for **British Pound / US Dollar** (Forex)
- **24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **37,571** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `GBPUSD_5m.csv` (37,121 rows, `2026-01-04` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **37,571** `5m` rows (~2.26 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-12-30` → `2026-07-02`.

## Download sample

**[GBPUSD_5m.csv](https://github.com/ork-ad/gbpusd-5m-ohlcv-forex-historical-data/blob/main/GBPUSD_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/gbpusd-5m-ohlcv-forex-historical-data/main/GBPUSD_5m.csv)) · [GitHub Releases](https://github.com/ork-ad/gbpusd-5m-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/gbpusd-5m-ohlcv-forex-historical-data/](https://ork-ad.github.io/gbpusd-5m-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | British Pound / US Dollar · Forex | British Pound / US Dollar · Forex |
| Timeframes | `5m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 5m rows | 37,121 | **37,571** |
| Size | 2.23 MB | ~2.26 MB |
| Period | `2026-01-04` → `2026-07-02` | `2025-12-30` → `2026-07-02` |
| File | `GBPUSD_5m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`5m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `5m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GBPUSD_5m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-04T22:05:00Z | 1.345053 | 1.345053 | 1.344313 | 1.344433 | 70.0 |
| 2026-01-04T22:10:00Z | 1.344433 | 1.344833 | 1.344433 | 1.344813 | 66.0 |
| 2026-01-04T22:15:00Z | 1.344813 | 1.344993 | 1.344683 | 1.344993 | 129.0 |
| 2026-01-04T22:20:00Z | 1.344993 | 1.345413 | 1.344993 | 1.345373 | 80.0 |
| 2026-01-04T22:25:00Z | 1.345373 | 1.345403 | 1.344853 | 1.345143 | 51.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T22:00:00Z | 1.33455 | 1.33484 | 1.33453 | 1.33476 | 216.0 |
| 2026-07-02T22:05:00Z | 1.33476 | 1.33483 | 1.3347 | 1.33475 | 119.0 |
| 2026-07-02T22:10:00Z | 1.33475 | 1.33483 | 1.33472 | 1.33479 | 114.0 |
| 2026-07-02T22:15:00Z | 1.33479 | 1.33485 | 1.33469 | 1.33481 | 64.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GBPUSD_5m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GBPUSD_5m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('GBPUSD_5m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='5min')
print(pf.stats())
```

## Download full data

The complete **GBPUSD** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **37,571** rows at `5m`, plus all other timeframes in the same ZIP.

**[→ Get the full GBPUSD dataset on ork.ad](https://ork.ad/)**

---
*GetData · GBPUSD 5m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*
# META 5m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-222_453_rows-blue)](https://getdata.finance/datasets/meta) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/meta)

### -> [**Download the full META dataset on getdata.finance**](https://getdata.finance/datasets/meta)

**META 5m OHLCV stocks historical data** — ultra high-quality 5m OHLCV for **Meta Platforms**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 5m OHLCV** for **Meta Platforms** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/meta) · **222,453** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `META_5m.csv` (9,906 rows, `2026-03-12` -> `2026-09-11`, 925.46 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/meta)** — **222,453** `5m` rows (full `1m`: 636,459), **11 timeframes**, `2012-05-18` -> `2026-09-11`.

## Download sample

**[META_5m.csv](https://github.com/getdata-finance/meta-5m-ohlcv-stocks-historical-data/blob/main/META_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/meta-5m-ohlcv-stocks-historical-data/main/META_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/meta-5m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/meta-5m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/meta-5m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/meta](https://getdata.finance/datasets/meta)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/meta))** |
|---|--:|---|
| Instrument | Meta Platforms · US stocks | Meta Platforms · US stocks |
| Timeframes | `5m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 5m rows | 9,906 | **222,453** |
| Size | 925.46 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/meta) |
| Period | `2026-03-12` -> `2026-09-11` | `2012-05-18` -> `2026-09-11` |
| File | `META_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/meta) |
| Coverage report | — | [META coverage](https://getdata.finance/coverage/meta) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/meta)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/meta) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`META_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T13:30:00+00:00 | 661.48 | 661.48 | 652.98 | 654.31 | 418 |
| 2026-03-12T13:35:00+00:00 | 654.31 | 656.64 | 654.26 | 656.22 | 348 |
| 2026-03-12T13:40:00+00:00 | 656.22 | 656.74 | 654.69 | 655.61 | 306 |
| 2026-03-12T13:45:00+00:00 | 655.61 | 655.61 | 651.34 | 654 | 453 |
| 2026-03-12T13:50:00+00:00 | 654 | 655.17 | 651.11 | 651.7 | 419 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T19:35:00+00:00 | 649.59 | 649.61 | 648.94 | 649.07 | 180 |
| 2026-09-11T19:40:00+00:00 | 649.07 | 649.11 | 647.93 | 648.15 | 240 |
| 2026-09-11T19:45:00+00:00 | 648.15 | 648.55 | 647.33 | 647.39 | 245 |
| 2026-09-11T19:50:00+00:00 | 647.39 | 647.6 | 645.77 | 646.98 | 390 |
| 2026-09-11T19:55:00+00:00 | 646.98 | 648.39 | 646.53 | 648.04 | 599 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('META_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('META_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('META_5m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='5min')
print(pf.stats())
```

## Download full data

The complete **META** archive on **[getdata.finance](https://getdata.finance/datasets/meta)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **222,453** rows at `5m`, plus all other timeframes in the same ZIP.

**[-> Get the full META dataset on getdata.finance](https://getdata.finance/datasets/meta)**

---
*GetData · META 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/meta)*

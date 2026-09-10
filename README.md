# AUS200 30m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-190_863_rows-blue)](https://getdata.finance/datasets/aus200) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aus200)

### -> [**Download the full AUS200 dataset on getdata.finance**](https://getdata.finance/datasets/aus200)

**AUS200 30m OHLCV index historical data** — ultra high-quality 30m OHLCV for **S&P/ASX 200**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **S&P/ASX 200** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aus200) · **190,863** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `AUS200_30m.csv` (5,469 rows, `2026-03-10` -> `2026-09-09`, 363.59 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/aus200)** — **190,863** `30m` rows (full `1m`: 5,046,226), **11 timeframes**, `2008-09-10` -> `2026-09-09`.

## Download sample

**[AUS200_30m.csv](https://github.com/getdata-finance/aus200-30m-ohlcv-index-historical-data/blob/main/AUS200_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aus200-30m-ohlcv-index-historical-data/main/AUS200_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/aus200-30m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aus200-30m-ohlcv-index-historical-data/](https://getdata-finance.github.io/aus200-30m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aus200](https://getdata.finance/datasets/aus200)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aus200))** |
|---|--:|---|
| Instrument | S&P/ASX 200 · Index | S&P/ASX 200 · Index |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 5,469 | **190,863** |
| Size | 363.59 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Period | `2026-03-10` -> `2026-09-09` | `2008-09-10` -> `2026-09-09` |
| File | `AUS200_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Coverage report | — | [AUS200 coverage](https://getdata.finance/coverage/aus200) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aus200)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/aus200) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T19:00:00+00:00 | 8721.97 | 8737.98 | 8719.46 | 8719.97 | 2156 |
| 2026-03-10T19:30:00+00:00 | 8719.97 | 8728.48 | 8707.46 | 8716.78 | 1802 |
| 2026-03-10T20:00:00+00:00 | 8716.78 | 8720.78 | 8711.78 | 8718.78 | 419.76337 |
| 2026-03-10T20:30:00+00:00 | 8718.78 | 8720.78 | 8718.78 | 8720.78 | 21.8578 |
| 2026-03-10T22:30:00+00:00 | 8720.78 | 8729.47 | 8719.78 | 8729.47 | 136.08156 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T00:00:00+00:00 | 8922.2 | 8945.6 | 8910.1 | 8914.09 | 1074 |
| 2026-09-09T00:30:00+00:00 | 8914.09 | 8917.61 | 8888.6 | 8892.6 | 562 |
| 2026-09-09T01:00:00+00:00 | 8892.6 | 8903.61 | 8885.59 | 8898.1 | 553 |
| 2026-09-09T01:30:00+00:00 | 8898.1 | 8902.6 | 8889.6 | 8894.6 | 456 |
| 2026-09-09T02:00:00+00:00 | 8894.6 | 8894.61 | 8892.11 | 8892.11 | 9 |

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

df = pd.read_csv('AUS200_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AUS200_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[getdata.finance](https://getdata.finance/datasets/aus200)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **190,863** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full AUS200 dataset on getdata.finance](https://getdata.finance/datasets/aus200)**

---
*GetData · AUS200 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aus200)*

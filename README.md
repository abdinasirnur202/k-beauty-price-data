# K-Beauty Price Report: Data (October 2026)

Original Korean skincare pricing statistics from KBeautyIntel. This repository holds the downloadable data behind the report at https://www.kbeautyintel.com/price-report

## Files

| File | Rows | What it contains |
|---|---|---|
| `category-prices-2026-10.csv` | 4 categories | Sunscreens, serums, moisturizers, cleansers: product count, median and mean price, median and mean price per mL |
| `brand-prices-2026-10.csv` | 53 brands | Average price per brand, for brands with at least 3 priced products |
| `price-changes-2026-10.csv` | 25 products | Products whose price changed between weekly snapshots since 2026-09-09 (old price, new price, direction, date) |
| `README.txt` | | Column definitions, license and attribution line |

## How the data was made

- Prices are manually researched, not scraped from a feed or API.
- All prices are in USD. Most current prices (337 of 412 priced products) are Korean retail prices converted to USD, not US shelf prices. The other 75 are direct USD prices.
- Headline per-mL figures use the **median**, because a few very expensive products skew the mean.
- The price-change file covers a short window of weekly snapshots, so treat it as a first look rather than a trend.
- Full methodology: https://www.kbeautyintel.com/price-report

## License and attribution

step by step: Add this one line to each of the three other dataset pages:

```
Cite as: KBeautyIntel. (2026). K-Beauty Price Report: Data (October 2026) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23397584
```

Free to use, including commercially, under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Attribution with a link is required:

> Source: KBeautyIntel K-Beauty Price Report, October 2026, https://www.kbeautyintel.com/price-report

New editions are published as new dated files. Earlier editions stay unchanged so numbers that were cited remain true.

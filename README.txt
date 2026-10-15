K-Beauty Intel Price Report -- October 2026 data files
Generated: 2026-10-15T07:46:07.206Z

category-prices-2026-10.csv
  category                   sunscreens / serums / moisturizers / cleansers
  n                           number of priced products in the category
  median_price_usd            median current price, USD
  mean_price_usd              mean current price, USD
  median_price_per_ml_usd     median price per mL (or per g where the product is measured that way), USD
  mean_price_per_ml_usd       mean price per mL, USD

brand-prices-2026-10.csv
  brand                       brand name
  n_products                  priced products from this brand (brands with fewer than 3 excluded)
  average_price_usd           mean current price across this brand's priced products
  categories                  categories this brand's products fall into, semicolon-separated
  Note: brand averages depend heavily on category mix -- a brand selling mostly serums will
  average higher than one selling mostly cleansers, independent of how it prices within a category.

price-changes-2026-10.csv
  brand, product_name, category   the product
  old_price_usd, new_price_usd    first and most recent recorded price in the snapshot window
  direction                       up or down
  old_date, new_date              dates of the first and most recent snapshot that captured the change
  Snapshot window: weekly snapshots since 2026-09-09. A product only appears here if its
  recorded price differs between its first and most recent snapshot in that window.

License: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)
Attribution: Source: KBeautyIntel K-Beauty Price Report, October 2026, https://www.kbeautyintel.com/price-report

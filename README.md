*Chapter 2 - "Overlapping Behaviour of Institutions and Crowding in Trades" from Deborah Miori's PhD Thesis*

- Notebook "[0] preprocess holdings.ipynb" considers raw holdings data as scratched from SEC 13F filings.
  It divides such data across quarters in an efficient way, and completes some initial data cleaning.
  We provide "raw-data-sample.csv", which a small sample of the raw data used (otherwise approx. 13GB big) to ease reproducibility of the approach.
- Notebook "[1] identify stock sectors.ipynb" groups stocks by their industry classification to do sector analysis, if desired.
  We similarly provide a subset "sample-pricesWRDS_industry.csv" of the data used to achieve such mapping, to allow easier implementation.
- Notebook "[2] allocations to imbalances - efficient.ipynb" then explains how to efficiently compute imbalances from holdings and runs some exploratory analyses.
  It also maps stocks' identifiers within imbalances (i.e. CUSIPs) to tickers via the "stocks.csv" file that we provide.
- We also upload here both "m0trade.csv" and "m0vol.csv" files, which are matrices of trade and volume imbalances, respectively, for a N=0 minimum activity threshold.
  Thanks to these files, the reader can easily run some of their own desired analyses regarding imbalances.

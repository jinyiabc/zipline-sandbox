https://pythonprogramming.net/zipline-local-install-python-programming-for-finance/

1. Import data bundle   
zipline ingest -b quantopian-quandl
2. Enable within jupyter notebook
%load_ext zipline
3. Backtest with data bundle.
%zipline --bundle quantopian-quandl --start 2000-1-1 --end 2012-1-1 -o backtest.pickle

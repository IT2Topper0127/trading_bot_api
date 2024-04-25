# tradingView-API
tradingview socket api for fetching real time prices.

## How to run

```
git clone https://github.com/IT2Topper0127/trading_bot_api.git
cd tradingView-API
pip3 install -r requirements.txt
python3 tradingView.py
```

# How to use

First you should select category type and searching text (by search() function in the code):
```
category list: 'stock' | 'futures' | 'forex' | 'cfd' | 'crypto' | 'index' | 'economic'
```
# Example
```python
data = search('btcusdt', 'crypto')
```

if any results found it will be shown.



# Cryptocurrency Exchanges Fees

A community-driven list with all withdraw fees.

## To contribute

The data should be recorded in dotJSON file following the pattern of those already published.

Example:


Filename: binance.json
```
[
   {
     "symbol": "PIVX",
     "name": "PIVX",
     "withdrawfee": "0.02"
   },
   {
     "symbol": "BTC",
     "name": "Bitcoin",
     "withdrawfee": "0.0005"
   },
]
```

symbol: exactly the same as that returned by the exchange API.

name: full name found in CoinMarketCap or CoinGecko.

withdrawfee: own currency fee charged when making transfers to other portfolios.
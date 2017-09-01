# MyCryptoHoldings

A simple system to get your cryptocurrencies holdings in usd.

## Usage:

Add to "cryptos.json" your crypto accounts. You only need to put the public addresses or balances.

## Example:

cryptos.json:
```
[
	{"currency": "bitcoin", "addr": "15ZrQBTkmxn7nnKUof2FmCmM1nDiosGENQ", "name": "donations"},
	{"currency": "zcash", "addr": "t1bgE4C2WrdAt5L5Yj3fusJzKMBzJoeh1v7", "name": "donations"},
	{"currency": "ethereum", "addr": "0xde0b295669a9fd93d5f28d9ec85e40f4cb697bae", "name": "eth example"},
	{"currency": "monero", "balance": 5.0, "name": "xmr example"}
	{"currency": "bitcoin-cash", "balance": 5.0, "name": "bcc example"}
]
```

run example:
```
#python mch.py 
Retrieving data...
TOTAL HOLDINGS: 648.20 usd
```

## Full supported currencies (retrieving balance from public addresses):

* bitcoin
* zcash
* ethereum

## Complete list of supported currencies (most of them without 'addr' support):

[Link](supported_currencies.md)

## Donations:

* BTC: 15ZrQBTkmxn7nnKUof2FmCmM1nDiosGENQ
* ZEC: t1bgE4C2WrdAt5L5Yj3fusJzKMBzJoeh1v7

## ToDo:

If you want, you can add new classes to "account.py" in order to support more currencies and send me a pull request :)

# CoinSpec Data

Community driven dataset about cryptocurrencies.

| Count | Collection | Description | |
| ---: | --- |  --- | --- |
| 3 | [Assets](/assets) | eq. Coins or Tokens | [JSON Schema](https://github.com/coinspec/schema/blob/master/src/assets.yaml) |
| 94 | [Exchanges](/exchanges) |  | [JSON Schema](https://github.com/coinspec/schema/blob/master/src/exchanges.yaml) |
| 2 | [Wallets](/wallets) |  | [JSON Schema](https://github.com/coinspec/schema/blob/master/src/wallets.yaml) |

## How to build & test

First, you need clone this repository locally:
```bash
git clone git@github.com:coinspec/data.git coinspec-data
cd coinspec-data
npm install
```

then you can use these commands:
```bash
# to generate bundle
npm run-script build

# to run tests
npm test 
```

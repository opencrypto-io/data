# Opencrypto data

Community driven dataset about cryptocurrencies ecosystem.

| Count | Collection | Description | |
| ---: | --- |  --- | --- |
| 1 | [Projects](/projects) |  | [JSON Schema](https://github.com/opencrypto-io/schema/blob/master/src/project.yaml) |
| 0 | [Exchanges](/exchanges) |  | [JSON Schema](https://github.com/opencrypto-io/schema/blob/master/src/exchange.yaml) |
| 0 | [Wallets](/wallets) |  | [JSON Schema](https://github.com/opencrypto-io/schema/blob/master/src/wallet.yaml) |
| 0 | [Trackers](/trackers) |  | [JSON Schema](https://github.com/opencrypto-io/schema/blob/master/src/tracker.yaml) |

## How to build & test

First, you need clone this repository locally:
```bash
git clone git@github.com:opencrypto-io/data.git opencrypto-data
cd opencrypto-data
npm install
```

then you can use these commands:
```bash
# to generate bundle
npm run-script build

# to run tests
npm test 
```

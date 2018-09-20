# OpenCrypto Data

Community-driven cryptoassets reference dataset. Our goal is to put together all basic reference informations about blockchains (ledger), crypto-assets (asset), networks, clients (wallets) and exchanges.

[Homepage](https://data.opencrypto.io) | [Data Explorer](http://explorer.opencrypto.io) | [Schema](https://schema.opencrypto.io)

## Features
* 👥 **Open & Transparent** - Everybody can review changes in [Commit history](../../commits/master), introduce new edits through [Pull Request](../../pulls) or submit a new [Issue](https://github.com/opencrypto-io/data/issues/new) or help with some [existing one](../../issues).
* 📖 **Structured** - Whole database is defined in [JSON Schema](https://json-schema.org/) standard ([schema](https://schema.opencrypto.io)). See [Structure](#structure) section below.
* 🔗 **Consistent** - Each change is tested agains schema (typed), so its not possible to release corrupted data or properties. Changes to [schema](https://schema.opencrypto.io) occurs rare and will be backward compatible. 
* 🌱 **Platform-agnostic** - Database source is just plain-text [YAML](http://yaml.org/) files and because of that it isn't dependent on any database software, platform or specific environment. You can just use [jq](https://stedolan.github.io/jq/) to browse it.
* 🔋 **Compact & Embeddable** - Automated builds produce a single-file version of full database ([data.json](https://data.opencrypto.io/data.json)), which can be easily downloaded/updated/used in any environment (base64 encoded icons and logos included!). See [Builds](#builds) section for more information.
* ⏰ **Up-to-date** - Updates are pushed regularly, Pull Requests are resolved as soon as possible. Automated checks helps to detect outdated links and identify other issues. 
* 🎁 **Forever free**! - Data is licensed under [ODC Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/summary/).


## Structure

All included models in this dataset are specified by [JSON Schema](http://json-schema.org/) vocabulary in separate repository [opencrypto-io/schema](https://github.com/opencrypto-io/schema) Continue to [schema.opencrypto.io](https://schema.opencrypto.io/) for inspect/explore schema and related informations.

There is basic structure of the database:
* Projects
  * Ledgers
    * Networks
  * Assets
  * Clients
  * Exchanges
    * Markets
    
## Libraries

Language | Library | Status | Mantainer
--- | --- | --- | ---
**JavaScript** | [opencrypto-data-js](https://github.com/opencrypto-io/data-js) *(official)* | ✅ Working | OpenCrypto.io
**PHP** | opencrypto-data-php | 🚧 In construction | OpenCrypto.io

## Builds

Latest production bundle is available on this address:

* https://data.opencrypto.io/data.json (full bundle including base64 encoded images)

List of all available builds is available on page [data.opencrypto.io/builds](https://data.opencrypto.io/builds). 

## Documentation
* [How to build & test](/BUILDING.md)
* [Sources](https://github.com/opencrypto-io/data/wiki/Sources) (wiki)

## License

[ODC Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/summary/)



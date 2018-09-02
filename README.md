# OpenCrypto Data

Community-driven cryptoassets reference dataset. Our goal is to create trustable, transparent, consistent and up-to-date source of basic reference informations about blockchains (ledger), crypto-assets (asset), networks, clients (wallets) and exchanges.

[Homepage](https://data.opencrypto.io) | [Data Explorer](http://explorer.opencrypto.io) | [Schema](https://schema.opencrypto.io)

## Features
* **Open & Transparent** - Everybody can review changes in [Commit history](../../commits/master), introduce new edits through [Pull Request](../../pulls) or submit a new [Issue](https://github.com/opencrypto-io/data/issues/new) or help with some [existing one](../../issues).
* **Structured** - Whole database is defined in [JSON Schema](https://json-schema.org/) standard ([schema](https://schema.opencrypto.io)). See [Structure](#structure) section below.
* **Consistent** - Each change is tested agains schema (typed), so its not possible to release corrupted data or properties. Changes to schema occurs rare and will be backward compatible. 
* **Platform-agnostic** - Database source is just plain-text [YAML](http://yaml.org/) files and because of that isn't dependent on any database software, platform or specific environment. You can just use [jq](https://stedolan.github.io/jq/) to browse it.
* **Compact & Embeddable** - Automated builds produce a single-file version of full database ([data.json](https://data.opencrypto.io/data.json)), which can be easily downloaded/updated/used in any environment (base64 encoded icons and logos included!). See [Builds](#builds) section for more information.
* **Up-to-date** - Updates are pushed regularly, Pull Requests are resolved as soon as possible. Automated checks helps to detect outdated links and identify other issues. 
* **Free for forever**! - Data is licensed under [ODC Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/summary/).


## Structure

All models included in this dataset is specified by [JSON Schema](http://json-schema.org/) vocabulary in separate repository [opencrypto-io/schema](https://github.com/opencrypto-io/schema) Continue to [schema.opencrypto.io](https://schema.opencrypto.io/) for inspect/explore schema and related informations.

There is basic structure of the database:
* Projects
  * Ledgers
    * Networks
  * Assets
  * Clients
  * Exchanges
    * Markets
    
## Libraries

Language | Name | Author
--- | --- | ---
**JavaScript** | [opencrypto-data-js](https://github.com/opencrypto-io/data-js) (official) | OpenCrypto.io
**PHP** | opencrypto-data-php (planned) | OpenCrypto.io
**Go** | opencrypto-data-go (planned) | OpenCrypto.io

## Builds

Latest production bundles is available at these addresses.

**Full bundle** of whole database including base64 encoded images:
* https://data.opencrypto.io/data.json
* https://data.opencrypto.io/data.json.gz - gzipped
* https://data.opencrypto.io/data.msgpack - [MessagePack](https://msgpack.org/) format


## Documentation
* [How to build & test](/BUILDING.md)
* [Sources](https://github.com/opencrypto-io/data/wiki/Sources) (wiki)

## License

[ODC Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/summary/)


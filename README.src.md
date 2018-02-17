# CoinSpec Data

Community driven dataset about cryptocurrencies.

| Count | Collection | Description |
| ---: | --- |  --- |<% for (let colId in collections) { %><% let col = collections[colId] %>
| <%= col.count | 0 %> | [<%= col.name %>](/<%= col.name %>) | <%= col.desc %><% } %>

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

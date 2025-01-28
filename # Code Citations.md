# Code Citations

## License: AGPL_3_0

https://github.com/PastVu/pastvu/tree/96319fc26476b78532a47388118182a211305812/.github/workflows/node.js.yml

```
steps:
      - uses: actions/checkout@v2
      - name: Use Node.js ${{ matrix.node-version }}
        uses: actions/setup-node@v2
        with:
          node-version: ${{ matrix.node-version }}
      - run:
```

## License: MIT

https://github.com/scottrabin/is-js/tree/cf4f9ecd98df92f4b3c22c57a9d4f770c41a7f56/.github/workflows/test.yml

```
.js CI

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [14.x, 16.x]

    steps:
      - uses: actions/checkout
```

## License: unknown

https://github.com/saibotsivad/bpr-npm-audit/tree/c6b37fd4bbbb2eb1539a6a17703252eba2f50ec9/.github/workflows/test.yml

```
ubuntu-latest

    strategy:
      matrix:
        node-version: [14.x, 16.x]

    steps:
      - uses: actions/checkout@v2
      - name: Use Node.js ${{ matrix.node-version }}
        uses: actions/setup-node@
```

## License: MIT

https://github.com/quarterback/22ksite/tree/01b6672c9f2e17d47eae37a9172fd65aff5198f7/.github/workflows/nodejs.yml

```
uses: actions/checkout@v2
      - name: Use Node.js ${{ matrix.node-version }}
        uses: actions/setup-node@v2
        with:
          node-version: ${{ matrix.node-version }}
      - run: npm install
      -
```

## License: unknown

https://github.com/ritave/snap-arbitrage/tree/0a4f9b7e90af69341bec3a9273d3d5f0d4ba8860/.github/workflows/build-test.yml

```
:
        node-version: [14.x, 16.x]

    steps:
      - uses: actions/checkout@v2
      - name: Use Node.js ${{ matrix.node-version }}
        uses: actions/setup-node@v2
        with:
          node-version
```

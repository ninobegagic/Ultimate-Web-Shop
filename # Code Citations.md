# Code Citations

## License: unknown

https://github.com/Scerutti/Portfolio/tree/9e13aeb35a7c902570249e41b70c31369066bce4/.github/workflows/main.yml

```
branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout code
      uses: actions/checkout@v2

    - name: Set up Node.js
      uses: actions/setup-node@v2
      with:
        node
```

## License: MPL_2_0

https://github.com/victim-alt/speak-dumbledore/tree/56b9660981bb27383ca92c98a75744184969bc2e/.github/workflows/codeql-analysis.yml

```
- main

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout code
      uses: actions/checkout@v2

    - name: Set up Node.js
      uses: actions/setup-node@v2
      with:
        node-version: '14'

    - name
```

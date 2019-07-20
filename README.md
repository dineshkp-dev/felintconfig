# felintconfig

Front end basic setup for VS Code based on the video from Brad Traversy here: [Video link](https://www.youtube.com/watch?v=SydnKbGc7W8)

## Linter

[ESLint](https://eslint.org/)

## Prettier

[Prettier](https://github.com/prettier/prettier-vscode)

## Style guide

[Airbnb style guide](https://github.com/airbnb/javascript)

## Steps

- Install ESLint VS Code plugin (from: Dirk Baeumer)
- Install Prettier - Code formatter (from: Esben Petersen)
- Install the following packages for eslint, prettier in local:

```bash
npm install --save-dev eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node

```

- Install ESLint cofig for airbnb coding style

```bash
npx install-peerdeps --dev eslint-config-airbnb
```

- (Optional) Install ESLInt globally to generate ESLint config file

```bash
npm install -g eslint
eslint --init
## Provide some answers and once completed,  a .eslintrc.json file will be generated.

```
* Open '.eslintrc.json' file and add the following information:

```bash



```

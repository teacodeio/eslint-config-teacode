# eslint-config-teacode

For **React**. To see for Node version check [eslint-config-teacode-node](https://github.com/teacodeio/eslint-config-teacode-node.git#readme)
## Setup 

#### install:
```bash
npm i eslint-config-teacode -D

# or 

yarn add eslint-config-teacode -D
```


#### Add to `package.json`:
```json
{
  "prettier": "eslint-config-teacode/prettier",
  "devDependencies": {
    "eslint": "^7.0.0 || ^8.0.0",
    "eslint-config-teacode": "^1",
    "typescript": "*"
  }
}
```
Config require both `eslint` and  `typescript` to be installed.

#### Add `.eslintrc`:
```json
{
  "extends": ["eslint-config-teacode"]
}
```

## overriding
Both Prettier and Eslint rules might depend on developers preferences.
Instructions how to change prettier rules can be found [here](https://prettier.io/docs/en/configuration.html#sharing-configurations),
and eslint rules are easily modifiable by adding `rules` in `.eslintrc`.



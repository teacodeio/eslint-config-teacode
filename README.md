# eslint-config-teacode
## Setup 

#### Add to `package.json`:
```json
{
  "prettier": "eslint-config-teacode/prettier",
  "devDependencies": {
    "eslint": "^7",
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



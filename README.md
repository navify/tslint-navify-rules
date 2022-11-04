### :rotating_light: DEPRECATED :rotating_light:

**TSLint isn't maintained anymore. Use Prettier with [`@navify/prettier-config`](https://github.com/navify/prettier-config/).**

# TSLint rules for Navify

Common TypeScript lint rules/preferences for Navify.

## Usage

```bash
npm i -D tslint-navify-rules
```

There is a strict flavor of lint rules, which we recommend:

```json
{
  "extends": "tslint-navify-rules/strict"
}
```

Otherwise, extend the base rules:

```json
{
  "extends": "tslint-navify-rules"
}
```

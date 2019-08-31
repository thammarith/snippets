# Linting

## Installing

```bash
npx install-peerdeps --dev eslint-config-airbnb-base
npm install -D prettier eslint-config-prettier eslint-plugin-prettier
```

## package.json

```javascript
{
  ...,
  "devDependencies": {
    ...,
    "eslint": "^6.1.0",
    "eslint-config-airbnb-base": "^14.0.0",
    "eslint-config-prettier": "^6.1.0",
    "eslint-plugin-import": "^2.18.2",
    "eslint-plugin-prettier": "^3.1.0",
    "prettier": "^1.18.2",
    ...,
  },
  ...
}
```

## .eslintrc.js

```javascript
{
  ...,
  "extends": ["airbnb-base", "prettier"],
  "plugins": ["prettier"],
  "rules": {
    "prettier/prettier": "error"
  },
  ...,
}

## .prettierrc

```javascript
{
  "trailingComma": "es5",
  "semi": true,
  "singleQuote": true,
}
```

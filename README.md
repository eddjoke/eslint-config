## Eslint configuration

Slightly customized React project Eslint configuration based on Airbnb and Prettier.

## Installation

1.  Add `.eslintrc.json, .eslintigore, .prettierrc, .prettierignore` to project root
1.  Run:

```bash
yarn add -D eslint prettier eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react
```

### package.json script

You can add the following script to `package.json` to start using eslint rightaway:

```json
  "lint:js": "eslint . --color",
```

# Typescript Eslint Template
This is a eslint template for typescript

## Based

- Node `v13.12.0`
- npm `6.14.4`

### Core

- [Typescript](https://www.typescriptlang.org/) `^4.1.3`
- [Eslint](https://eslint.org/) `^7.18.0`

### Plugins

- [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin) `^4.13.0`
- [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser) `^4.13.0`


### How to install Eslint into your project

- Install these below packages into your project:
```
npm install typescript^4.1.3 --save-dev
npm install eslint@^7.18.0 --save-dev
npm install @typescript-eslint/parser@^4.13.0 --save-dev
npm install @typescript-eslint/eslint-plugin@^4.13.0 --save-dev
```
- Copy the `.eslintrc.js` and `.eslintignore` into your root project.
- (Optional) Update lint script into `package.json`. This script will check lint for all .ts files:
```
"script": {
  ...,
  "lint": "eslint . --ext .ts"
}
```

### Enhancement
- You can check lint with our sample code:
  + run `npm install`.
  + Write some codes into `./src/index.ts`.
  + run `npm run lint`.
- Install eslint extension `dbaeumer.vscode-eslint` for auto checking eslint when files change (Vscode).
- Install prettier extension `esbenp.prettier-vscode` for use prettier to fix lint problem with eslint configuration (Vscode).
- Want to update more rules. please check [eslint document](https://eslint.org/).

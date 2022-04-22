# 🛠️ Dev Dependency Notes

# Favorite Dev Dependencies

## Linting + Formatting
- [commitlint](https://github.com/conventional-changelog/commitlint): Linting for your commits. `npm install -D @commitlint/cli`.
- [ESLint](https://eslint.org/): A linter for JavaScript/TypeScript that helps find problems and enforce rules in code. Very useful to use along with the `fixAll` on save functionality VS Code offers in your `settings.json` configuration. `npm install -D eslint`.
```json
   "editor.codeActionsOnSave": {
      "source.fixAll.eslint": true
    }
```
- [JS Beautifier](https://github.com/beautify-web/js-beautify): A configurable code formatter for JavaScript/TypeScript. Can be used with VS Code's format on save functionality. `npm install -D js-beautify`.

## TypeScript/JavaScript

### 🧪 Testing
- [Jest](https://jestjs.io/): `npm install -D jest` and for TypeScript, also `npm install -D @types/jest ts-jest`
- [Jasmine](https://jasmine.github.io/): Built in with Angular by default.


## Angular
- [Compodoc](https://compodoc.app/guides/getting-started.html): A tool that generates documentation for Angular projects. `npm install -D @compodoc/compodoc`.

### 🧪 Testing
- [ngMocks](https://ng-mocks.sudo.eu/)

# ESLint + Typescript + Prettier

An arbitrary custom ESLint configuration for React projects

Ideal for projects using [TypeScript](https://www.typescriptlang.org/), [Jest](https://jestjs.io/) with [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

## Usage

1.Install peer dependencies:

```bash
npx install-peerdeps --dev eslint-config-paulopreto
```

2.Extend eslint-config-paulopreto in your eslint file

-  create `.eslintrc` file with the following content:

```json
{
  "extends": ["eslint-config-paulopreto"]
}
```

3.To lint your code run:

```bash
npx eslint .
```

OR if you'd like fixable errors to be fixed automatically, run:

```bash
npx eslint . --fix
```

Remove `"editor.defaultFormatter": "esbenp.prettier-vscode"` line if you had it before.
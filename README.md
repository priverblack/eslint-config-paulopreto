# ESLint + Typescript + Prettier

An arbitrary custom ESLint configuration for Reactjs projects

## Usage

1.Install peer dependencies:

```bash
npx install-peerdeps --dev eslint-config-pp
```

2.Extend eslint-config-pp in your eslint file

-  create `.eslintrc` file with the following content:

```json
{
  "extends": ["eslint-config-pp"]
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
# ESLint configuration

ESLint configuration for my personal projects.

## Install

Install this package, ESLint and the necessary plugins.

```shell
npm install --save-dev @betahuhn/eslint-config eslint eslint-plugin-import eslint-plugin-vue
```

## Usage

Create a file named `.eslintrc.json` with following contents in the root folder of your project:

```json
{
  "extends": "@betahuhn/eslint-config"
}
```

You can override the settings by editing the `.eslintrc.json` file.

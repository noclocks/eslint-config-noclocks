# No Clocks ESLint Configuration

> [!NOTE]
> This repository is published as an NPM package.

<!-- BADGES:START -->

![NPM Version](https://img.shields.io/npm/v/%40noclocksdev%2Feslint-config-noclocks?logo=npm&label=NPM%20Package&labelColor=black)

![GitHub Tag](https://img.shields.io/github/v/tag/noclocks/eslint-config-noclocks?logo=github&label=GitHub%20Package&labelColor=black)

[![Publish NPM Package](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/publish-npm.yml/badge.svg)](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/publish-npm.yml)

[![Automate Changelog](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/changelog.yml/badge.svg)](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/changelog.yml)

<!-- BADGES:STOP -->

## Installation

```bash
npx install-peerdeps --dev eslint-config-noclocks
```

## Usage

In your `.eslintrc.js`:

```tsx
module.exports = {
  extends: ['mantine'],
  parserOptions: {
    project: './tsconfig.json',
  },
};
```

## License

Unlicense

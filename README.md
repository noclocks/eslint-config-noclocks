# No Clocks ESLint Configuration

> [!NOTE]
> This repository is published as an NPM package.

## Contents

- [Badges](#badges)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Badges

<!-- BADGES:START -->

[![GitHub Release](https://img.shields.io/github/v/tag/noclocks/eslint-config-noclocks?logo=github&label=GitHub%20Release)](https://github.com/noclocks/eslint-config-noclocks/releases/latest)

[![NPM Version](https://img.shields.io/npm/v/%40noclocksdev%2Feslint-config-noclocks?logo=npm&label=@noclocksdev/eslint-config-noclocks%20Package)](https://www.npmjs.com/package/@noclocksdev/eslint-config-noclocks) [![GitHub Package](https://img.shields.io/github/v/tag/noclocks/eslint-config-noclocks?logo=github&label=@noclocks/eslint-config-noclocks%20Package)](https://github.com/noclocks/eslint-config-noclocks/pkgs/npm/eslint-config-noclocks)

[![Automate Changelog](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/changelog.yml/badge.svg)](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/changelog.yml) [![Publish GitHub Package](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/publish-ghpkg.yml/badge.svg)](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/publish-ghpkg.yml) [![Publish NPM Package](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/publish-npm.yml/badge.svg)](https://github.com/noclocks/eslint-config-noclocks/actions/workflows/publish-npm.yml)

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

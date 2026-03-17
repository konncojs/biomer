# @konnco/biomer

Standard Frontend rules for Konnco Studio using Biomejs.

## Installation

```bash
# NPM
npm install @konnco/biomer --save-dev

# Yarn
yarn add @konnco/biomer --dev

# PNPM
pnpm add @konnco/biomer --save-dev
```

## Usage

Add the following to your `biome.json` file:

```json
{
  "extends": ["@konnco/biomer/standard"]
}
```

## Examples

```json
{
  "$schema": "https://biomejs.dev/schemas/2.3.12/schema.json",
  "extends": ["@konnco/biomer/standard"],
  "files": {
    "includes": [
      "!!**/*.lottie.json",
      "!!android/*",
      "!!ios/*",
      "expo-env.d.ts"
    ]
  }
}
```

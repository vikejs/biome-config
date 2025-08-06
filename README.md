## Install

```shell
pnpm add -D @biomejs/biome @vike/biome-config
```

## Create biome config

```json
{
  "$schema": "./node_modules/@biomejs/biome/configuration_schema.json",
  "extends": "./node_modules/@vikejs/biome-config/config.json"
}
```

## Update `package.json` scripts

```json
{
  "scripts": {
    "lint": "biome lint",
    "format": "biome format",
    "check": "biome check"
  }
}
```

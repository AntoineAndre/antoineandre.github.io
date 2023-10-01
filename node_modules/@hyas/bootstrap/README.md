# Hyas Bootstrap

Official Bootstrap integration for Hyas.

## Status

[![npm (scoped)](https://img.shields.io/npm/v/@hyas/bootstrap?style=flat-square)](https://www.npmjs.com/package/@hyas/bootstrap)

## Installation

```bash
npm i -D @hyas/bootstrap
```

## Setup

Add mounts to `./config/_default/module.toml`:

```toml
[[mounts]]
  source = "node_modules/@hyas/bootstrap/assets"
  target = "assets"

[[mounts]]
  source = "node_modules/@hyas/bootstrap/layouts"
  target = "layouts"

[[mounts]]
  source = "assets"
  target = "assets"

[[mounts]]
  source = "layouts"
  target = "layouts"
```

## How to use

See the Hyas documentation:

- [Bootstrap](https://docs.gethyas.com/guides/integrations-guide/bootstrap/)

## Credits

This npm package is based on the Bootstrap examples:

- [Bootstrap Color Modes](https://github.com/twbs/examples/tree/main/color-modes)
- [Bootstrap w/ Vite](https://github.com/twbs/examples/tree/main/vite)

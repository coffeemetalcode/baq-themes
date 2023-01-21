# BAQ Themes

Themes and assets for Bon Air Quilt Company's Shopify store

## Preface

Software in this repo uses the [Shopify Liquid](https://shopify.dev/api/liquid) theme engine and is intended to be used with [Shopify CLI](https://shopify.dev/themes/tools/cli).

| Contents                                  |
| ----------------------------------------- |
| [Preface](#preface)                       |
| [Setup](#setup)                           |
| [Commands](#commands)                     |
| [Full Documentation](#full-documentation) |

## Setup

### Prerequisites

- [Node v16.19.0](https://nodejs.org/en/download/releases/)
- [Node Version Manager](https://github.com/nvm-sh/nvm)
- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Bundler](https://bundler.io/)
- [Shopify CLI v3.xx](https://shopify.dev/themes/tools/cli)

## Commands

### Version 3

#### Sync to Store, Login, Build, and Serve

*from the theme's root directory*

```bash
shopify theme dev --store=<store-name>.myshopify.com
```

#### [Full List of V3 Commands](https://shopify.dev/themes/tools/cli/commands)
### Version 2

#### Login

```bash
shopify login --store=<store-name>.myshopify.com
```

#### Fetch Theme

```bash
shopify theme pull --theme=<theme-name-or-id>
```

#### Build and Serve Theme

*from the theme's root directory*

```bash
shopify theme serve
```

#### [Full List of V2 Commands](https://shopify.dev/themes/tools/cli/cli-2/commands)

## Full Documentation

* [Shopify APIs](https://shopify.dev/api)
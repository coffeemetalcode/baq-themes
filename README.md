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
- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Shopify CLI v2.xx](https://rubygems.org/gems/shopify-cli)

@TODO: Upgrade Shopify CLI to [v3.xx](https://shopify.dev/themes/tools/cli/install) (requires Ruby 3)

## Commands

### Login

```bash
shopify login --store=<store-name>.myshopify.com
```

### Fetch Theme

```bash
shopify theme pull --theme=<theme-name-or-id>
```

### Build and Serve Theme

*from the theme's root directory*

```bash
shopify theme serve
```

### [Full List of Commands](https://shopify.dev/themes/tools/cli/cli-2/commands)

## Full Documentation

* [Shopify APIs](https://shopify.dev/api)
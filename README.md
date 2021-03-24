<p align="center">
    <a href="https://github.com/locomotivemtl/locomotive-boilerplate">
        <img src="https://user-images.githubusercontent.com/4596862/54868065-c2aea200-4d5e-11e9-9ce3-e0013c15f48c.png" height="140">
    </a>
</p>
<h1 align="center">Locomotive Shopify Boilerplate</h1>
<p align="center">Front-end Shopify boilerplate for projects by Locomotive.</p>

## @TODO
* Maybe add `.env` to manage global variables and integrate them in `config.yml`
* ✅ Add some kind of live reloading to enhance workflow

## Requirements

| Name       | Version  |
| ---------- | -------- |
| [Node]     | > 14.15  |
| [ThemeKit]     | > 1.1.6  |

[Node]:         https://nodejs.org/en/
[ThemeKit]:     https://github.com/Shopify/themekit

You can use [nvm](https://github.com/nvm-sh/nvm) to install the node version in `.nvmrc`.

## Installation
```sh
npm i
```

## Configuration
Basic knowledge of [ThemeKit](https://github.com/Shopify/themekit) is required.
* Duplicate `config.yml.example` to `config.yml`
```sh
# Example
development:
    password: <password>
    theme_id: "<theme id>"
    store: <store.myshopify.com>
    directory: www
```

## Usage
Open 2 terminal tabs

First tab:
```sh
# start it
npm start
```

Second tab:
```sh
# themekit watch command
theme watch --allow-live
```

## Build

#### Tasks
```sh
# watch
npm start

# build
npm run build
```

## Front-end documentation
Please refer to [locomotive-boilerplate](https://github.com/locomotivemtl/locomotive-boilerplate) to see how to use the boilerplate.



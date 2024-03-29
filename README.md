# Vue Router Quickstart
> Starter template for a multi-page Vue 2 app

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vue-router-quickstart)](https://github.com/MichaelCurrin/vue-router-quickstart/tags/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node](https://img.shields.io/badge/Node.js->=12-blue)](https://nodejs.org)
[![Package - vue](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-router-quickstart/vue?logo=vue.js&logoColor=white)](https://www.npmjs.com/package/vue)
[![Package - vue-router](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-router-quickstart/vue-router)](https://www.npmjs.com/package/vue-router)


## Preview

![Sample 1](/sample-1.png)

![Sample 2](/sample-2.png)


## About

This project was generated using the GUI invoked by this command:

```sh
$ npx @vue/cli ui
```

The _router_ option was enabled there to set up the Home and About pages - _Project plugins_ then _Add vue-router_.

You can also use this to add Vue Router to an existing project.

```sh
$ vue add router
```

To create a simpler project _without_ Vue Router, see:

- [![MichaelCurrin - vue-quickstart](https://img.shields.io/static/v1?label=MichaelCurrin&message=vue-quickstart&color=blue&logo=github)](https://github.com/MichaelCurrin/vue-quickstart)

For a Vue 3 project using Vue Router and slash-based paths.

- [![MichaelCurrin - vue-slash-routes-quickstart](https://img.shields.io/static/v1?label=MichaelCurrin&message=vue-slash-routes-quickstart&color=blue&logo=github)](https://github.com/MichaelCurrin/vue-slash-routes-quickstart)


## Requirements

- [Node.js](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/node.md)
- [Yarn](https://classic.yarnpkg.com/en/)


## Installation
> How to setup the app locally

### Install system dependencies

Install Node.js and Yarn - see these [gist instructions](https://gist.github.com/MichaelCurrin/bdc34c554fa3023ee81449eb77375fcb).

### Clone

Clone the repo - or your own repo generated from the template

```sh
$ git clone git@github.com:MichaelCurrin/vue-router-quickstart.git
$ cd vue-router-quickstart
```

### Install project dependencies

Install Node packages.

```sh
$ yarn install
```

### Recommended extensions

To add syntax highlighting of `.vue` files in VS Code, install an extension such as [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur).


## Usage
> How to run the app locally

### Run

Compile and start a hot-reloading dev server.

```sh
$ yarn serve
```

Open in the browser:

- https://localhost:8080

### Build

Compile and minify for production.

```sh
$ yarn build
```

View the output in the unversioned `dist` directory.

### Lint and fix

```sh
$ yarn lint
```

Add Prettier support:

- Install `prettier`
- Add `@vue/prettier` to `eslintConfig` `extends` in `package.json`.

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).


## License

Released under [MIT](/LICENSE).

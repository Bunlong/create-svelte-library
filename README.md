# create-svelte-library

CLI for creating reusable, modern Svelte libraries using Rollup.

[![NPM](https://img.shields.io/npm/v/create-svelte-library.svg)](https://www.npmjs.com/package/create-svelte-library) [![Build Status](https://api.travis-ci.com/Bunlong/create-svelte-library.svg?branch=master)](https://travis-ci.com/Bunlong/create-svelte-library) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Features

* Easy-to-use CLI
* Handles all modern JS features
* Bundles commonjs and es module formats
* [Sapper](https://sapper.svelte.dev) for example usage and local dev
* [Rollup](https://rollupjs.org/guide/en) for bundling
* [Babel](https://babeljs.io) for transpiling
* Thorough documentation

## Install globally

```sh
npm install -g create-svelte-library
```

## Usage with npx

```sh
npx create-svelte-library
```

([npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) comes with npm 5.2+ and higher, see [instructions for older npm versions](https://gist.github.com/gaearon/4064d3c23a77c74a3614c498a8bb1c5f))

## Creating a New Module

```sh
create-svelte-library
```

Answer some basic prompts about your module, and then the CLI will perform the following steps:

* copy over the template
* install dependencies via yarn or npm
* link packages together for local development
* initialize local git repo

## ❗ Issues

If you think any of the `create-svelte-library` can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to watch/star this repository to revisit.

## 💪 Contribution

We'd love to have your helping hand on contributions to `create-svelte-library` by forking and sending a pull request!

Your contributions are heartily ♡ welcome, recognized and appreciated. (✿◠‿◠)

How to contribute:

- Open pull request with improvements
- Discuss ideas in issues
- Spread the word
- Reach out with any feedback

## ⚖️ License

The MIT License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# react-modern-library-boilerplate

> Boilerplate and CLI for publishing modern React modules with Rollup and example usage via create-react-app.

[![NPM](https://img.shields.io/npm/v/react-modern-library-boilerplate.svg)](https://www.npmjs.com/package/react-modern-library-boilerplate) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Intro

_Note_: Modern means modern as of March, 2018.. I'm sure everything will change in a month... :joy: :joy:

We strongly recommend that you use the accompanying CLI to create new modules based off of this boilerplate.

**The purpose of this boilerplate is to make publishing your own React components as simple as possible.**

## Features

- Easy-to-use CLI
- Transpiles all modern JS features
- Bundles `cjs` and `es` module formats
- [create-react-app](https://github.com/facebookincubator/create-react-app) for example usage and local dev
- [Rollup](https://rollupjs.org/) for build process
- [Babel](https://babeljs.io/) for transpilation
- [Jest](https://facebook.github.io/jest/) for testing
- Supports complicated peer-dependencies
- Supports CSS modules
- Sourcemap creation
- Thorough documentation :heart_eyes:

## Manual Setup

If you'd prefer to setup a new module manually, check out the introductory [blog post](https://hackernoon.com/publishing-baller-react-modules-2b039d84bce7).

## Examples

It comes with an example create-react-app hosted on github pages.

### Material-UI

Here is a [branch](https://github.com/transitive-bullshit/react-modern-library-boilerplate/tree/feature/material-ui) which demonstrates how to create a module that makes use of a relatively complicated peer dependency, [material-ui](https://github.com/mui-org/material-ui). It shows the power of [rollup-plugin-peer-deps-external](https://www.npmjs.com/package/rollup-plugin-peer-deps-external) which makes it a breeze to create reusable modules that include complicated material-ui subcomponents without having them bundled as a part of your module.

# vue-scheduler
[![Build Status](https://travis-ci.org/SSENSE/vue-scheduler.svg?branch=master)](https://travis-ci.org/SSENSE/vue-scheduler)
[![Coverage Status](https://coveralls.io/repos/github/SSENSE/vue-scheduler/badge.svg?branch=master)](https://coveralls.io/github/SSENSE/vue-scheduler?branch=master)
[![Latest Stable Version](https://img.shields.io/npm/v/@ssense/vue-carousel.svg)](https://www.npmjs.com/package/@ssense/vue-scheduler)

> A Vue component to schedule a date & time based on available dates

![screenshot](https://github.com/uptownhr/vue-scheduler/blob/master/vue-scheduler.png?raw=true)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Development](#development)
- [License](#license)

## Installation

``` bash
npm install -S vue-scheduler
```

## Usage

``` js
import Vue from 'vue';
import VueExampleComponent from 'vue-scheduler';

Vue.use(VueExampleComponent);
```

## Documentation

Make sure all dependencies are installed:
``` bash
npm install
```

To run a documentation dev server:
``` bash
npm run docs:dev
```

To build documentation:
``` bash
npm run docs:build
```

To publish documentation to `gh-pages`:
``` bash
npm run docs:publish
```

## Development

A sandboxed dev environment is provided by [vue-play](https://github.com/vue-play/vue-play). Changes made to the component files will appear in real time in the sandbox.

To begin development, run:

``` bash
npm install
npm run dev
```

then navigate to `http://localhost:5000`

To modify and add sandbox scenarios, edit `play/index.js`

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

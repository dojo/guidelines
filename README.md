<p align="center">
	<img src="https://raw.githubusercontent.com/dojo/meta/master/images/Dojo-New.png" alt="Dojo Logo" height="128" width="128" />
</p>

# dojo-meta

[![Join the chat at https://gitter.im/dojo/dojo2](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dojo/dojo2?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This repository contains information regarding Dojo 2 that crosses package boundaries.

## Guidelines and Style Guide

There are several documents that are relevent for contributing to Dojo 2.

* [Contributing Guidelines](CONTRIBUTING.md) - Guidelines for contributing code (or documentation) to Dojo 2
* [Style Guide](STYLE.md) - The style guide for Dojo 2.
* [tslint.json](tslint.json) - The configuration file [tslint](https://palantir.github.io/tslint/) that is used to validate Dojo 2 code against

## Dependent Technologies

While Dojo 2 tries to provide a holistic set of tools to build web applications, there are several key technologies where we feel that Dojo 2 would be better integrating and building upon versus building from the ground up.

In order to ensure that Dojo 2 is a solid set of JavaScript tools and libraries, Dojo 2 is built on [TypeScript](https://www.typescriptlang.org/).  This provides us with structural design time typing as well as an effective way to communicate the intent of the Dojo 2 APIs.  It also provides us the ability to adopt ES6+ syntax features but make distributables that will be backwards compatible to the target browsers for Dojo 2.

In addition, there are some core runtime technologies that parts of Dojo 2 are built on:

* [MaquetteJS](http://maquettejs.org/) a minimalistic virtual DOM built in TypeScript

## Packages

There are several packages that makeup the Dojo 2 platform:

* [`dojo/cli`](https://github.com/dojo/cli) - Command Line Tooling for Dojo 2 Applications
* [`dojo/compose`](https://github.com/dojo/compose) - A mixin/trait based composition library
* [`dojo/core`](https://github.com/dojo/core) - The foundational code of the Dojo 2 platform
* [`dojo/dgrid`](https://github.com/dojo/dgrid) - Reactive extensive grid for Dojo 2
* [`dojo/has`](https://github.com/dojo/has) - A feature detection library
* [`dojo/interfaces`](https://github.com/dojo/interfaces) - Common interfaces and types for Dojo 2
* [`dojo/i18n`](https://github.com/dojo/i18n) - A set of internationalization tooling
* [`dojo/loader`](https://github.com/dojo/loader) - A TypeScript based AMD loader
* [`dojo/routing`](https://github.com/dojo/routing) - A routing service to build web applications with
* [`dojo/shim`](https://github.com/dojo/shim) - Modules that provide fills of ES6+ functionality
* [`dojo/stores`](https://github.com/dojo/stores) - Data stores, querying, transformation and materialization library
* [`dojo/streams`](https://github.com/dojo/streams) - WHATWG Streams implementation
* [`dojo/widget-core`](https://github.com/dojo/widget-core) - The foundation code of Dojo 2 widgets
* [`dojo/widgets`](https://github.com/dojo/widgets) - A set of rich UI elements

We also have packages that are still in their planning stages and as such might not be part of the initial Dojo 2 release.

* [`dojo/actions`](https://github.com/dojo/actions) - A command like library for Dojo 2 applications
* [`dojo/app`](https://github.com/dojo/app) - An application framework for Dojo 2
* [`dojo/crypto`](https://github.com/dojo/crypto) - A set of libraries to deal with cryptography
* [`dojo/dataviz`](https://github.com/dojo/dataviz) - A data visualization library for Dojo 2
* [`dojo/dom`](https://github.com/dojo/dom) - A set of APIs for manipulating the DOM

We have some deprecated packages:

* [`dojo/parser`](https://github.com/dojo/parser) - A HTML document parser for instantiating objects declaratively - *This is deprecated in lieu of functionality provided by `dojo/app`.*

### Examples

We have added a repository of examples which have been built on Dojo 2.  Those examples are available
in the [dojo/examples](https://github.com/dojo/examples) repository.

### Support Packages

There are several packages which are designed to support the Dojo 2 platform:

* [dojo/dojo2-package-template](https://github.com/dojo/dojo2-package-template) - The standard template for Dojo 2 packages, including build and packaging templates
* [dojo/grunt-dojo2](https://github.com/dojo/grunt-dojo2) - A set of Grunt tasks for use with Dojo 2 packages.
* [dojo/intern-helper](https://github.com/dojo/intern-helper) - A set of modules to help with testing Dojo 2 with Intern

These packages are aimed at Dojo 2 contributors rather than Dojo 2 end users.

### Status

The following tables contain status information for the packages:

|Package|CI Status|Code Coverage|npm       |Stage|
|-------|---------|-------------|----------|-----|
|[dojo/cli](https://github.com/dojo/cli/)|[![Build Status](https://travis-ci.org/dojo/cli.svg?branch=master)](https://travis-ci.org/dojo/cli)|[![codecov.io](https://codecov.io/gh/dojo/cli/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/cli/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fcli.svg)](https://badge.fury.io/js/%40dojo%2Fcli)|Beta1|
|[dojo/compose](https://github.com/dojo/compose)|[![Build Status](https://travis-ci.org/dojo/compose.svg?branch=master)](https://travis-ci.org/dojo/compose)|[![codecov.io](https://codecov.io/gh/dojo/compose/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/compose/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fcompose.svg)](https://badge.fury.io/js/%40dojo%2Fcompose)|Beta1|
|[dojo/core](https://github.com/dojo/core)|[![Build Status](https://travis-ci.org/dojo/core.svg?branch=master)](https://travis-ci.org/dojo/core)|[![codecov.io](https://codecov.io/gh/dojo/core/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/core/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fcore.svg)](https://badge.fury.io/js/%40dojo%2Fcore)|Beta1|
|[dojo/dgrid](https://github.com/dojo/dgrid)|[![Build Status](https://travis-ci.org/dojo/dgrid.svg?branch=master)](https://travis-ci.org/dojo/dgrid)|[![codecov.io](https://codecov.io/gh/dojo/dgrid/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/dgrid/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fdgrid.svg)](https://badge.fury.io/js/%40dojo%2Fdgrid)|Alpha|
|[dojo/has](https://github.com/dojo/has)|[![Build Status](https://travis-ci.org/dojo/has.svg?branch=master)](https://travis-ci.org/dojo/has)|[![codecov.io](https://codecov.io/gh/dojo/has/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/has/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fhas.svg)](https://badge.fury.io/js/%40dojo%2Fhas)|Beta1|
|[dojo/interfaces](https://github.com/dojo/interfaces)|[![Build Status](https://travis-ci.org/dojo/interfaces.svg?branch=master)](https://travis-ci.org/dojo/interfaces)|[![codecov.io](https://codecov.io/gh/dojo/interfaces/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/interfaces/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Finterfaces.svg)](https://badge.fury.io/js/%40dojo%2Finterfaces)|Beta1|
|[dojo/i18n](https://github.com/dojo/i18n)|[![Build Status](https://travis-ci.org/dojo/i18n.svg?branch=master)](https://travis-ci.org/dojo/i18n)|[![codecov.io](https://codecov.io/gh/dojo/i18n/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/i18n/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fi18n.svg)](https://badge.fury.io/js/%40dojo%2Fi18n)|Beta1|
|[dojo/loader](https://github.com/dojo/loader)|[![Build Status](https://travis-ci.org/dojo/loader.svg?branch=master)](https://travis-ci.org/dojo/loader)|[![codecov.io](https://codecov.io/gh/dojo/loader/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/loader/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Floader.svg)](https://badge.fury.io/js/%40dojo%2Floader)|Beta1|
|[dojo/routing](https://github.com/dojo/routing)|[![Build Status](https://travis-ci.org/dojo/routing.svg?branch=master)](https://travis-ci.org/dojo/routing)|[![codecov.io](https://codecov.io/gh/dojo/routing/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/routing/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Frouting.svg)](https://badge.fury.io/js/%40dojo%2Frouting)|Beta1|
|[dojo/shim](https://github.com/dojo/shim)|[![Build Status](https://travis-ci.org/dojo/shim.svg?branch=master)](https://travis-ci.org/dojo/shim)|[![codecov.io](https://codecov.io/gh/dojo/shim/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/shim/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fshim.svg)](https://badge.fury.io/js/%40dojo%2Fshim)|Beta1|
|[dojo/stores](https://github.com/dojo/stores)|[![Build Status](https://travis-ci.org/dojo/stores.svg?branch=master)](https://travis-ci.org/dojo/stores)|[![codecov.io](https://codecov.io/gh/dojo/stores/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/stores/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fstores.svg)](https://badge.fury.io/js/%40dojo%2Fstores)|Alpha|
|[dojo/streams](https://github.com/dojo/streams)|[![Build Status](https://travis-ci.org/dojo/streams.svg?branch=master)](https://travis-ci.org/dojo/streams)|[![codecov.io](https://codecov.io/gh/dojo/streams/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/streams/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fstreams.svg)](https://badge.fury.io/js/%40dojo%2Fstreams)|Alpha|
|[dojo/widget-core](https://github.com/dojo/widget-core)|[![Build Status](https://travis-ci.org/dojo/widget-core.svg?branch=master)](https://travis-ci.org/dojo/widget-core)|[![codecov.io](https://codecov.io/gh/dojo/widget-core/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/widget-core/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fwidget-core.svg)](https://badge.fury.io/js/%40dojo%2Fwidget-core)|Beta1|
|[dojo/widgets](https://github.com/dojo/widgets)|[![Build Status](https://travis-ci.org/dojo/widgets.svg?branch=master)](https://travis-ci.org/dojo/widgets)|[![codecov.io](https://codecov.io/gh/dojo/widgets/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/widgets/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fwidgets.svg)](https://badge.fury.io/js/%40dojo%2Fwidgets)|Alpha|

#### CLI Packages

The `dojo/cli` will provide extensible functionality via a variety of packages that can be plugged
into the CLI.

|Package|CI Status|Code Coverage|npm       |Stage|
|-------|---------|-------------|----------|-----|
|[dojo/cli-build](https://github.com/dojo/cli-build)|[![Build Status](https://travis-ci.org/dojo/cli-build.svg?branch=master)](https://travis-ci.org/dojo/cli-build)|[![codecov.io](https://codecov.io/gh/dojo/cli-build/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/cli-build/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fcli-build-webpack.svg)](https://badge.fury.io/js/%40dojo%2Fcli-build-webpack)|Beta1|
|[dojo/cli-create-app](https://github.com/dojo/cli-create-app)|[![Build Status](https://travis-ci.org/dojo/cli-create-app.svg?branch=master)](https://travis-ci.org/dojo/cli-create-app)|[![codecov.io](https://codecov.io/gh/dojo/cli-create-app/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/cli-create-app/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fcli-create-app.svg)](https://badge.fury.io/js/%40dojo%2Fcli-create-app)|Beta1|
|[dojo/cli-test-intern](https://github.com/dojo/cli-test-intern)|[![Build Status](https://travis-ci.org/dojo/cli-test-intern.svg?branch=master)](https://travis-ci.org/dojo/cli-test-intern)|[![codecov.io](https://codecov.io/gh/dojo/cli-test-intern/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/cli-test-intern/branch/master)|[![npm version](https://badge.fury.io/js/%40dojo%2Fcli-test-intern.svg)](https://badge.fury.io/js/%40dojo%2Fcli-test-intern)|Beta1|

#### Proposed packages

|Package|CI Status|Code Coverage|
|-------|---------|-------------|
|[dojo/actions](https://github.com/dojo/actions)|[![Build Status](https://travis-ci.org/dojo/actions.svg?branch=master)](https://travis-ci.org/dojo/actions)|[![codecov.io](https://codecov.io/gh/dojo/actions/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/actions/branch/master)|
|[dojo/app](https://github.com/dojo/app)|[![Build Status](https://travis-ci.org/dojo/app.svg?branch=master)](https://travis-ci.org/dojo/app)|[![codecov.io](https://codecov.io/gh/dojo/app/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/app/branch/master)|
|[dojo/crypto](https://github.com/dojo/crypto)| | | |
|[dojo/dataviz](https://github.com/dojo/dataviz)|[![Build Status](https://travis-ci.org/dojo/dataviz.svg?branch=master)](https://travis-ci.org/dojo/dataviz)| | |
|[dojo/dom](https://github.com/dojo/dom)|[![Build Status](https://travis-ci.org/dojo/dom.svg?branch=master)](https://travis-ci.org/dojo/dom)|[![codecov.io](https://codecov.io/gh/dojo/dom/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/dom/branch/master)|

#### Example app packages

|Package|CI Status|Code Coverage|
|-------|---------|-------------|
|[dojo/examples](https://github.com/dojo/examples)|[![Build Status](https://travis-ci.org/dojo/examples.svg?branch=master)](https://travis-ci.org/dojo/examples)|[![codecov.io](https://codecov.io/gh/dojo/examples/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/examples/branch/master)|

#### Internal packages

|Package|CI Status|Code Coverage|npm       |Stage|
|-------|---------|-------------|----------|-----|
|[dojo/grunt-dojo2](https://github.com/dojo/grunt-dojo2/)|[![Build Status](https://travis-ci.org/dojo/grunt-dojo2.svg?branch=master)](https://travis-ci.org/dojo/grunt-dojo2)|[![codecov.io](https://codecov.io/gh/dojo/grunt-dojo2/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/grunt-dojo2/branch/master)|[![npm version](https://badge.fury.io/js/grunt-dojo2.svg)](https://badge.fury.io/js/grunt-dojo2)|Beta1|
|[dojo/intern-helper](https://github.com/dojo/intern-helper/)|[![Build Status](https://travis-ci.org/dojo/intern-helper.svg?branch=master)](https://travis-ci.org/dojo/intern-helper)|[![codecov.io](https://codecov.io/gh/dojo/intern-helper/branch/master/graph/badge.svg)](https://codecov.io/gh/dojo/intern-helper/branch/master)| |Alpha|

#### Deprecated packages

|Package|
|-------|
|[dojo/parser](https://github.com/dojo/parser)|
|[dojo/cli-css-typings](https://github.com/dojo/cli-css-typings)|

## Licensing information

© [JS Foundation](https://js.foundation/) & contributors. [New BSD](http://opensource.org/licenses/BSD-3-Clause) license.

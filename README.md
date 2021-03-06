
<p align="center">
  <a href="https://vuetifyjs.com" target="_blank">
    <img width="100"src="https://vuetifyjs.com/static/doc-images/logo.svg">
  </a>
</p>

<p align="center">
  <a href="https://travis-ci.org/vuetifyjs/vuetify">
    <img src="https://img.shields.io/travis/vuetifyjs/vuetify.svg" alt="travis ci badge">
  </a>
  <a href="https://codecov.io/gh/vuetifyjs/vuetify">
    <img src="https://img.shields.io/codecov/c/github/vuetifyjs/vuetify.svg" alt="Coverage">
  </a>
  <a href="https://codebeat.co/projects/github-com-vuetifyjs-vuetify-dev">
    <img src="https://codebeat.co/badges/b2d1ce87-848b-440e-9d7e-df9883c0cd93" alt="codebeat badge">
  </a>
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/dm/vuetify.svg" alt="Downloads">
  </a>
  <br>
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/l/vuetify.svg" alt="License">
  </a>
  <a href="https://app.zenhub.com/workspace/o/vuetifyjs/vuetify/boards">
    <img src="https://img.shields.io/badge/Managed_with-ZenHub-5e60ba.svg" alt="zenhub">
  </a>
  <a href="https://chat.vuetifyjs.com">
    <img src="https://img.shields.io/badge/chat-on%20discord-7289da.svg" alt="Chat">
  </a>
  <br>
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/v/vuetify.svg" alt="Version">
  </a>
  <a href="https://cdnjs.com/libraries/vuetify">
    <img src="https://img.shields.io/cdnjs/v/vuetify.svg" alt="CDN">
  </a>
</p>

<br>

<h2 align="center">Supporting Vuetify</h2>
<p>Vuetify is an open source MIT project that has been made possible due to the generous contributions by <a href="https://github.com/vuetifyjs/vuetify/blob/dev/BACKERS.md">community backers</a>. If you are interested in supporting this project, please consider becoming a patron.</p>

<p align="center">
  <a href="https://www.patreon.com/vuetify">
    <img src="https://c5.patreon.com/external/logo/become_a_patron_button.png" alt="Become a Patron" />
  </a>
</p>

<br>
<h3 align="center">Patrons</h3>

<h4 align="center">Diamond</h4>

<p align="center">
  <a href="https://careers.lmax.com/?utm_source=vuetify&utm_medium=github-link&utm_campaign=lmax-careers">
    <img height="70px" src="https://vuetifyjs.com/static/doc-images/backers/lmax-exchange.png">
  </a>
  <a href="http://intygrate.com/?ref=vuetify-github">
    <img height="70px" src="https://vuetifyjs.com/static/doc-images/backers/intygrate.png">
  </a>
</p>

<h4 align="center">Palladium</h4>

<p align="center">
  <a href="http://www.eikospartners.com/?ref=vuetify-github">
    <img height="40px" src="https://vuetifyjs.com/static/doc-images/backers/eikos-partners.webp">
  </a>
  <a href="https://application.rategenius.com/?ref=vuetify-github">
    <img height="40px" src="https://vuetifyjs.com/static/doc-images/backers/rate-genius.png">
  </a>
  <a href="http://quitt.ch/?ref=vuetify-github">
    <img height="40px" src="https://vuetifyjs.com/static/doc-images/backers/quitt.png">
  </a>
  <a href="http://www.clearbluetechnologies.com/?ref=vuetify-github">
    <img height="40px" src="https://vuetifyjs.com/static/doc-images/backers/clear-blue.png">
  </a>
</p>

<br>

## Introduction

Vuetify is a semantic component framework for Vue. It aims to provide clean, semantic and reusable components that make building your application a breeze.

Build *amazing* applications with the power of Vue and Material Design and a massive library of beautifully crafted components. Created according to Google's **<a href="https://material.io/" target="_blank">Material Design Spec</a>**, Vuetify components feature an easy-to-remember semantic design that shifts remembering complex classes and markup, to type-as-you speak properties that have simple and clear names.

Harness the power of the [Vuetify community](https://chat.vuetifyjs.com) and get help 24/7 from the development team and our talented community members across the world. Become a [backer](https://www.patreon.com/vuetify) and get access to dedicated support from the team.

### Browser Support

Vuetify supports all **modern browsers**, including IE11 and Safari 9+ (using polyfills). From mobile to laptop to desktop, you can rest assured that your application will work as expected. Interested in the bleeding edge? Try the vue-cli Webpack SSR (Server side rendered) template and build websites optimized for SEO.

## Documentation

You can find the Vuetify documentation <a href="https://vuetifyjs.com" target="_blank">on the website</a>.

## One minute Quick-start

[Codepen link](https://codepen.io/johnjleider/pen/jYZwVZ)
```html
<!DOCTYPE html>
<html>
<head>
  <link href='https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Material+Icons' rel="stylesheet">
  <link href="https://unpkg.com/vuetify/dist/vuetify.min.css" rel="stylesheet">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no, minimal-ui">
</head>
<body>
  <div id="app">
    <v-app>
      <v-content>
        <v-container>Hello world</v-container>
      </v-content>
    </v-app>
  </div>

  <script src="https://unpkg.com/vue/dist/vue.js"></script>
  <script src="https://unpkg.com/vuetify/dist/vuetify.js"></script>
  <script>
    new Vue({
      el: '#app'
    })
  </script>
</body>
</html>
```

## Installation

``` bash
# npm
npm install vuetify
```

``` bash
# yarn
yarn add vuetify
```

## Usage

```javascript
import Vue from 'vue'
import Vuetify from 'vuetify'

Vue.use(Vuetify)
```

For including styles, you can either place the below styles in your `index.html`
```html
<link href='https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Material+Icons' rel="stylesheet">
<link href="https://unpkg.com/vuetify/dist/vuetify.min.css" rel="stylesheet">
```
Or you can import it to your webpack entry point
```javascript
require('https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Material+Icons')
require('/path/to/node_modules/vuetify/dist/vuetify.min.css')
```
Keep in mind, you will need to ensure your webpack config contains a <a href="https://github.com/webpack-contrib/css-loader" target="_blank">css loader</a>.

## Community Support

Ask your support questions on the [Vuetify Discord Community](https://community.vuetifyjs.com/).

Frequently asked questions and Gotchas on the [FAQ Guide](https://vuetifyjs.com/vuetify/frequently-asked-questions)

## Contributing

Developers interested in contributing should read the [Code of Conduct](./CODE_OF_CONDUCT.md).

> Please do **not** ask general questions in an issue. Issues are only to report bugs, request
  enhancements, or request new features. For general questions and discussions, ask on the [Vuetify Discord Community](https://community.vuetifyjs.com/).

It is important to note that for each release, the detailed changes are documented in the [release notes](https://github.com/vuetifyjs/vuetify/releases).

### Contributing Guide

You can report issues by following the [Issue Template](https://issues.vuetifyjs.com/) and you can create a minimal reproduction with a [CodePen template](https://template.vuetifyjs.com/) or a full project at [CodeSandbox](https://codesandbox.io/s/vue).

### Good First Issue

To help you get you familiar with our contribution process, we have a list of [good first issues](https://github.com/vuetifyjs/vuetify/labels/good%20first%20issue) that contain bugs which have a relatively limited scope. This is a great place to get started.

We also have a list of [help wanted](https://github.com/vuetifyjs/vuetify/labels/help%20wanted) issues that you might want to check.

### License

Vuetify is [MIT licensed](./LICENSE).

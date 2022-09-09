# Text Editor
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This is  a single-page, text editor application that runs in the browser and meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.


## Table of Contents

  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [How to Contribute](#how-to-contribute)
  - [Tests](#tests)
  - [Questions](#questions)
  - [Heroku URL](#heroku-url)

## Installation

To install this application, you will need to clone the repo and run a few commands into the terminal. 

**Installs include**:

* ``npm init`` followed by ``npm install`` (These commands will install the dependencies needed for the package.json)

**Dependencies**
* ``idb``| This is a tiny library that mostly mirrors the IndexedDB API, but with small improvements that make a big difference to usability.
* ``concurrently``| Run multiple commands concurrently.
* ``webpack``| Webpack is a module bundler. Its main purpose is to bundle JavaScript files for usage in a browser, yet it is also capable of transforming, bundling, or packaging just about any resource or asset.
* ``webpack-cli``
* ``webpack-dev-server``
* ``webpack-pwa-manifest``
* ``workbox-webpack-plugin``| A plugin for your Webpack build process, helping you generate a manifest of local files that workbox-sw should precache.
* ``html-webpack-plugin``| Plugin that simplifies creation of HTML files to serve your bundles.
* ``http-server``| A simple, zero-configuration command-line static HTTP server.
* ``css-loader``| Interprets @import and url() like import/require() and will resolve them.
* ``style-loader``| Inject CSS into the DOM.
* ``babel-loader``| Used to convert code written in modern flavors and supersets of JavaScript into plain old JavaScript code supported by older browsers.
* ``@babel/runtime``
* ``@babel/preset-env``
* ``@babel/plugin-transform-runtime``
* ``@babel/core``

>_If you want to learn more about any of these npm packages, [click here](https://www.npmjs.com/)._

## Usage

The application runs via the root directory by typing ``npm run build`` into your terminal (this will create the dist folder), followed by ``npm run start``(this will start the server on localhost 3000).

When the user clicks the 'Install' button, the web application will download to the machine.

## License

This project is licensed under **MIT** license.

## How to Contribute

When creating an open source project on GitHub, there is always the option for other developers to contribute to your projects. | If you would like to contribute, please contact me at the email listed below.

## Tests

At this time, no tests have been documented for this application.

## Questions

Please reach out with any questions you may have about this application.

* :octocat: GitHub: [@lindsey-lansford](https://github.com/lindsey-lansford)
* :envelope: Email: lindsey.lansford@gmail.com

## Heroku URL

[Heroku Deployed URL](https://enigmatic-plains-15102.herokuapp.com/)

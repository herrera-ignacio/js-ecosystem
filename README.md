# js-ecosystem

A curated list of *open source* and free tooling for js projects

> For framework-related tools please check [React ecosystem](./react.md) or [Express ecosystem](./express.md).

- [js-ecosystem](#js-ecosystem)
  - [CLIs](#clis)
  - [Data Layer & State Management](#data-layer--state-management)
    - [Redux](#redux)
  - [Data Visualization](#data-visualization)
  - [Development (Monitoring, Clustering, CI/CD)](#development-monitoring-clustering-cicd)
  - [Frameworks](#frameworks)
    - [Graphql](#graphql)
  - [Guidelines & Examples](#guidelines--examples)
  - [Immutability](#immutability)
  - [Networking](#networking)
  - [Security](#security)
  - [Styling](#styling)
  - [Testing & Automation](#testing--automation)
  - [Utility](#utility)

## CLIs

* [colors](https://github.com/Marak/colors.js) - get color and style in your node.js console
* [Commander](https://github.com/tj/commander.js) - complete solution for CLIs
* [Inquirer](https://www.npmjs.com/package/inquirer) - collection of common interactive CLIs
* [minimist](https://www.npmjs.com/package/minimist) - minimalistic argument parser
* [yargs](https://www.npmjs.com/package/yargs) - argument parser

## Data Layer & State Management

* [neo4j](https://neo4j.com/)
* [RxJs](https://rxjs.dev/)
* [Mongoose](https://github.com/Automattic/mongoose) - MongoDB ORM
* [Node-Redis](https://github.com/redis/node-redis) - high performance Redis client
* [Sequelize](https://github.com/sequelize/sequelize) - Active Record promise-based ORM
* [TypeORM](https://github.com/typeorm/typeorm) - Active Record & Data Mapper ORM
* [protobuf](https://github.com/protobufjs/protobuf.js) - Protocol Buffers implementation for serializing data

### Redux

> Official [Redux site](https://redux.js.org/) and [Redux style guide](https://redux.js.org/style-guide/style-guide)

* [Redux DevTools](https://github.com/reduxjs/redux-devtools)
  * [d3-state-visualizer](https://github.com/reduxjs/d3-state-visualizer)
* [Redux Saga](https://redux-saga.js.org/) - side effect manager based on ES6 generators
* [Redux Thunk](https://github.com/reduxjs/redux-thunk)
* [Reselect](https://github.com/reduxjs/reselect)
* [Ducks Pattern](https://github.com/erikras/ducks-modular-redux)
  * [extensible-duck](https://github.com/investtools/extensible-duck)
  * [ducks-middleware](https://github.com/drpicox/ducks-middleware)
  * [ducks-reducer](https://github.com/drpicox/ducks-reducer)
* [Redux Toolkit](https://redux-toolkit.js.org/)
* Examples
  * [redux-essentials-counter-example](https://github.com/reduxjs/redux-essentials-counter-example)

## Data Visualization

> See [Awesome Charting Repository](https://github.com/zingchart/awesome-charting) for a complete curated list

* [Billboard](https://naver.github.io/billboard.js/)
* [Chart.js](https://www.chartjs.org/) 
* [D3](https://d3js.org/)
* [vis](https://visjs.org/)
* [Google Charts](https://developers.google.com/chart/)

## Development (Monitoring, Clustering, CI/CD)

* [core-js](https://github.com/zloirock/core-js) - modular STL for JS with polyfills
* [debug](https://github.com/debug-js/debug) - tiny debugging utility
* [ESlint](https://eslint.org/) - JS linting
* [Husky](https://www.npmjs.com/package/husky)
* [nodemon](https://nodemon.io/) - restart application when file changes in the directory are detected
* [Sentry](https://sentry.io/welcome/)
* [tracer](https://github.com/baryon/tracer) - customizable logging library
* [Webpack](https://webpack.github.io/) - module bundler

## Frameworks

* [Angular](https://github.com/angular/angular) - mobile and desktop web applications framework
* [Connect](https://github.com/senchalabs/connect) - extensible HTTP server framework using middlewares
* [Elasticsearch](https://github.com/elastic/elasticsearch-js) - distributed, RESTful search and analytics engine
* [Express](https://expressjs.com/) - webApp framework built upon Connect
* [Jade](https://www.npmjs.com/package/jade) - template engine
* [React](https://reactjs.org/) - library for building user interfaces
* [Restify](https://github.com/restify/node-restify) - Connect-style middleware for building REST APIs
* [Sails](https://github.com/balderdashy/sails) - built on Express, Socket.io and Waterline ORM
* [Typescript](https://www.npmjs.com/package/typescript) - Language extension for application-scale JS
* [Koa](https://www.npmjs.com/package/koa) - expressive HTTP middleware framework

### Graphql

* [Apollo](https://www.apollographql.com/pricing)
  * [Rover CLI](https://www.apollographql.com/docs/rover/)
* [graphql-yoga](https://github.com/dotansimha/graphql-yoga)

## Guidelines & Examples

* [Domain: don't ignore errors](https://nodejs.org/docs/latest/api/domain.html#domain_warning_don_t_ignore_errors)

## Immutability

* [Immer](https://immerjs.github.io/immer/)
* [immutable.js](https://github.com/immutable-js/immutable-js)

## Networking

* [axios](https://www.npmjs.com/package/axios) - promise based HTTP client
* [node-mailer](https://www.npmjs.com/package/nodemailer) - send e-mails from Node.js 
* [http-errors](https://github.com/jshttp/http-errors) 
* [response-time](https://github.com/expressjs/response-time)
* [rid](https://github.com/node-modules/rid) - request unique id
* [soap](https://github.com/vpulim/node-soap) - soap client and server
* [WebSocket-Node](https://github.com/theturtle32/WebSocket-Node) - WebSocket client & server

## Security

* [bcrypt](https://github.com/kelektiv/node.bcrypt.js) - hash passwords
* [crypto](https://www.npmjs.com/package/crypto-js) - crypto standards
* [csp-header](https://github.com/frux/csp/tree/master/packages/csp-header#readme) - Content-Security-Policy header generator

## Styling

* [Autoprefixer](https://github.com/postcss/autoprefixer) - parse CSS and add vendor prefixes
* [Dart Sass](https://github.com/sass/dart-sass) - CSS extension
* [Styled Components](https://github.com/styled-components/styled-components) - write CSS code to style your components

## Testing & Automation

* [Gulp](https://www.npmjs.com/package/gulp) - automation toolkit
* [Invariant](https://github.com/zertosh/invariant) - a mirror of Facebook's invariant
* [Jest](https://jestjs.io/)
* [Mocha](https://mochajs.org/)
* [Node Schedule](https://github.com/node-schedule/node-schedule) - flexible scheduler
* [Puppeteer](https://github.com/puppeteer/puppeteer) - high-level API to control Chrome or Chromium over the DevTools Protocol

## Utility

* [async](https://github.com/caolan/async) - helper methods for working with asynchronous JS
* [async-validator](https://github.com/yiminghe/async-validator) - validate form asynchronous
* [clipboard](https://github.com/zenorocha/clipboard.js) - lightweight copy to clipboard
* [codemirror](https://github.com/codemirror/CodeMirror) - versatile text editor with over 100 language modes and various addons
* [compression](https://www.npmjs.com/package/compression) - deflate & gzip compression middleware
* [debounce](https://github.com/component/debounce) - wraps function so that it will postpone its execution until after wait milliseconds have elapsed since the last time it was invoked
* [donwload](https://github.com/kevva/download) - download and extract files
* [fs-extra](https://www.npmjs.com/package/fs-extra) - adds file system methods and promise support
* [fuzzy](https://github.com/mattyork/fuzzy) - 1k standalone fuzzy search
* [glob](https://www.npmjs.com/package/glob) - match files using the patterns the shell uses
* [lodash](https://github.com/lodash/lodash) - utility library delivering modularity, performance, & extras
* [Math.js](https://www.npmjs.com/package/mathjs) - extensive math library
* [Moment](https://www.npmjs.com/package/moment) - date library for parsing, validating, manipulating, and formatting dates
* [node-notifier](https://github.com/mikaelbr/node-notifier) - cross platform native notifications
* [safe-regex](https://www.npmjs.com/package/safe-regex) - detect potentially catastrophic exponential-time regular expressions
* [uglify](https://www.npmjs.com/package/uglify-js) - JS parser, minifier, compressor and beautifier toolkit
* [underscore](https://underscorejs.org/) - useful functional programming helpers
* [uuid](https://www.npmjs.com/package/uuid) - creation of RFC4122 UUIDs
* [vuln-regex-detector](https://github.com/davisjam/vuln-regex-detector) - detect regexes that could lead to catastrophic backtracking


# js-ecosystem

A curated list of *open source* and free tooling for js projects

> For framework-related tools please check [react ecosystem](./react.md) or [express ecosystem](./express.md).

- [js-ecosystem](#js-ecosystem)
  - [Data Layer & State Management](#data-layer--state-management)
    - [Redux](#redux)
      - [Examples](#examples)
  - [Data Visualization](#data-visualization)
  - [Frameworks](#frameworks)
    - [Graphql](#graphql)
  - [General Purpose (Monitoring, Clustering, CI/CD)](#general-purpose-monitoring-clustering-cicd)
  - [Guidelines & Examples](#guidelines--examples)
  - [Immutability](#immutability)
  - [Networking](#networking)
  - [Security](#security)
  - [Testing](#testing)
  - [Worth Mentioning](#worth-mentioning)

## Data Layer & State Management

* [neo4j](https://neo4j.com/)
* [RxJs](https://rxjs.dev/)

### Redux

> Official [Redux site](https://redux.js.org/) and [Redux style guide](https://redux.js.org/style-guide/style-guide)

* [Redux DevTools](https://github.com/reduxjs/redux-devtools)
  * [d3-state-visualizer](https://github.com/reduxjs/d3-state-visualizer)
* [Redux Thunk](https://github.com/reduxjs/redux-thunk)
* [Reselect](https://github.com/reduxjs/reselect)
* [Ducks Pattern](https://github.com/erikras/ducks-modular-redux)
  * [extensible-duck](https://github.com/investtools/extensible-duck)
  * [ducks-middleware](https://github.com/drpicox/ducks-middleware)
  * [ducks-reducer](https://github.com/drpicox/ducks-reducer)
* [Redux Toolkit](https://redux-toolkit.js.org/)

#### Examples

* [redux-essentials-counter-example](https://github.com/reduxjs/redux-essentials-counter-example)

## Data Visualization

> See [Awesome Charting Repository](https://github.com/zingchart/awesome-charting) for a complete curated list

* [Billboard](https://naver.github.io/billboard.js/)
* [Chart.js](https://www.chartjs.org/) 
* [D3](https://d3js.org/)
* [vis](https://visjs.org/)
* [Google Charts](https://developers.google.com/chart/)

## Frameworks

* [Connect](https://github.com/senchalabs/connect) - extensible HTTP server framework using middlewares
* [Express](https://expressjs.com/) - webApp framework built upon Connect
* [Restify](https://github.com/restify/node-restify) - Connect-style middleware for building REST APIs
* [Sails](https://github.com/balderdashy/sails) - built on Express, Socket.io and Waterline ORM

### Graphql

* [Apollo](https://www.apollographql.com/pricing)
  * [Rover CLI](https://www.apollographql.com/docs/rover/)
* [graphql-yoga](https://github.com/dotansimha/graphql-yoga)

## General Purpose (Monitoring, Clustering, CI/CD)

* [Husky](https://www.npmjs.com/package/husky)
* [Sentry](https://sentry.io/welcome/)
* [Webpack](https://webpack.github.io/)

## Guidelines & Examples

* [Domain: don't ignore errors](https://nodejs.org/docs/latest/api/domain.html#domain_warning_don_t_ignore_errors)

## Immutability

* [Immer](https://immerjs.github.io/immer/)
* [immutable.js](https://github.com/immutable-js/immutable-js)

## Networking

* [http-errors](https://github.com/jshttp/http-errors) 
* [response-time](https://github.com/expressjs/response-time)
* [rid](https://github.com/node-modules/rid) - request unique id

## Security

* [csp-header](https://github.com/frux/csp/tree/master/packages/csp-header#readme) - Content-Security-Policy header generator

## Testing

* [Jest](https://jestjs.io/)
* [Mocha](https://mochajs.org/)

## Worth Mentioning

* [safe-regex](https://www.npmjs.com/package/safe-regex) - detect potentially catastrophic exponential-time regular expressions
* [vuln-regex-detector](https://github.com/davisjam/vuln-regex-detector) - detect regexes that could lead to catastrophic backtracking

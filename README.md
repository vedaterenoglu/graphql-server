# GraphQL Server

>  **A simple, straight forward guide to building a GraphQL server with Apollo Server.**

## About this repository

[![Donate](https://img.shields.io/badge/paypal-donate-179BD7.svg)](https://www.paypal.me/vedaterenoglu)

[![MIT license](http://img.shields.io/badge/license-MIT-lightgrey.svg)](http://opensource.org/licenses/MIT)


This repository is the example application for the [_Getting Started_ guide](https://www.apollographql.com/docs/apollo-server/v2/getting-started.html) in the Apollo Server documentation.

## This project uses the followings:
* [**A**pollo Server](https://www.apollographql.com/docs/apollo-server/): backend framework
* [**G**raphQL](https://graphql.org/): GraphQL as a query language for API
* [**N**ode.js](https://nodejs.org): runtime environment

Other tools and technologies used:
* [Babel](https://babeljs.io/docs/en/): It is used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.

## Prerequisites

* Install [Node.js](https://nodejs.org)
* Clone this repository: `git clone git@github.com:vedaterenoglu/graphql-server.git`
* `cd graphql-server` change the directory to the app folder and run the following commands:

```js
// Install the dependecies

npm i
```
* Run
### Development mode
```js
// run in development mode

npm start
```

* Open your browser and see the server running on `localhost:4000/graphql` with the GraphQL playground.

```js
// write the qury in playground window to get the results

{
  books  {
    title
  }
}
```

![screen shot 2018-08-29 at 21 02 00](https://user-images.githubusercontent.com/38211466/44809982-9bc92c80-abd0-11e8-9b8a-56a6cc8072a2.png)

```js
// write the qury in playground window to get the results

{
  books  {
    title
    author
    type
  }
}
```

![screen shot 2018-08-29 at 21 03 55](https://user-images.githubusercontent.com/38211466/44810044-c5825380-abd0-11e8-94e9-8e96dca58955.png)

## Documentation

Check out the [official Apollo Server documentation](https://www.apollographql.com/docs/apollo-server/v2/) for more information.

## Please open an issue if
* you have any suggestion to improve this project
* you noticed any problem or error

## Wiki
To get more help about this project, [visit the official wiki](#).

### Author
![Vedat Erenoglu](https://s.gravatar.com/avatar/0e529b095e48c12b9834e4d6ec081dc3?s=80)
* [Vedat Erenoglu](https://github.com/VedatErenoglu)
### e-mail:
* info@vedaterenoglu.com
### Linkedin Profile
* https://www.linkedin.com/in/vedaterenoglu/
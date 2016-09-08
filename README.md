# express-webpack-bootstrap Starter Kit

Starter Kit for Express Webpack and Bootstrap Application including SCSS.

  - Express
  - Handlebars
  - Webpack
  - Babel (es6)
  - SCSS
  - ESlint using Airbnb Configuration.
  - Asset Fingerprinting

Entry point for Webpack is:

```
scripts/site.js
```

In order to run the application:

First install node modules

```
$ npm install
```

Then using 2 terminals, run the following:

```
$ npm run watch
$ nodemon server
```

For production, build the assets and start the server

```
$ npm run prod
```

By default, this will start up on

```
http://localhost:3010
```
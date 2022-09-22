## Welcome to Be Present!

Be Present is a social platform designed for users to connect with friends and receive recommendations for gifts based on their interests.

This project was built using Vue.js and connects to our backend server using axios, the link to the back end can be found here:

https://github.com/RichardNeat/backend-be-present

This front end utilises a web scraper built using axios and cheerio to retrieve product data from https://www.etsy.com/ and present suggestions to the user based on the interests that they have selected.

## Hosted Version Link

https://be-present.netlify.app/?#/

## Project setup

By default, 'npm install' will install all dependencies in the package.json file. In this case this will install:

    "axios": "^0.27.2",
    "cheerio": "^1.0.0-rc.12",
    "core-js": "^3.8.3",
    "vue": "^3.2.13",
    "vue-router": "^4.0.3",
    "@vue/cli-plugin-babel": "~5.0.0",
    "@vue/cli-plugin-router": "~5.0.0",
    "@vue/cli-service": "~5.0.0"

### Compiles and hot-reloads for development

npm run serve

### Compiles and minifies for production

npm run build

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).


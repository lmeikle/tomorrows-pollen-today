<h1 align="center">
  <a href="https://tomorrowspollen.today">
    <img src="/public/images/logo.svg" width="20%" alt="Tomorrow's Pollen Today">
  </a>
  <br>
  Tomorrow's Pollen Today
  <br>
  <br>
</h1>

[![JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![Build Status](https://travis-ci.org/Tomorrows-pollen-today/tomorrows-pollen-today.svg?branch=master)](https://travis-ci.org/Tomorrows-pollen-today/tomorrows-pollen-today)

# Usage

1. Install dependencies with `npm install`
2. Create a `.env` file and fill out the following:
   * `PREDICTOR_URL` : The url for the pollen prediction service
   * `API_KEY` : The API key for the pollen prediction service
   * `NODE_ENV` : The environment that this webservice runs in. Valid values are:
     * `'development'`
     * `'production'`
3. Test using `npm test`
4. Run using `npm start`

# License

[MIT](/LICENSE)

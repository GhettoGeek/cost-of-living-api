# Cost of Living API

> Unofficial [Numbeo Cost of Living](https://www.numbeo.com/cost-of-living/) JSON API

To access our API, if you want to use http connection please use URL prefix http://www.numbeo.com:8008/api/ (this might not work in a browser that uses HSTS while it should work in command line clients such as wget or curl). If you want to use secure https connection please use URL prefix https://www.numbeo.com/api/

## Getting Started

First, install dependencies:

```sh
npm install
```

Then run the application in development mode:

```sh
npm run dev
```

## API

### `/:city?currency`

Returns the cost of different items in the requested city. Return an empty array of costs if there is not city data available.

#### Params

##### `city`

The city for which you want to retrieve cost-of-living data for

#### Query

##### `currency`

The three letter currency code for the currency you want values in. Defaults to CAD.

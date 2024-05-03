# Swagger UI Electron Desktop App

A sample desktop app for Swagger UI for your OpenAPI definitions online and offline.

## Usage

Add your OpenAPI definition file paths/URLs to the list on `index.html`.

```javascript
// if url is specified dropdown on top bar is removed
// url: 'https://petstore3.swagger.io/api/v3/openapi.json',
urls: [
    {
        url: 'api-files/openapi_openweathermap.yml',
        name: 'OpenWeatherMap API (Local file)',
    },
    {
        url: 'api-files/petstore.yaml',
        name: 'Petstore API (Local file)',
    },
    {
        url: 'https://petstore3.swagger.io/api/v3/openapi.json',
        name: 'Petstore API',
    },
],
```

Run your app.

```sh
npm install
npm start
```

## Installation

To install prebuilt Electron binaries, use [`npm`](https://docs.npmjs.com/).
The preferred method is to install Electron as a development dependency in your
app:

```sh
npm install
```

## Run

```sh
npm start
```

## Build

```sh
npm run dist:windows
```

## Cross platform build

```sh
docker-compose up
```

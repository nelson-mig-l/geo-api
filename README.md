# geo-api

## Setup

* `pip install -r requirements.txt`
* update geo-api-config.yml server.url: to https://musical-waddle-r9pj9xrjjw357vw-5000.app.github.dev/openapi
* `export PYGEOAPI_CONFIG=geo-api-config.yml`
* `export PYGEOAPI_OPENAPI=geo-api-openapi.yml`
* `pygeoapi openapi generate $PYGEOAPI_CONFIG > $PYGEOAPI_OPENAPI`

## Reconfigure

* `export PYGEOAPI_CONFIG=geo-api-config.yml`
* `export PYGEOAPI_OPENAPI=geo-api-openapi.yml`
* `pygeoapi openapi generate $PYGEOAPI_CONFIG > $PYGEOAPI_OPENAPI`

## Launch

* `export PYGEOAPI_CONFIG=geo-api-config.yml`
* `flask --app main run`

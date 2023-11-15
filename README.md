# geo-api

## Setup

* `pip install -r requirements.txt`
* update geo-api-config.yml server.url: to https://dados.bazurl.com/openapi
* `export PYGEOAPI_CONFIG=geo-api-config.yml`
* `export PYGEOAPI_OPENAPI=geo-api-openapi.yml`
* `pygeoapi openapi generate $PYGEOAPI_CONFIG > $PYGEOAPI_OPENAPI`

## Reconfigure

* `export PYGEOAPI_CONFIG=geo-api-config.yml`
* `export PYGEOAPI_OPENAPI=geo-api-openapi.yml`
* `pygeoapi openapi generate $PYGEOAPI_CONFIG > $PYGEOAPI_OPENAPI`
* `passenger-config restart-app ~`

## Launch

* `export PYGEOAPI_CONFIG=geo-api-config.yml`
* `flask --app main run`

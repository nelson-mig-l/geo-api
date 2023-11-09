# geo-api

* `pip install -r requirements.txt`
* update geo-api-config.yml server.url: to https://musical-waddle-r9pj9xrjjw357vw-5000.app.github.dev/oapi
* `export PYGEOAPI_CONFIG=geo-api-config.yml`
* `export PYGEOAPI_OPENAPI=geo-api-openapi.yml`
* `pygeoapi openapi generate $PYGEOAPI_CONFIG > $PYGEOAPI_OPENAPI`
* `flask --app main run`
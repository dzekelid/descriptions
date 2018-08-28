swagger: "2.0"
x-collection-name: Crypto Compare
x-complete: 1
info:
  title: Cryptocompare
  description: todo-add-description
  version: 1.0.0
host: min-api.cryptocompare.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:
    get:
      summary: API Description
      description: Api description.
      operationId: UnnammedEndpointGet
      x-api-path-slug: get
      responses:
        200:
          description: OK
      tags:
      - Discovery
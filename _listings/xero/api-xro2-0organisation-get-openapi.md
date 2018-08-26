---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Xero oAuth 1a Organisation
  description: 'TODO: Add Description'
  version: 1.0.0
host: api.xero.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api.xro/2.0/Organisation:
    get:
      summary: Organisation
      description: 'TODO: Add Description'
      operationId: ApiXro20OrganisationGet
      x-api-path-slug: api-xro2-0organisation-get
      parameters:
      - in: header
        name: accept
      responses:
        200:
          description: OK
      tags:
      - ""
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
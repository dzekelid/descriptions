---
swagger: "2.0"
x-collection-name: Xero
x-complete: 1
info:
  title: Xero oAuth 1a
  description: a-collection-to-authenticate-to-the-xero-api-using-oauth1-0a
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
---
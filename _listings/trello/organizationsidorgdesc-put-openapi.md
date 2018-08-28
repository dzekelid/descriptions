---
swagger: "2.0"
x-collection-name: Trello
x-complete: 0
info:
  title: Trello Put Organizations Desc
  description: Put organizations desc.
  termsOfService: https://trello.com/legal
  contact:
    name: Trello
    url: https://trello.com/home
  version: "1.0"
host: trello.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /boards/{idBoard}/desc:
    put:
      summary: Put Boards Desc
      description: Put boards desc.
      operationId: updateBoardsDescByIdBoard
      x-api-path-slug: boardsidboarddesc-put
      parameters:
      - in: body
        name: body
        description: Attributes of Boards Desc to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Desc
  /cards/{idCard}/desc:
    put:
      summary: Put Cards Desc
      description: Put cards desc.
      operationId: updateCardsDescByIdCard
      x-api-path-slug: cardsidcarddesc-put
      parameters:
      - in: body
        name: body
        description: Attributes of Cards Desc to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idCard
        description: card id or shortlink
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Cards
      - Desc
  /organizations/{idOrg}/desc:
    put:
      summary: Put Organizations Desc
      description: Put organizations desc.
      operationId: updateOrganizationsDescByIdOrg
      x-api-path-slug: organizationsidorgdesc-put
      parameters:
      - in: body
        name: body
        description: Attributes of Organizations Desc to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idOrg
        description: idOrg or name
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Desc
  /webhooks/{idWebhook}/description:
    put:
      summary: Put Webhooks Description
      description: Put webhooks description.
      operationId: updateWebhooksDescriptionByIdWebhook
      x-api-path-slug: webhooksidwebhookdescription-put
      parameters:
      - in: body
        name: body
        description: Attributes of Webhooks Description to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idWebhook
        description: idWebhook
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Webhooks
      - Description
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
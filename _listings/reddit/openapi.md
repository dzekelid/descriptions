swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /multi/multipath/description:
    get&nbsp;:
      summary: Get Multi Multipath Description
      description: Get a multi&#39;s description.
      operationId: get&nbsp;MultiMultipathDescription
      x-api-path-slug: multimultipathdescription-getnbsp
      parameters:
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Description
    put&nbsp;:
      summary: Put Multi Multipath Description
      description: Change a multi&#39;s markdown description.
      operationId: put&nbsp;MultiMultipathDescription
      x-api-path-slug: multimultipathdescription-putnbsp
      parameters:
      - in: query
        name: model
        description: 'json data:{  &quot;body_md&quot;: raw markdown text,}'
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Description
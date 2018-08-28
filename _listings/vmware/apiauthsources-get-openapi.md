---
swagger: "2.0"
x-collection-name: VMWare
x-complete: 0
info:
  title: VMWare vRealize Operations Get Auth Sources
  description: 'TODO: Add Description'
  version: 1.0.0
host: example.com
basePath: /suite-api/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /adapters:
    get:
      summary: Get An Adapter Instance(s) of Type (Kind)
      description: 'TODO: Add Description'
      operationId: AdaptersGet
      x-api-path-slug: adapters-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: adapterKindKey
      responses:
        200:
          description: OK
      tags:
      - Adapters
  /api/adapterkinds:
    get:
      summary: Get Adapter Types (Kinds)
      description: 'TODO: Add Description'
      operationId: ApiAdapterkindsGet
      x-api-path-slug: apiadapterkinds-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Adapterkinds
  /api/adapters:
    get:
      summary: Get Adapter Instances
      description: 'TODO: Add Description'
      operationId: ApiAdaptersGet
      x-api-path-slug: apiadapters-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Adapters
  /api/alertdefinitions/{alertDefinitionId}:
    get:
      summary: Get Alert Definition
      description: 'TODO: Add Description'
      operationId: ApiAlertdefinitionsByAlertDefinitionIdGet
      x-api-path-slug: apialertdefinitionsalertdefinitionid-get
      parameters:
      - in: header
        name: Accept
      - in: path
        name: alertDefinitionId
      responses:
        200:
          description: OK
      tags:
      - Alertdefinitions
      - AlertDefinitionId
  /api/alerts/7c2a4f9a-fd04-4300-b85c-cda555782e86:
    get:
      summary: Get Alert
      description: 'TODO: Add Description'
      operationId: ApiAlerts7c2a4f9aFd044300B85cCda555782e86Get
      x-api-path-slug: apialerts7c2a4f9afd044300b85ccda555782e86-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Alerts
  /api/alerts/query:
    post:
      summary: Query Alerts
      description: 'TODO: Add Description'
      operationId: ApiAlertsQueryPost
      x-api-path-slug: apialertsquery-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - Query
  /api/auth/sources:
    get:
      summary: Get Auth Sources
      description: 'TODO: Add Description'
      operationId: ApiAuthSourcesGet
      x-api-path-slug: apiauthsources-get
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Sources
  /api/auth/token/acquire:
    post:
      summary: RUN FIRST - Get vR Ops Auth Token
      description: 'TODO: Add Description'
      operationId: ApiAuthTokenAcquirePost
      x-api-path-slug: apiauthtokenacquire-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Token
      - Acquire
  /api/auth/users:
    post:
      summary: Create Local User
      description: 'TODO: Add Description'
      operationId: ApiAuthUsersPost
      x-api-path-slug: apiauthusers-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Users
  /api/resources/adapters/{adapterInstanceId}:
    post:
      summary: Create an EPOPS Unix MultiProcess Monitor Resource
      description: 'TODO: Add Description'
      operationId: ApiResourcesAdaptersByAdapterInstanceIdPost3
      x-api-path-slug: apiresourcesadaptersadapterinstanceid-post
      parameters:
      - in: header
        name: Accept
      - in: path
        name: adapterInstanceId
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Resources
      - Adapters
      - AdapterInstanceId
  /api/resources/query:
    post:
      summary: Get Resources
      description: 'TODO: Add Description'
      operationId: ApiResourcesQueryPost
      x-api-path-slug: apiresourcesquery-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Resources
      - Query
  /api/resources/{agentResourceId}/relationships:
    get:
      summary: Get OS Resource ID and Save
      description: 'TODO: Add Description'
      operationId: ApiResourcesRelationshipsByAgentResourceIdGet
      x-api-path-slug: apiresourcesagentresourceidrelationships-get
      parameters:
      - in: header
        name: Accept
      - in: path
        name: agentResourceId
      responses:
        200:
          description: OK
      tags:
      - Resources
      - AgentResourceId
      - Relationships
  /api/resources/{epopsMonitorResourceId}/monitoringstate/start:
    put:
      summary: Start Monitoring a Resource
      description: 'TODO: Add Description'
      operationId: ApiResourcesMonitoringstateStartByEpopsMonitorResourceIdPut
      x-api-path-slug: apiresourcesepopsmonitorresourceidmonitoringstatestart-put
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: epopsMonitorResourceId
      responses:
        200:
          description: OK
      tags:
      - Resources
      - EpopsMonitorResourceId
      - Monitoringstate
      - Start
  /api/resources/{resourceId}/properties:
    get:
      summary: Get Properties of a Resource
      description: 'TODO: Add Description'
      operationId: ApiResourcesPropertiesByResourceIdGet
      x-api-path-slug: apiresourcesresourceidproperties-get
      parameters:
      - in: path
        name: resourceId
      responses:
        200:
          description: OK
      tags:
      - Resources
      - ResourceId
      - Properties
    post:
      summary: Add or Update Properties of a Resource
      description: 'TODO: Add Description'
      operationId: ApiResourcesPropertiesByResourceIdPost
      x-api-path-slug: apiresourcesresourceidproperties-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: resourceId
      responses:
        200:
          description: OK
      tags:
      - Resources
      - ResourceId
      - Properties
  /api/resources/{resourceId}/stats:
    post:
      summary: Add or Update Stats of a Resource
      description: 'TODO: Add Description'
      operationId: ApiResourcesStatsByResourceIdPost
      x-api-path-slug: apiresourcesresourceidstats-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: resourceId
      responses:
        200:
          description: OK
      tags:
      - Resources
      - ResourceId
      - Stats
  /api/symptoms/query:
    post:
      summary: Query Symptoms
      description: 'TODO: Add Description'
      operationId: ApiSymptomsQueryPost
      x-api-path-slug: apisymptomsquery-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Symptoms
      - Query
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
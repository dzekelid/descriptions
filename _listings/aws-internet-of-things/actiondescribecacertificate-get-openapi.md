---
swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 0
info:
  title: AWS Internet of Things API Describe C A Certificate
  version: 1.0.0
  description: Describes a registered CA certificate.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeCACertificate:
    get:
      summary: Describe C A Certificate
      description: Describes a registered CA certificate.
      operationId: describeCACertificate
      x-api-path-slug: actiondescribecacertificate-get
      parameters:
      - in: query
        name: certificateId
        description: The CA certificate identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - CA Certificates
  /?Action=DescribeCertificate:
    get:
      summary: Describe Certificate
      description: Gets information about the specified certificate.
      operationId: describeCertificate
      x-api-path-slug: actiondescribecertificate-get
      parameters:
      - in: query
        name: certificateId
        description: The ID of the certificate
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificates
  /?Action=DescribeEndpoint:
    get:
      summary: Describe Endpoint
      description: Returns a unique endpoint specific to the AWS account making the
        call.
      operationId: describeEndpoint
      x-api-path-slug: actiondescribeendpoint-get
      parameters:
      - in: query
        name: endpointAddress
        description: The endpoint
        type: string
      responses:
        200:
          description: OK
      tags:
      - Endpoints
  /?Action=DescribeThing:
    get:
      summary: Describe Thing
      description: Gets information about the specified thing.
      operationId: describeThing
      x-api-path-slug: actiondescribething-get
      parameters:
      - in: query
        name: thingName
        description: The name of the thing
        type: string
      responses:
        200:
          description: OK
      tags:
      - Things
  /?Action=DescribeThingType:
    get:
      summary: Describe Thing Type
      description: Gets information about the specified thing type.
      operationId: describeThingType
      x-api-path-slug: actiondescribethingtype-get
      parameters:
      - in: query
        name: thingTypeName
        description: The name of the thing type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Thing Types
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
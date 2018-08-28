---
swagger: "2.0"
x-collection-name: AWS Elasticsearch Service
x-complete: 0
info:
  title: Amazon Elasticsearch Service API Describe Elasticsearch Domain
  version: 1.0.0
  description: |-
    Describes the domain configuration for the specified Amazon ES domain, including the
                    domain ID, domain service endpoint, and domain ARN. Use the HTTP GET
                    method with this operation.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2015-01-01/es/domain-info:
    post:
      summary: Describe Elasticsearch Domains
      description: |-
        Describes the domain configuration for up to five specified Amazon ES domains.
                        Information includes the domain ID, domain service endpoint, and domain ARN. Use the
                        HTTP POST method with this operation.
      operationId: describeElasticsearchDomains
      x-api-path-slug: 20150101esdomaininfo-post
      parameters:
      - in: body
        name: DomainNames
        description: Array of Amazon ES domains in the following                                            format:{DomainNames:[&lt;Domain_Name&gt;,&lt;Domain_Name&gt;
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Domains
  /2015-01-01/es/domain/{domain_name}:
    get:
      summary: Describe Elasticsearch Domain
      description: |-
        Describes the domain configuration for the specified Amazon ES domain, including the
                        domain ID, domain service endpoint, and domain ARN. Use the HTTP GET
                        method with this operation.
      operationId: describeElasticsearchDomain
      x-api-path-slug: 20150101esdomaindomain-name-get
      parameters:
      - in: query
        name: DomainName
        description: Name of the Amazon ES domain that you want to                                        describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
  /2015-01-01/es/domain/{domain_name}/config:
    get:
      summary: Describe Elasticsearch Domain Config
      description: |-
        Displays the configuration of an Amazon ES domain. Use the HTTP GET method
                        with this operation.
      operationId: describeElasticsearchDomainConfig
      x-api-path-slug: 20150101esdomaindomain-nameconfig-get
      parameters:
      - in: query
        name: DomainName
        description: Name of the Amazon ES domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
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
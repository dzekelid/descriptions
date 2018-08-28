swagger: "2.0"
x-collection-name: AWS Elasticsearch Service
x-complete: 1
info:
  title: AWS Elasticsearch Service API
  version: 1.0.0
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
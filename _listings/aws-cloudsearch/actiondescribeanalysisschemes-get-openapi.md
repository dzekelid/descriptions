---
swagger: "2.0"
x-collection-name: AWS CloudSearch
x-complete: 0
info:
  title: AWS CloudSearch Describe Analysis Schemes
  version: 1.0.0
  description: Gets the analysis schemes configured for a domain.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAnalysisSchemes:
    get:
      summary: Describe Analysis Schemes
      description: Gets the analysis schemes configured for a domain.
      operationId: DescribeAnalysisSchemes
      x-api-path-slug: actiondescribeanalysisschemes-get
      parameters:
      - in: query
        name: AnalysisSchemeNames.member.N
        description: The analysis schemes you want to describe
        type: string
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Analysis Scheme
  /?Action=DescribeAvailabilityOptions:
    get:
      summary: Describe Availability Options
      description: Gets the availability options configured for a domain.
      operationId: DescribeAvailabilityOptions
      x-api-path-slug: actiondescribeavailabilityoptions-get
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Availability Options
  /?Action=DescribeDomains:
    get:
      summary: Describe Domains
      description: Gets information about the search domains owned by this account.
      operationId: DescribeDomains
      x-api-path-slug: actiondescribedomains-get
      parameters:
      - in: query
        name: DomainNames.member.N
        description: The names of the domains you want to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
  /?Action=DescribeExpressions:
    get:
      summary: Describe Expressions
      description: Gets the expressions configured for the search domain.
      operationId: DescribeExpressions
      x-api-path-slug: actiondescribeexpressions-get
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      - in: query
        name: ExpressionNames.member.N
        description: Limits the                         DescribeExpressions                      response
          to the specified expressions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Expressions
  /?Action=DescribeIndexFields:
    get:
      summary: Describe Index Fields
      description: Gets information about the index fields configured for the search
        domain.
      operationId: DescribeIndexFields
      x-api-path-slug: actiondescribeindexfields-get
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      - in: query
        name: FieldNames.member.N
        description: A list of the index fields you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Index Fields
  /?Action=DescribeScalingParameters:
    get:
      summary: Describe Scaling Parameters
      description: Gets the scaling parameters configured for a domain.
      operationId: DescribeScalingParameters
      x-api-path-slug: actiondescribescalingparameters-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Scaling Parameters
  /?Action=DescribeServiceAccessPolicies:
    get:
      summary: Describe Service Access Policies
      description: Gets information about the access policies that control access
        to the domain's document and search endpoints.
      operationId: DescribeServiceAccessPolicies
      x-api-path-slug: actiondescribeserviceaccesspolicies-get
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Access Policies
  /?Action=DescribeSuggesters:
    get:
      summary: Describe Suggesters
      description: Gets the suggesters configured for a domain.
      operationId: DescribeSuggesters
      x-api-path-slug: actiondescribesuggesters-get
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      - in: query
        name: SuggesterNames.member.N
        description: The suggesters you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Suggesters
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
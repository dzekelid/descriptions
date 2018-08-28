---
swagger: "2.0"
x-collection-name: AWS Service Catalog
x-complete: 0
info:
  title: AWS Service Catalog API Describe Product View
  version: 1.0.0
  description: Retrieves information about a specified product.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeConstraint:
    get:
      summary: Describe Constraint
      description: Retrieves detailed information for a specified constraint.
      operationId: describeConstraint
      x-api-path-slug: actiondescribeconstraint-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the constraint
        type: string
      responses:
        200:
          description: OK
      tags:
      - Constraints
  /?Action=DescribePortfolio:
    get:
      summary: Describe Portfolio
      description: |-
        Retrieves detailed information and any tags associated with the specified
                 portfolio.
      operationId: describePortfolio
      x-api-path-slug: actiondescribeportfolio-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the portfolio for which to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Portfolios
  /?Action=DescribeProduct:
    get:
      summary: Describe Product
      description: Retrieves information about a specified product.
      operationId: describeProduct
      x-api-path-slug: actiondescribeproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The ProductId of the product to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProductAsAdmin:
    get:
      summary: Describe Product As Admin
      description: |-
        Retrieves information about a specified product, run with administrator
                 access.
      operationId: describeProductAsAdmin
      x-api-path-slug: actiondescribeproductasadmin-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the product for which to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProductView:
    get:
      summary: Describe Product View
      description: Retrieves information about a specified product.
      operationId: describeProductView
      x-api-path-slug: actiondescribeproductview-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The ProductViewId of the product to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProvisioningArtifact:
    get:
      summary: Describe Provisioning Artifact
      description: Retrieves detailed information about the specified provisioning
        artifact.
      operationId: describeProvisioningArtifact
      x-api-path-slug: actiondescribeprovisioningartifact-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: ProvisioningArtifactId
        description: The identifier of the provisioning artifact
        type: string
      responses:
        200:
          description: OK
      tags:
      - Provisioning Artifacts
  /?Action=DescribeProvisioningParameters:
    get:
      summary: Describe Provisioning Parameters
      description: |-
        Provides information about parameters required to provision a specified product in a
                 specified manner.
      operationId: describeProvisioningParameters
      x-api-path-slug: actiondescribeprovisioningparameters-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: PathId
        description: The identifier of the path for this products provisioning
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: ProvisioningArtifactId
        description: The provisioning artifact identifier for this product
        type: string
      responses:
        200:
          description: OK
      tags:
      - Provisioning Parameters
  /?Action=DescribeRecord:
    get:
      summary: Describe Record
      description: Retrieves a paginated list of the full details of a specific request.
      operationId: describeRecord
      x-api-path-slug: actiondescriberecord-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The record identifier of the ProvisionedProduct object for which
          to retrieve output         information
        type: string
      - in: query
        name: PageSize
        description: The maximum number of items to return in the results
        type: string
      - in: query
        name: PageToken
        description: The page token of the first page retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Records
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
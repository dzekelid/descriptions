---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Describe Identity Usage
  version: 1.0.0
  description: Gets usage information for an identity, including number of datasets
    and data usage.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeDataset:
    get:
      summary: Describe Dataset
      description: Gets meta data about a dataset by identity and dataset name.
      operationId: describeDataset
      x-api-path-slug: actiondescribedataset-get
      parameters:
      - in: query
        name: DatasetName
        description: A string of up to 128 characters
        type: string
      - in: query
        name: IdentityId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Dataset
  /?Action=DescribeIdentity:
    get:
      summary: Describe Identity
      description: |-
        Returns metadata related to the given identity, including when the identity was
                 created and any associated linked logins.
      operationId: describeIdentity
      x-api-path-slug: actiondescribeidentity-get
      parameters:
      - in: query
        name: IdentityId
        description: A unique identifier in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identities
  /?Action=DescribeIdentityPool:
    get:
      summary: Describe Identity Pool
      description: |-
        Gets details about a particular identity pool, including the pool name, ID
                 description, creation date, and current number of users.
      operationId: describeIdentityPool
      x-api-path-slug: actiondescribeidentitypool-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=DescribeIdentityPoolUsage:
    get:
      summary: Describe Identity Pool Usage
      description: Gets usage details (for example, data storage) about a particular
        identity pool.
      operationId: describeIdentityPoolUsage
      x-api-path-slug: actiondescribeidentitypoolusage-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool Usage
  /?Action=DescribeIdentityUsage:
    get:
      summary: Describe Identity Usage
      description: Gets usage information for an identity, including number of datasets
        and data usage.
      operationId: describeIdentityUsage
      x-api-path-slug: actiondescribeidentityusage-get
      parameters:
      - in: query
        name: IdentityId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool Usage
  /?Action=DescribeUserImportJob:
    get:
      summary: Describe User Import Job
      description: Describes the user import job.
      operationId: describeUserImportJob
      x-api-path-slug: actiondescribeuserimportjob-get
      parameters:
      - in: query
        name: JobId
        description: The job ID for the user import job
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool that the users are being imported            into
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Imports
  /?Action=DescribeUserPool:
    get:
      summary: Describe User Pool
      description: |-
        Returns the configuration information and metadata of the specified user
                    pool.
      operationId: describeUserPool
      x-api-path-slug: actiondescribeuserpool-get
      parameters:
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pools
  /?Action=DescribeUserPoolClient:
    get:
      summary: Describe User Pool Client
      description: |-
        Client method for returning the configuration information and metadata of the
                    specified user pool client.
      operationId: describeUserPoolClient
      x-api-path-slug: actiondescribeuserpoolclient-get
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pool Clients
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
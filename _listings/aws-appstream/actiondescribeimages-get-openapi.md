---
swagger: "2.0"
x-collection-name: AWS AppStream
x-complete: 0
info:
  title: AWS AppStream 2.0 API Describe Images
  description: Describes the images.
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeFleets:
    get:
      summary: Describe Fleets
      description: |-
        If fleet names are provided, this operation describes the specified fleets;
                    otherwise, all the fleets in the account are described.
      operationId: DescribeFleets
      x-api-path-slug: actiondescribefleets-get
      parameters:
      - in: query
        name: Names
        description: The fleet names to describe
        type: string
      - in: query
        name: NextToken
        description: The pagination token to use to retrieve the next page of results
          for this operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Fleet
  /?Action=DescribeImages:
    get:
      summary: Describe Images
      description: Describes the images.
      operationId: DescribeImages
      x-api-path-slug: actiondescribeimages-get
      parameters:
      - in: query
        name: Names
        description: A specific list of images to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Images
  /?Action=DescribeSessions:
    get:
      summary: Describe Sessions
      description: Describes the streaming sessions for a stack and a fleet.
      operationId: DescribeSessions
      x-api-path-slug: actiondescribesessions-get
      parameters:
      - in: query
        name: FleetName
        description: The name of the fleet for which to list sessions
        type: string
      - in: query
        name: Limit
        description: The size of each page of results
        type: string
      - in: query
        name: NextToken
        description: The pagination token to use to retrieve the next page of results
          for this operation
        type: string
      - in: query
        name: StackName
        description: The name of the stack for which to list sessions
        type: string
      - in: query
        name: UserId
        description: The user for whom to list sessions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sessions
  /?Action=DescribeStacks:
    get:
      summary: Describe Stacks
      description: |-
        If stack names are not provided, this operation describes the specified stacks;
                    otherwise, all stacks in the account are described.
      operationId: DescribeStacks
      x-api-path-slug: actiondescribestacks-get
      parameters:
      - in: query
        name: Names
        description: The stack names to describe
        type: string
      - in: query
        name: NextToken
        description: The pagination token to use to retrieve the next page of results
          for this operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stacks
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
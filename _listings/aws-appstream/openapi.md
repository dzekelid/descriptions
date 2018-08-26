---
swagger: "2.0"
x-collection-name: AWS AppStream
x-complete: 1
info:
  title: AWS AppStream 2.0 API
  description: amazon-appstream-2-0-is-a-fully-managed-secure-application-streaming-service-that-allows-you-to-stream-desktop-applications-from-aws-to-any-device-running-a-web-browser-without-rewriting-them--amazon-appstream-2-0-provides-users-instanton-access-to-the-applications-they-need-and-a-responsive-fluid-user-experience-on-the-device-of-their-choice-
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
---
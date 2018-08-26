---
swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 0
info:
  title: AWS Directory Service API Describe Conditional Forwarders
  version: 1.0.0
  description: Obtains information about the conditional forwarders for this account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeConditionalForwarders:
    get:
      summary: Describe Conditional Forwarders
      description: Obtains information about the conditional forwarders for this account.
      operationId: describeConditionalForwarders
      x-api-path-slug: actiondescribeconditionalforwarders-get
      parameters:
      - in: query
        name: DirectoryId
        description: The directory ID for which to get the list of associated conditional
          forwarders
        type: string
      - in: query
        name: RemoteDomainNames
        description: The fully qualified domain names (FQDN) of the remote domains
          for which to get the list of associated conditional forwarders
        type: string
      responses:
        200:
          description: OK
      tags:
      - Conditional Forwarder
  /?Action=DescribeDirectories:
    get:
      summary: Describe Directories
      description: Obtains information about the directories that belong to this account.
      operationId: describeDirectories
      x-api-path-slug: actiondescribedirectories-get
      parameters:
      - in: query
        name: DirectoryIds
        description: A list of identifiers of the directories for which to obtain
          the information
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return
        type: string
      - in: query
        name: NextToken
        description: The DescribeDirectoriesResult
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directories
  /?Action=DescribeEventTopics:
    get:
      summary: Describe Event Topics
      description: Obtains information about which SNS topics receive status messages
        from the specified directory.
      operationId: describeEventTopics
      x-api-path-slug: actiondescribeeventtopics-get
      parameters:
      - in: query
        name: DirectoryId
        description: The Directory ID for which to get the list of associated SNS
          topics
        type: string
      - in: query
        name: TopicNames
        description: A list of SNS topic names for which to obtain the information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Topics
  /?Action=DescribeSnapshots:
    get:
      summary: Describe Snapshots
      description: Obtains information about the directory snapshots that belong to
        this account.
      operationId: describeSnapshots
      x-api-path-slug: actiondescribesnapshots-get
      parameters:
      - in: query
        name: DirectoryId
        description: The identifier of the directory for which to retrieve snapshot
          information
        type: string
      - in: query
        name: Limit
        description: The maximum number of objects to return
        type: string
      - in: query
        name: NextToken
        description: The DescribeSnapshotsResult
        type: string
      - in: query
        name: SnapshotIds
        description: A list of identifiers of the snapshots to obtain the information
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=DescribeTrusts:
    get:
      summary: Describe Trusts
      description: Obtains information about the trust relationships for this account.
      operationId: describeTrusts
      x-api-path-slug: actiondescribetrusts-get
      parameters:
      - in: query
        name: DirectoryId
        description: The Directory ID of the AWS directory that is a part of the requested
          trust relationship
        type: string
      - in: query
        name: Limit
        description: The maximum number of objects to return
        type: string
      - in: query
        name: NextToken
        description: The DescribeTrustsResult
        type: string
      - in: query
        name: TrustIds
        description: A list of identifiers of the trust relationships for which to
          obtain the information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Trust
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
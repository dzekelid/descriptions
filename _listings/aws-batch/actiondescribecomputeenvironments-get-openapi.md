---
swagger: "2.0"
x-collection-name: AWS Batch
x-complete: 0
info:
  title: AWS Batch API Describe Compute Environments
  version: 1.0.0
  description: Describes one or more of your compute environments.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeComputeEnvironments:
    get:
      summary: Describe Compute Environments
      description: Describes one or more of your compute environments.
      operationId: describeComputeEnvironments
      x-api-path-slug: actiondescribecomputeenvironments-get
      parameters:
      - in: query
        name: computeEnvironments
        description: A list of up to 100 compute environment names or full Amazon
          Resource Name (ARN) entries
        type: string
      - in: query
        name: maxResults
        description: The maximum number of cluster results returned by            DescribeComputeEnvironments
          in paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated            DescribeComputeEnvironments
          request where maxResults was used         and the results exceeded the value
          of that parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compute Environment
  /?Action=DescribeJobDefinitions:
    get:
      summary: Describe Job Definitions
      description: Describes a list of job definitions.
      operationId: describeJobDefinitions
      x-api-path-slug: actiondescribejobdefinitions-get
      parameters:
      - in: query
        name: jobDefinitionName
        description: The name of the job definition to describe
        type: string
      - in: query
        name: jobDefinitions
        description: A space-separated list of up to 100 job definition names or full
          Amazon Resource Name (ARN)         entries
        type: string
      - in: query
        name: maxResults
        description: The maximum number of results returned by DescribeJobDefinitions
          in         paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated            DescribeJobDefinitions
          request where maxResults was used and         the results exceeded the value
          of that parameter
        type: string
      - in: query
        name: status
        description: The status with which to filter job definitions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Definitions
  /?Action=DescribeJobQueues:
    get:
      summary: Describe Job Queues
      description: Describes one or more of your job queues.
      operationId: describeJobQueues
      x-api-path-slug: actiondescribejobqueues-get
      parameters:
      - in: query
        name: jobQueues
        description: A list of up to 100 queue names or full queue Amazon Resource
          Name (ARN) entries
        type: string
      - in: query
        name: maxResults
        description: The maximum number of results returned by DescribeJobQueues in
          paginated         output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated            DescribeJobQueues
          request where maxResults was used and the         results exceeded the value
          of that parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Queue
  /?Action=DescribeJobs:
    get:
      summary: Describe Jobs
      description: Describes a list of AWS Batch jobs.
      operationId: describeJobs
      x-api-path-slug: actiondescribejobs-get
      parameters:
      - in: query
        name: jobs
        description: A space-separated list of up to 100 job IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Definitions
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
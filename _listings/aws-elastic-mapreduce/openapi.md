swagger: "2.0"
x-collection-name: AWS Elastic MapReduce
x-complete: 1
info:
  title: AWS Elastic MapReduce API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeCluster:
    get:
      summary: Describe Cluster
      description: Provides cluster-level details including status, hardware and software
        configuration, VPC settings, and so on.
      operationId: describeCluster
      x-api-path-slug: actiondescribecluster-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeJobFlows:
    get:
      summary: Describe Job Flows
      description: This API is deprecated and will eventually be removed.
      operationId: describeJobFlows
      x-api-path-slug: actiondescribejobflows-get
      parameters:
      - in: query
        name: CreatedAfter
        description: Return only job flows created after this date and time
        type: string
      - in: query
        name: CreatedBefore
        description: Return only job flows created before this date and time
        type: string
      - in: query
        name: JobFlowIds
        description: Return only job flows whose job flow ID is contained in this
          list
        type: string
      - in: query
        name: JobFlowStates
        description: Return only job flows whose state is contained in this list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Flows
  /?Action=DescribeSecurityConfiguration:
    get:
      summary: Describe Security Configuration
      description: Provides the details of a security configuration by returning the
        configuration JSON.
      operationId: describeSecurityConfiguration
      x-api-path-slug: actiondescribesecurityconfiguration-get
      parameters:
      - in: query
        name: Name
        description: The name of the security configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Configurations
  /?Action=DescribeStep:
    get:
      summary: Describe Step
      description: Provides more detail about the cluster step.
      operationId: describeStep
      x-api-path-slug: actiondescribestep-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster with steps to describe
        type: string
      - in: query
        name: StepId
        description: The identifier of the step to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Steps
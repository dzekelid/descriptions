---
swagger: "2.0"
x-collection-name: AWS EC2 Container Service
x-complete: 0
info:
  title: Amazon EC2 Container Service API Describe Container Instances
  version: 1.0.0
  description: Describes Amazon EC2 Container Service container instances.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeClusters:
    get:
      summary: Describe Clusters
      description: Describes one or more of your clusters.
      operationId: describeClusters
      x-api-path-slug: actiondescribeclusters-get
      parameters:
      - in: query
        name: clusters
        description: A space-separated list of up to 100 cluster names or full cluster
          Amazon Resource Name (ARN)            entries
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeContainerInstances:
    get:
      summary: Describe Container Instances
      description: Describes Amazon EC2 Container Service container instances.
      operationId: describeContainerInstances
      x-api-path-slug: actiondescribecontainerinstances-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that hosts the container instances            to describe
        type: string
      - in: query
        name: containerInstances
        description: A space-separated list of container instance IDs or full Amazon
          Resource Name (ARN)            entries
        type: string
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Instances
  /?Action=DescribeServices:
    get:
      summary: Describe Services
      description: Describes the specified services running in your cluster.
      operationId: describeServices
      x-api-path-slug: actiondescribeservices-get
      parameters:
      - in: query
        name: cluster
        description: The name of the cluster that hosts the service to describe
        type: string
      - in: query
        name: services
        description: A list of services to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Services
  /?Action=DescribeTaskDefinition:
    get:
      summary: Describe Task Definition
      description: Describes a task definition.
      operationId: describeTaskDefinition
      x-api-path-slug: actiondescribetaskdefinition-get
      parameters:
      - in: query
        name: taskDefinition
        description: The family for the latest ACTIVE revision,                family
          and revision (family:revision) for a            specific revision in the
          family, or full Amazon Resource Name (ARN) of the task definition to            describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Task Definitions
  /?Action=DescribeTasks:
    get:
      summary: Describe Tasks
      description: Describes a specified task or tasks.
      operationId: describeTasks
      x-api-path-slug: actiondescribetasks-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that hosts the task to describe
        type: string
      - in: query
        name: tasks
        description: A space-separated list of task IDs or full Amazon Resource Name
          (ARN) entries
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tasks
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
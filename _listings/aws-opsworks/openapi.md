---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAgentVersions:
    get:
      summary: Describe Agent Versions
      description: Describes the available AWS OpsWorks Stacks agent versions.
      operationId: describeAgentVersions
      x-api-path-slug: actiondescribeagentversions-get
      parameters:
      - in: query
        name: ConfigurationManager
        description: The configuration manager
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Agent
      - Versions
  /?Action=DescribeApps:
    get:
      summary: Describe Apps
      description: Requests a description of a specified set of apps.
      operationId: describeApps
      x-api-path-slug: actiondescribeapps-get
      parameters:
      - in: query
        name: AppIds
        description: An array of app IDs for the apps to be described
        type: string
      - in: query
        name: StackId
        description: The app stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Apps
  /?Action=DescribeCommands:
    get:
      summary: Describe Commands
      description: Describes the results of specified commands.
      operationId: describeCommands
      x-api-path-slug: actiondescribecommands-get
      parameters:
      - in: query
        name: CommandIds
        description: An array of command IDs
        type: string
      - in: query
        name: DeploymentId
        description: The deployment ID
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Commands
  /?Action=DescribeDeployments:
    get:
      summary: Describe Deployments
      description: Requests a description of a specified set of deployments.
      operationId: describeDeployments
      x-api-path-slug: actiondescribedeployments-get
      parameters:
      - in: query
        name: AppId
        description: The app ID
        type: string
      - in: query
        name: DeploymentIds
        description: An array of deployment IDs to be described
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Deployments
  /?Action=DescribeEcsClusters:
    get:
      summary: Describe Ecs Clusters
      description: Describes Amazon ECS clusters that are registered with a stack.
      operationId: describeEcsClusters
      x-api-path-slug: actiondescribeecsclusters-get
      parameters:
      - in: query
        name: EcsClusterArns
        description: A list of ARNs, one for each cluster to be described
        type: string
      - in: query
        name: MaxResults
        description: To receive a paginated response, use this parameter to specify
          the maximum number      of results to be returned with a single call
        type: string
      - in: query
        name: NextToken
        description: If the previous paginated request did not return all of the remaining
          results,      the response objectsNextToken parameter value is set to a
          token
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Ecs
      - Clusters
  /?Action=DescribeElasticLoadBalancers:
    get:
      summary: Describe Elastic Load Balancers
      description: Describes a stack's Elastic Load Balancing instances.
      operationId: describeElasticLoadBalancers
      x-api-path-slug: actiondescribeelasticloadbalancers-get
      parameters:
      - in: query
        name: LayerIds
        description: A list of layer IDs
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Elastic
      - Load
      - Balancers
  /?Action=DescribeInstances:
    get:
      summary: Describe Instances
      description: Requests a description of a set of instances.
      operationId: describeInstances
      x-api-path-slug: actiondescribeinstances-get
      parameters:
      - in: query
        name: InstanceIds
        description: An array of instance IDs to be described
        type: string
      - in: query
        name: LayerId
        description: A layer ID
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Instances
  /?Action=DescribeLayers:
    get:
      summary: Describe Layers
      description: Requests a description of one or more layers in a specified stack.
      operationId: describeLayers
      x-api-path-slug: actiondescribelayers-get
      parameters:
      - in: query
        name: LayerIds
        description: An array of layer IDs that specify the layers to be described
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Layers
  /?Action=DescribeLoadBasedAutoScaling:
    get:
      summary: Describe Load Based Auto Scaling
      description: Describes load-based auto scaling configurations for specified
        layers.
      operationId: describeLoadBasedAutoScaling
      x-api-path-slug: actiondescribeloadbasedautoscaling-get
      parameters:
      - in: query
        name: LayerIds
        description: An array of layer IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Load
      - Based
      - Auto
      - Scaling
  /?Action=DescribeMyUserProfile:
    get:
      summary: Describe My User Profile
      description: Describes a user's SSH information.
      operationId: describeMyUserProfile
      x-api-path-slug: actiondescribemyuserprofile-get
      parameters:
      - in: query
        name: UserProfile
        description: A UserProfile object that describes the users SSH information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - My
      - User
      - Profile
  /?Action=DescribePermissions:
    get:
      summary: Describe Permissions
      description: Describes the permissions for a specified stack.
      operationId: describePermissions
      x-api-path-slug: actiondescribepermissions-get
      parameters:
      - in: query
        name: IamUserArn
        description: The users IAM ARN
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Permissions
  /?Action=DescribeRaidArrays:
    get:
      summary: Describe Raid Arrays
      description: Describe an instance's RAID arrays.
      operationId: describeRaidArrays
      x-api-path-slug: actiondescriberaidarrays-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: RaidArrayIds
        description: An array of RAID array IDs
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Raid
      - Arrays
  /?Action=DescribeRdsDbInstances:
    get:
      summary: Describe Rds Db Instances
      description: Describes Amazon RDS instances.
      operationId: describeRdsDbInstances
      x-api-path-slug: actiondescriberdsdbinstances-get
      parameters:
      - in: query
        name: RdsDbInstanceArns
        description: An array containing the ARNs of the instances to be described
        type: string
      - in: query
        name: StackId
        description: The stack ID that the instances are registered with
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Rds
      - Db
      - Instances
  /?Action=DescribeServiceErrors:
    get:
      summary: Describe Service Errors
      description: Describes AWS OpsWorks Stacks service errors.
      operationId: describeServiceErrors
      x-api-path-slug: actiondescribeserviceerrors-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: ServiceErrorIds
        description: An array of service error IDs
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Service
      - Errors
  /?Action=DescribeStackProvisioningParameters:
    get:
      summary: Describe Stack Provisioning Parameters
      description: Requests a description of a stack's provisioning parameters.
      operationId: describeStackProvisioningParameters
      x-api-path-slug: actiondescribestackprovisioningparameters-get
      parameters:
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Stack
      - Provisioning
      - Parameters
  /?Action=DescribeStacks:
    get:
      summary: Describe Stacks
      description: Requests a description of one or more stacks.
      operationId: describeStacks
      x-api-path-slug: actiondescribestacks-get
      parameters:
      - in: query
        name: StackIds
        description: An array of stack IDs that specify the stacks to be described
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Stacks
  /?Action=DescribeStackSummary:
    get:
      summary: Describe Stack Summary
      description: |-
        Describes the number of layers and apps in a specified stack, and the number of instances in
              each state, such as running_setup or online.
      operationId: describeStackSummary
      x-api-path-slug: actiondescribestacksummary-get
      parameters:
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Stack
      - Summary
  /?Action=DescribeTimeBasedAutoScaling:
    get:
      summary: Describe Time Based Auto Scaling
      description: Describes time-based auto scaling configurations for specified
        instances.
      operationId: describeTimeBasedAutoScaling
      x-api-path-slug: actiondescribetimebasedautoscaling-get
      parameters:
      - in: query
        name: InstanceIds
        description: An array of instance IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Time
      - Based
      - Auto
      - Scaling
  /?Action=DescribeUserProfiles:
    get:
      summary: Describe User Profiles
      description: Describe specified users.
      operationId: describeUserProfiles
      x-api-path-slug: actiondescribeuserprofiles-get
      parameters:
      - in: query
        name: IamUserArns
        description: An array of IAM or federated user ARNs that identify the users
          to be described
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - User
      - Profiles
  /?Action=DescribeVolumes:
    get:
      summary: Describe Volumes
      description: Describes an instance's Amazon EBS volumes.
      operationId: describeVolumes
      x-api-path-slug: actiondescribevolumes-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: RaidArrayId
        description: The RAID array ID
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      - in: query
        name: VolumeIds
        description: Am array of volume IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Volumes
  /?Action=DescribeElasticIps:
    get:
      summary: Describes Elastic IPs
      description: Describes Elastic IPs
      operationId: describeElasticIps
      x-api-path-slug: actiondescribeelasticips-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: Ips
        description: An array of Elastic IP addresses to be described
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describes
      - Elastic
      - IP Addressess
---
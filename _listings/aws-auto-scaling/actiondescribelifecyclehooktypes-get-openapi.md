---
swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 0
info:
  title: AWS Auto Scaling API Describe Lifecycle Hook Types
  version: 1.0.0
  description: Describes the available types of lifecycle hooks.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAccountLimits:
    get:
      summary: Describe Account Limits
      description: Describes the current Auto Scaling resource limits for your AWS
        account.
      operationId: describeAccountLimits
      x-api-path-slug: actiondescribeaccountlimits-get
      parameters:
      - in: query
        name: MaxNumberOfAutoScalingGroups
        description: The maximum number of groups allowed for your AWS account
        type: string
      - in: query
        name: MaxNumberOfLaunchConfigurations
        description: The maximum number of launch configurations allowed for your
          AWS account
        type: string
      - in: query
        name: NumberOfAutoScalingGroups
        description: The current number of groups for your AWS account
        type: string
      - in: query
        name: NumberOfLaunchConfigurations
        description: The current number of launch configurations for your AWS account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Limits
  /?Action=DescribeAdjustmentTypes:
    get:
      summary: Describe Adjustment Types
      description: Describes the policy adjustment types for use with.
      operationId: describeAdjustmentTypes
      x-api-path-slug: actiondescribeadjustmenttypes-get
      parameters:
      - in: query
        name: AdjustmentTypes.member.N
        description: The policy adjustment types
        type: string
      responses:
        200:
          description: OK
      tags:
      - Adjustment Types
  /?Action=DescribeAutoScalingGroups:
    get:
      summary: Describe Auto Scaling Groups
      description: Describes one or more Auto Scaling groups.
      operationId: describeAutoScalingGroups
      x-api-path-slug: actiondescribeautoscalinggroups-get
      parameters:
      - in: query
        name: AutoScalingGroupNames.member.N
        description: The group names
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Groups
  /?Action=DescribeAutoScalingInstances:
    get:
      summary: Describe Auto Scaling Instances
      description: Describes one or more Auto Scaling instances.
      operationId: describeAutoScalingInstances
      x-api-path-slug: actiondescribeautoscalinginstances-get
      parameters:
      - in: query
        name: InstanceIds.member.N
        description: The instances to describe; up to 50 instance IDs
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Instances
  /?Action=DescribeAutoScalingNotificationTypes:
    get:
      summary: Describe Auto Scaling Notification Types
      description: Describes the notification types that are supported by Auto Scaling.
      operationId: describeAutoScalingNotificationTypes
      x-api-path-slug: actiondescribeautoscalingnotificationtypes-get
      parameters:
      - in: query
        name: AutoScalingNotificationTypes.member.N
        description: The notification types
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Notifications
  /?Action=DescribeLaunchConfigurations:
    get:
      summary: Describe Launch Configurations
      description: Describes one or more launch configurations.
      operationId: describeLaunchConfigurations
      x-api-path-slug: actiondescribelaunchconfigurations-get
      parameters:
      - in: query
        name: LaunchConfigurationNames.member.N
        description: The launch configuration names
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Launch
  /?Action=DescribeLifecycleHooks:
    get:
      summary: Describe Lifecycle Hooks
      description: Describes the lifecycle hooks for the specified Auto Scaling group.
      operationId: describeLifecycleHooks
      x-api-path-slug: actiondescribelifecyclehooks-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: LifecycleHookNames.member.N
        description: The names of one or more lifecycle hooks
        type: string
      responses:
        200:
          description: OK
      tags:
      - Life Cycle
  /?Action=DescribeLifecycleHookTypes:
    get:
      summary: Describe Lifecycle Hook Types
      description: Describes the available types of lifecycle hooks.
      operationId: describeLifecycleHookTypes
      x-api-path-slug: actiondescribelifecyclehooktypes-get
      parameters:
      - in: query
        name: LifecycleHookTypes.member.N
        description: The lifecycle hook types
        type: string
      responses:
        200:
          description: OK
      tags:
      - Life Cycle
  /?Action=DescribeLoadBalancers:
    get:
      summary: Describe Load Balancers
      description: Describes the load balancers for the specified Auto Scaling group.
      operationId: describeLoadBalancers
      x-api-path-slug: actiondescribeloadbalancers-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
  /?Action=DescribeLoadBalancerTargetGroups:
    get:
      summary: Describe Load Balancer Target Groups
      description: Describes the target groups for the specified Auto Scaling group.
      operationId: describeLoadBalancerTargetGroups
      x-api-path-slug: actiondescribeloadbalancertargetgroups-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
  /?Action=DescribeMetricCollectionTypes:
    get:
      summary: Describe Metric Collection Types
      description: Describes the available CloudWatch metrics for Auto Scaling.
      operationId: describeMetricCollectionTypes
      x-api-path-slug: actiondescribemetriccollectiontypes-get
      parameters:
      - in: query
        name: Granularities.member.N
        description: The granularities for the metrics
        type: string
      - in: query
        name: Metrics.member.N
        description: One or more metrics
        type: string
      responses:
        200:
          description: OK
      tags:
      - Metric Collection
  /?Action=DescribeNotificationConfigurations:
    get:
      summary: Describe Notification Configurations
      description: Describes the notification actions associated with the specified
        Auto Scaling group.
      operationId: describeNotificationConfigurations
      x-api-path-slug: actiondescribenotificationconfigurations-get
      parameters:
      - in: query
        name: AutoScalingGroupNames.member.N
        description: The name of the group
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Notifications
  /?Action=DescribePolicies:
    get:
      summary: Describe Policies
      description: Describes the policies for the specified Auto Scaling group.
      operationId: describePolicies
      x-api-path-slug: actiondescribepolicies-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to be returned with each call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: PolicyNames.member.N
        description: One or more policy names or policy ARNs to be described
        type: string
      - in: query
        name: PolicyTypes.member.N
        description: One or more policy types
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=DescribeScalingActivities:
    get:
      summary: Describe Scaling Activities
      description: Describes one or more scaling activities for the specified Auto
        Scaling group.
      operationId: describeScalingActivities
      x-api-path-slug: actiondescribescalingactivities-get
      parameters:
      - in: query
        name: ActivityIds.member.N
        description: The activity IDs of the desired scaling activities
        type: string
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Scaling Activities
  /?Action=DescribeScalingProcessTypes:
    get:
      summary: Describe Scaling Process Types
      description: Describes the scaling process types for use with.
      operationId: describeScalingProcessTypes
      x-api-path-slug: actiondescribescalingprocesstypes-get
      parameters:
      - in: query
        name: Processes.member.N
        description: The names of the process types
        type: string
      responses:
        200:
          description: OK
      tags:
      - Scaling Process
  /?Action=DescribeScheduledActions:
    get:
      summary: Describe Scheduled Actions
      description: Describes the actions scheduled for your Auto Scaling group that
        haven't run.
      operationId: describeScheduledActions
      x-api-path-slug: actiondescribescheduledactions-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: EndTime
        description: The latest scheduled start time to return
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: ScheduledActionNames.member.N
        description: Describes one or more scheduled actions
        type: string
      - in: query
        name: StartTime
        description: The earliest scheduled start time to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Scheduled Actions
  /?Action=DescribeTags:
    get:
      summary: Describe Tags
      description: Describes the specified tags.
      operationId: describeTags
      x-api-path-slug: actiondescribetags-get
      parameters:
      - in: query
        name: Filters.member.N
        description: A filter used to scope the tags to return
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DescribeTerminationPolicyTypes:
    get:
      summary: Describe Termination Policy Types
      description: Describes the termination policies supported by Auto Scaling.
      operationId: describeTerminationPolicyTypes
      x-api-path-slug: actiondescribeterminationpolicytypes-get
      parameters:
      - in: query
        name: TerminationPolicyTypes.member.N
        description: The termination policies supported by Auto Scaling (OldestInstance,
          OldestLaunchConfiguration,             NewestInstance, ClosestToNextInstanceHour,
          and Default)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Termination Policies
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
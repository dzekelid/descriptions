---
swagger: "2.0"
x-collection-name: AWS Elastic Load Balancing
x-complete: 0
info:
  title: AWS Elastic Load Balancing API Describe S S L Policies
  version: 1.0.0
  description: Describes the specified policies or all policies used for SSL negotiation.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeListeners:
    get:
      summary: Describe Listeners
      description: Describes the specified listeners or the listeners for the specified
        Application Load Balancer.
      operationId: describeListeners
      x-api-path-slug: actiondescribelisteners-get
      parameters:
      - in: query
        name: ListenerArns.member.N
        description: The Amazon Resource Names (ARN) of the listeners
        type: string
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Listeners
  /?Action=DescribeLoadBalancerAttributes:
    get:
      summary: Describe Load Balancer Attributes
      description: Describes the attributes for the specified Application Load Balancer.
      operationId: describeLoadBalancerAttributes
      x-api-path-slug: actiondescribeloadbalancerattributes-get
      parameters:
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
  /?Action=DescribeLoadBalancers:
    get:
      summary: Describe Load Balancers
      description: Describes the specified Application Load Balancers or all of your
        Application Load Balancers.
      operationId: describeLoadBalancers
      x-api-path-slug: actiondescribeloadbalancers-get
      parameters:
      - in: query
        name: LoadBalancerArns.member.N
        description: The Amazon Resource Names (ARN) of the load balancers
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Names.member.N
        description: The names of the load balancers
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
  /?Action=DescribeRules:
    get:
      summary: Describe Rules
      description: Describes the specified rules or the rules for the specified listener.
      operationId: describeRules
      x-api-path-slug: actiondescriberules-get
      parameters:
      - in: query
        name: ListenerArn
        description: The Amazon Resource Name (ARN) of the listener
        type: string
      - in: query
        name: RuleArns.member.N
        description: The Amazon Resource Names (ARN) of the rules
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
  /?Action=DescribeSSLPolicies:
    get:
      summary: Describe S S L Policies
      description: Describes the specified policies or all policies used for SSL negotiation.
      operationId: describeSSLPolicies
      x-api-path-slug: actiondescribesslpolicies-get
      parameters:
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Names.member.N
        description: The names of the policies
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      responses:
        200:
          description: OK
      tags:
      - SSL Policies
  /?Action=DescribeTags:
    get:
      summary: Describe Tags
      description: Describes the tags for the specified resources.
      operationId: describeTags
      x-api-path-slug: actiondescribetags-get
      parameters:
      - in: query
        name: ResourceArns.member.N
        description: The Amazon Resource Names (ARN) of the resources
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DescribeTargetGroupAttributes:
    get:
      summary: Describe Target Group Attributes
      description: Describes the attributes for the specified target group.
      operationId: describeTargetGroupAttributes
      x-api-path-slug: actiondescribetargetgroupattributes-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Target Groups
  /?Action=DescribeTargetGroups:
    get:
      summary: Describe Target Groups
      description: Describes the specified target groups or all of your target groups.
      operationId: describeTargetGroups
      x-api-path-slug: actiondescribetargetgroups-get
      parameters:
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Names.member.N
        description: The names of the target groups
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      - in: query
        name: TargetGroupArns.member.N
        description: The Amazon Resource Names (ARN) of the target groups
        type: string
      responses:
        200:
          description: OK
      tags:
      - Target Groups
  /?Action=DescribeTargetHealth:
    get:
      summary: Describe Target Health
      description: Describes the health of the specified targets or all of your targets.
      operationId: describeTargetHealth
      x-api-path-slug: actiondescribetargethealth-get
      parameters:
      - in: query
        name: TargetGroupArn
        description: The Amazon Resource Name (ARN) of the target group
        type: string
      - in: query
        name: Targets.member.N
        description: The targets
        type: string
      responses:
        200:
          description: OK
      tags:
      - Target Health
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
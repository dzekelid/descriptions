swagger: "2.0"
x-collection-name: AWS Step Functions
x-complete: 1
info:
  title: AWS Step Functions API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeActivity:
    get:
      summary: Describe Activity
      description: Describes an activity.
      operationId: describeActivity
      x-api-path-slug: actiondescribeactivity-get
      parameters:
      - in: query
        name: activityArn
        description: The Amazon Resource Name (ARN) of the activity to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activity
  /?Action=DescribeExecution:
    get:
      summary: Describe Execution
      description: Describes an execution.
      operationId: describeExecution
      x-api-path-slug: actiondescribeexecution-get
      parameters:
      - in: query
        name: executionArn
        description: The Amazon Resource Name (ARN) of the execution to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Execution
  /?Action=DescribeStateMachine:
    get:
      summary: Describe State Machine
      description: Describes a state machine.
      operationId: describeStateMachine
      x-api-path-slug: actiondescribestatemachine-get
      parameters:
      - in: query
        name: stateMachineArn
        description: The Amazon Resource Name (ARN) of the state machine to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - State Machine
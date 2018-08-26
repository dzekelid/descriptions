---
swagger: "2.0"
x-collection-name: AWS Shield
x-complete: 1
info:
  title: AWS Shield API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAttack:
    get:
      summary: Describe Attack
      description: Describes the details of a DDoS attack.
      operationId: describeAttack
      x-api-path-slug: actiondescribeattack-get
      parameters:
      - in: query
        name: AttackId
        description: The unique identifier (ID) for the attack that to be described
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attacks
  /?Action=DescribeProtection:
    get:
      summary: Describe Protection
      description: Lists the details of a.
      operationId: describeProtection
      x-api-path-slug: actiondescribeprotection-get
      parameters:
      - in: query
        name: ProtectionId
        description: The unique identifier (ID) for the Protection object that is         described
        type: string
      responses:
        200:
          description: OK
      tags:
      - Protection
  /?Action=DescribeSubscription:
    get:
      summary: Describe Subscription
      description: Provides details about the AWS Shield Advanced subscription for
        an account.
      operationId: describeSubscription
      x-api-path-slug: actiondescribesubscription-get
      parameters:
      - in: query
        name: Subscription
        description: The AWS Shield Advanced subscription details for an account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
---
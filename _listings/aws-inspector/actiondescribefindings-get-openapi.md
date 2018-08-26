---
swagger: "2.0"
x-collection-name: AWS Inspector
x-complete: 0
info:
  title: AWS Inspector API Describe Findings
  version: 1.0.0
  description: Describes the findings that are specified by the ARNs of the findings.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAssessmentRuns:
    get:
      summary: Describe Assessment Runs
      description: |-
        Describes the assessment runs that are specified by the ARNs of the assessment
                 runs.
      operationId: describeAssessmentRuns
      x-api-path-slug: actiondescribeassessmentruns-get
      parameters:
      - in: query
        name: assessmentRunArns
        description: The ARN that specifies the assessment run that you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assessment Runs
  /?Action=DescribeAssessmentTargets:
    get:
      summary: Describe Assessment Targets
      description: |-
        Describes the assessment targets that are specified by the ARNs of the assessment
                 targets.
      operationId: describeAssessmentTargets
      x-api-path-slug: actiondescribeassessmenttargets-get
      parameters:
      - in: query
        name: assessmentTargetArns
        description: The ARNs that specifies the assessment targets that you want
          to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assessment Targets
  /?Action=DescribeAssessmentTemplates:
    get:
      summary: Describe Assessment Templates
      description: |-
        Describes the assessment templates that are specified by the ARNs of the assessment
                 templates.
      operationId: describeAssessmentTemplates
      x-api-path-slug: actiondescribeassessmenttemplates-get
      parameters:
      - in: query
        name: assessmentTemplateArns
        description: 'Type: array of Strings'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assessment Templates
  /?Action=DescribeCrossAccountAccessRole:
    get:
      summary: Describe Cross Account Access Role
      description: |-
        Describes the IAM role that enables Amazon Inspector to access your AWS
                 account.
      operationId: describeCrossAccountAccessRole
      x-api-path-slug: actiondescribecrossaccountaccessrole-get
      parameters:
      - in: query
        name: registeredAt
        description: The date when the cross-account access role was registered
        type: string
      - in: query
        name: roleArn
        description: The ARN that specifies the IAM role that Amazon Inspector uses
          to access your AWS         account
        type: string
      - in: query
        name: valid
        description: A Boolean value that specifies whether the IAM role has the necessary
          policies         attached to enable Amazon Inspector to access your AWS
          account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cross Account Access Roles
  /?Action=DescribeFindings:
    get:
      summary: Describe Findings
      description: Describes the findings that are specified by the ARNs of the findings.
      operationId: describeFindings
      x-api-path-slug: actiondescribefindings-get
      parameters:
      - in: query
        name: findingArns
        description: The ARN that specifies the finding that you want to describe
        type: string
      - in: query
        name: locale
        description: The locale into which you want to translate a finding description,
          recommendation,         and the short description that identifies the finding
        type: string
      responses:
        200:
          description: OK
      tags:
      - Findings
  /?Action=DescribeResourceGroups:
    get:
      summary: Describe Resource Groups
      description: |-
        Describes the resource groups that are specified by the ARNs of the resource
                 groups.
      operationId: describeResourceGroups
      x-api-path-slug: actiondescriberesourcegroups-get
      parameters:
      - in: query
        name: resourceGroupArns
        description: The ARN that specifies the resource group that you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Resource Groups
  /?Action=DescribeRulesPackages:
    get:
      summary: Describe Rules Packages
      description: |-
        Describes the rules packages that are specified by the ARNs of the rules
                 packages.
      operationId: describeRulesPackages
      x-api-path-slug: actiondescriberulespackages-get
      parameters:
      - in: query
        name: locale
        description: The locale that you want to translate a rules package description
          into
        type: string
      - in: query
        name: rulesPackageArns
        description: The ARN that specifies the rules package that you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules Packages
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
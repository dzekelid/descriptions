---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 0
info:
  title: AWS Elastic Beanstalk API Describe Environment Managed Action History
  version: 1.0.0
  description: Lists an environment's completed and failed managed actions.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeApplications:
    get:
      summary: Describe Applications
      description: Returns the descriptions of existing applications.
      operationId: describeApplications
      x-api-path-slug: actiondescribeapplications-get
      parameters:
      - in: query
        name: ApplicationNames.member.N
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to only include      those with the specified names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DescribeApplicationVersions:
    get:
      summary: Describe Application Versions
      description: Retrieve a list of application versions.
      operationId: describeApplicationVersions
      x-api-path-slug: actiondescribeapplicationversions-get
      parameters:
      - in: query
        name: ApplicationName
        description: Specify an application name to show only application versions
          for that      application
        type: string
      - in: query
        name: MaxRecords
        description: Specify a maximum number of application versions to paginate
          in the request
        type: string
      - in: query
        name: NextToken
        description: Specify a next token to retrieve the next page in a paginated
          request
        type: string
      - in: query
        name: VersionLabels.member.N
        description: Specify a version label to show a specific application version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Application Version
  /?Action=DescribeConfigurationOptions:
    get:
      summary: Describe Configuration Options
      description: |-
        Describes the configuration options that are used in a particular configuration
              template or environment, or that a specified solution stack defines.
      operationId: describeConfigurationOptions
      x-api-path-slug: actiondescribeconfigurationoptions-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application associated with the configuration
          template or environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment whose configuration options you want
          to describe
        type: string
      - in: query
        name: Options.member.N
        description: If specified, restricts the descriptions to only the specified
          options
        type: string
      - in: query
        name: SolutionStackName
        description: The name of the solution stack whose configuration options you
          want to      describe
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template whose configuration options
          you want to      describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - ConfigurationOptions
  /?Action=DescribeConfigurationSettings:
    get:
      summary: Describe Configuration Settings
      description: |-
        Returns a description of the settings for the specified configuration set, that is,
              either a configuration template or the configuration set associated with a running
              environment.
      operationId: describeConfigurationSettings
      x-api-path-slug: actiondescribeconfigurationsettings-get
      parameters:
      - in: query
        name: ApplicationName
        description: The application for the environment or configuration template
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to describe
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Settings
  /?Action=DescribeEnvironmentHealth:
    get:
      summary: Describe Environment Health
      description: Returns information about the overall health of the specified environment.
      operationId: describeEnvironmentHealth
      x-api-path-slug: actiondescribeenvironmenthealth-get
      parameters:
      - in: query
        name: AttributeNames.member.N
        description: Specify the response elements to return
        type: string
      - in: query
        name: EnvironmentId
        description: Specify the environment by ID
        type: string
      - in: query
        name: EnvironmentName
        description: Specify the environment by name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeEnvironmentManagedActionHistory:
    get:
      summary: Describe Environment Managed Action History
      description: Lists an environment's completed and failed managed actions.
      operationId: describeEnvironmentManagedActionHistory
      x-api-path-slug: actiondescribeenvironmentmanagedactionhistory-get
      parameters:
      - in: query
        name: EnvironmentId
        description: The environment ID of the target environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the target environment
        type: string
      - in: query
        name: MaxItems
        description: The maximum number of items to return for a single request
        type: string
      - in: query
        name: NextToken
        description: The pagination token returned by a previous request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeEnvironmentManagedActions:
    get:
      summary: Describe Environment Managed Actions
      description: Lists an environment's upcoming and in-progress managed actions.
      operationId: describeEnvironmentManagedActions
      x-api-path-slug: actiondescribeenvironmentmanagedactions-get
      parameters:
      - in: query
        name: EnvironmentId
        description: The environment ID of the target environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the target environment
        type: string
      - in: query
        name: Status
        description: To show only actions with a particular status, specify a status
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeEnvironmentResources:
    get:
      summary: Describe Environment Resources
      description: Returns AWS resources for this environment.
      operationId: describeEnvironmentResources
      x-api-path-slug: actiondescribeenvironmentresources-get
      parameters:
      - in: query
        name: EnvironmentId
        description: The ID of the environment to retrieve AWS resource usage data
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to retrieve AWS resource usage data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeEnvironments:
    get:
      summary: Describe Environments
      description: Returns descriptions for existing environments.
      operationId: describeEnvironments
      x-api-path-slug: actiondescribeenvironments-get
      parameters:
      - in: query
        name: ApplicationName
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to include only      those that are associated with this application
        type: string
      - in: query
        name: EnvironmentIds.member.N
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to include only      those that have the specified IDs
        type: string
      - in: query
        name: EnvironmentNames.member.N
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to include only      those that have the specified names
        type: string
      - in: query
        name: IncludedDeletedBackTo
        description: If specified when IncludeDeleted is set to true, then      environments
          deleted after this date are displayed
        type: string
      - in: query
        name: IncludeDeleted
        description: 'Indicates whether to include deleted environments:'
        type: string
      - in: query
        name: VersionLabel
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to include only      those that are associated with this application version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeEvents:
    get:
      summary: Describe Events
      description: Returns list of event descriptions matching criteria up to the
        last 6 weeks.
      operationId: describeEvents
      x-api-path-slug: actiondescribeevents-get
      parameters:
      - in: query
        name: ApplicationName
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to include only      those associated with this application
        type: string
      - in: query
        name: EndTime
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to those that      occur up to, but not including, the EndTime
        type: string
      - in: query
        name: EnvironmentId
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to those      associated with this environment
        type: string
      - in: query
        name: EnvironmentName
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to those      associated with this environment
        type: string
      - in: query
        name: MaxRecords
        description: Specifies the maximum number of events that can be returned,
          beginning with the most      recent event
        type: string
      - in: query
        name: NextToken
        description: Pagination token
        type: string
      - in: query
        name: RequestId
        description: If specified, AWS Elastic Beanstalk restricts the described events
          to include only      those associated with this request ID
        type: string
      - in: query
        name: Severity
        description: If specified, limits the events returned from this call to include
          only those with the      specified severity or higher
        type: string
      - in: query
        name: StartTime
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to those that      occur on or after this time
        type: string
      - in: query
        name: TemplateName
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to those that      are associated with this environment configuration
        type: string
      - in: query
        name: VersionLabel
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to those      associated with this application version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
  /?Action=DescribeInstancesHealth:
    get:
      summary: Describe Instances Health
      description: |-
        Retrives detailed information about the health of instances in your AWS Elastic
              Beanstalk.
      operationId: describeInstancesHealth
      x-api-path-slug: actiondescribeinstanceshealth-get
      parameters:
      - in: query
        name: AttributeNames.member.N
        description: Specifies the response elements you wish to receive
        type: string
      - in: query
        name: EnvironmentId
        description: Specify the AWS Elastic Beanstalk environment by ID
        type: string
      - in: query
        name: EnvironmentName
        description: Specify the AWS Elastic Beanstalk environment by name
        type: string
      - in: query
        name: NextToken
        description: Specify the pagination token returned by a previous call
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances Health
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
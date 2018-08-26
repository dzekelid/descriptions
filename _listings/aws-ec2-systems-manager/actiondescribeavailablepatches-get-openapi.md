---
swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 0
info:
  title: Amazon EC2 Systems Manager API Describe Available Patches
  version: 1.0.0
  description: Lists all patches that could possibly be included in a patch baseline.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeActivations:
    get:
      summary: Describe Activations
      description: |-
        Details about the activation, including: the date and time the activation was created,
           the expiration date, the IAM role assigned to the instances in the activation, and the number of
           instances activated by this registration.
      operationId: describeActivations
      x-api-path-slug: actiondescribeactivations-get
      parameters:
      - in: query
        name: Filters
        description: A filter to view information about your activations
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: A token to start the list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activations
  /?Action=DescribeAssociation:
    get:
      summary: Describe Association
      description: Describes the associations for the specified SSM document or instance.
      operationId: describeAssociation
      x-api-path-slug: actiondescribeassociation-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID for which you want information
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Association
  /?Action=DescribeAutomationExecutions:
    get:
      summary: Describe Automation Executions
      description: Provides details about all active and terminated Automation executions.
      operationId: describeAutomationExecutions
      x-api-path-slug: actiondescribeautomationexecutions-get
      parameters:
      - in: query
        name: Filters
        description: Filters used to limit the scope of executions that are requested
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Automation
      - Executions
  /?Action=DescribeAvailablePatches:
    get:
      summary: Describe Available Patches
      description: Lists all patches that could possibly be included in a patch baseline.
      operationId: describeAvailablePatches
      x-api-path-slug: actiondescribeavailablepatches-get
      parameters:
      - in: query
        name: Filters
        description: Filters used to scope down the returned patches
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of patches to return (per page)
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Available
      - Patches
  /?Action=DescribeDocument:
    get:
      summary: Describe Document
      description: Describes the specified SSM document.
      operationId: describeDocument
      x-api-path-slug: actiondescribedocument-get
      parameters:
      - in: query
        name: DocumentVersion
        description: The document version for which you want information
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
  /?Action=DescribeDocumentPermission:
    get:
      summary: Describe Document Permission
      description: Describes the permissions for an SSM document.
      operationId: describeDocumentPermission
      x-api-path-slug: actiondescribedocumentpermission-get
      parameters:
      - in: query
        name: Name
        description: The name of the document for which you are the owner
        type: string
      - in: query
        name: PermissionType
        description: The permission type for the document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
      - Permission
  /?Action=DescribeEffectiveInstanceAssociations:
    get:
      summary: Describe Effective Instance Associations
      description: All associations for the instance(s).
      operationId: describeEffectiveInstanceAssociations
      x-api-path-slug: actiondescribeeffectiveinstanceassociations-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID for which you want to view all associations
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Effective
      - Instance
      - Associations
  /?Action=DescribeEffectivePatchesForPatchBaseline:
    get:
      summary: Describe Effective Patches For Patch Baseline
      description: Retrieves the current effective patches (the patch and the approval
        state) for the specified patch baseline.
      operationId: describeEffectivePatchesForPatchBaseline
      x-api-path-slug: actiondescribeeffectivepatchesforpatchbaseline-get
      parameters:
      - in: query
        name: BaselineId
        description: The ID of the patch baseline to retrieve the effective patches
          for
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of patches to return (per page)
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Effective
      - PatchesBaseline
  /?Action=DescribeInstanceAssociationsStatus:
    get:
      summary: Describe Instance Associations Status
      description: The status of the associations for the instance(s).
      operationId: describeInstanceAssociationsStatus
      x-api-path-slug: actiondescribeinstanceassociationsstatus-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance IDs for which you want association status information
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance
      - Associations
      - Status
  /?Action=DescribeInstanceInformation:
    get:
      summary: Describe Instance Information
      description: Describes one or more of your instances.
      operationId: describeInstanceInformation
      x-api-path-slug: actiondescribeinstanceinformation-get
      parameters:
      - in: query
        name: Filters
        description: One or more filters
        type: string
      - in: query
        name: InstanceInformationFilterList
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance
      - Information
  /?Action=DescribeInstancePatches:
    get:
      summary: Describe Instance Patches
      description: Retrieves information about the patches on the specified instance
        and their state relative to the patch baseline being used for the instance.
      operationId: describeInstancePatches
      x-api-path-slug: actiondescribeinstancepatches-get
      parameters:
      - in: query
        name: Filters
        description: 'Each entry in the array is a structure containing:'
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance whose patch state information should be
          retrieved
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of patches to return (per page)
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance
      - Patches
  /?Action=DescribeInstancePatchStates:
    get:
      summary: Describe Instance Patch States
      description: Retrieves the high-level patch state of one or more instances.
      operationId: describeInstancePatchStates
      x-api-path-slug: actiondescribeinstancepatchstates-get
      parameters:
      - in: query
        name: InstanceIds
        description: The ID of the instance whose patch state information should be
          retrieved
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of instances to return (per page)
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance
      - States
  /?Action=DescribeInstancePatchStatesForPatchGroup:
    get:
      summary: Describe Instance Patch States For Patch Group
      description: Retrieves the high-level patch state for the instances in the specified
        patch group.
      operationId: describeInstancePatchStatesForPatchGroup
      x-api-path-slug: actiondescribeinstancepatchstatesforpatchgroup-get
      parameters:
      - in: query
        name: Filters
        description: 'Each entry in the array is a structure containing:'
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of patches to return (per page)
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: PatchGroup
        description: The name of the patch group for which the patch state information
          should be retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance
      - StatesGroup
  /?Action=DescribeMaintenanceWindowExecutions:
    get:
      summary: Describe Maintenance Window Executions
      description: |-
        Lists the executions of a Maintenance Window (meaning, information about when the
           Maintenance Window was scheduled to be active and information about tasks registered and run with
           the Maintenance Window).
      operationId: describeMaintenanceWindowExecutions
      x-api-path-slug: actiondescribemaintenancewindowexecutions-get
      parameters:
      - in: query
        name: Filters
        description: 'Each entry in the array is a structure containing:'
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: WindowId
        description: The ID of the Maintenance Window whose executions should be retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Executions
  /?Action=DescribeMaintenanceWindowExecutionTaskInvocations:
    get:
      summary: Describe Maintenance Window Execution Task Invocations
      description: |-
        Retrieves the individual task executions (one per target) for a particular task executed
           as part of a Maintenance Window execution.
      operationId: describeMaintenanceWindowExecutionTaskInvocations
      x-api-path-slug: actiondescribemaintenancewindowexecutiontaskinvocations-get
      parameters:
      - in: query
        name: Filters
        description: Optional filters used to scope down the returned task invocations
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: TaskId
        description: The ID of the specific task in the Maintenance Window task that
          should be   retrieved
        type: string
      - in: query
        name: WindowExecutionId
        description: The ID of the Maintenance Window execution the task is part of
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Execution
      - Task
      - Invocations
  /?Action=DescribeMaintenanceWindowExecutionTasks:
    get:
      summary: Describe Maintenance Window Execution Tasks
      description: For a given Maintenance Window execution, lists the tasks that
        were executed.
      operationId: describeMaintenanceWindowExecutionTasks
      x-api-path-slug: actiondescribemaintenancewindowexecutiontasks-get
      parameters:
      - in: query
        name: Filters
        description: Optional filters used to scope down the returned tasks
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: WindowExecutionId
        description: The ID of the Maintenance Window execution whose task executions
          should be   retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Execution
      - Tasks
  /?Action=DescribeMaintenanceWindows:
    get:
      summary: Describe Maintenance Windows
      description: Retrieves the Maintenance Windows in an AWS account.
      operationId: describeMaintenanceWindows
      x-api-path-slug: actiondescribemaintenancewindows-get
      parameters:
      - in: query
        name: Filters
        description: Optional filters used to narrow down the scope of the returned
          Maintenance Windows
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Windows
  /?Action=DescribeMaintenanceWindowTargets:
    get:
      summary: Describe Maintenance Window Targets
      description: Lists the targets registered with the Maintenance Window.
      operationId: describeMaintenanceWindowTargets
      x-api-path-slug: actiondescribemaintenancewindowtargets-get
      parameters:
      - in: query
        name: Filters
        description: Optional filters that can be used to narrow down the scope of
          the returned window   targets
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: WindowId
        description: The ID of the Maintenance Window whose targets should be retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Targets
  /?Action=DescribeMaintenanceWindowTasks:
    get:
      summary: Describe Maintenance Window Tasks
      description: Lists the tasks in a Maintenance Window.
      operationId: describeMaintenanceWindowTasks
      x-api-path-slug: actiondescribemaintenancewindowtasks-get
      parameters:
      - in: query
        name: Filters
        description: Optional filters used to narrow down the scope of the returned
          tasks
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: WindowId
        description: The ID of the Maintenance Window whose tasks should be retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
      - Tasks
  /?Action=DescribeParameters:
    get:
      summary: Describe Parameters
      description: Get information about a parameter.
      operationId: describeParameters
      x-api-path-slug: actiondescribeparameters-get
      parameters:
      - in: query
        name: Filters
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameters
  /?Action=DescribePatchBaselines:
    get:
      summary: Describe Patch Baselines
      description: Lists the patch baselines in your AWS account.
      operationId: describePatchBaselines
      x-api-path-slug: actiondescribepatchbaselines-get
      parameters:
      - in: query
        name: Filters
        description: 'Each element in the array is a structure containing:'
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of patch baselines to return (per page)
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Baselines
  /?Action=DescribePatchGroups:
    get:
      summary: Describe Patch Groups
      description: Lists all patch groups that have been registered with patch baselines.
      operationId: describePatchGroups
      x-api-path-slug: actiondescribepatchgroups-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of patch groups to return (per page)
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Groups
  /?Action=DescribePatchGroupState:
    get:
      summary: Describe Patch Group State
      description: Returns high-level aggregated patch compliance state for a patch
        group.
      operationId: describePatchGroupState
      x-api-path-slug: actiondescribepatchgroupstate-get
      parameters:
      - in: query
        name: PatchGroup
        description: The name of the patch group whose patch snapshot should be retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - State
  /?Action=ListDocuments:
    get:
      summary: List Documents
      description: Describes one or more of your SSM documents.
      operationId: listDocuments
      x-api-path-slug: actionlistdocuments-get
      parameters:
      - in: query
        name: DocumentFilterList
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Documents
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
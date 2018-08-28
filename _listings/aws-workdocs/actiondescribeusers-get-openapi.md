---
swagger: "2.0"
x-collection-name: AWS WorkDocs
x-complete: 0
info:
  title: AWS WorkDocs API Describe Users
  version: 1.0.0
  description: Describes the specified users.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeDocumentVersions:
    get:
      summary: Describe Document Versions
      description: Retrieves the document versions for the specified document.
      operationId: describeDocumentVersions
      x-api-path-slug: actiondescribedocumentversions-get
      parameters:
      - in: query
        name: DocumentId
        description: The ID of the document
        type: string
      - in: query
        name: Fields
        description: Specify SOURCE to include initialized versions and a URL for
          the source document
        type: string
      - in: query
        name: Include
        description: A comma-separated list of values
        type: string
      - in: query
        name: Limit
        description: The maximum number of versions to return with this call
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
  /?Action=DescribeFolderContents:
    get:
      summary: Describe Folder Contents
      description: Describes the contents of the specified folder, including its documents
        and sub-folders.
      operationId: describeFolderContents
      x-api-path-slug: actiondescribefoldercontents-get
      parameters:
      - in: query
        name: FolderId
        description: The ID of the folder
        type: string
      - in: query
        name: Include
        description: The contents to include
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Order
        description: The order for the contents of the folder
        type: string
      - in: query
        name: Sort
        description: The sorting criteria
        type: string
      - in: query
        name: Type
        description: The type of items
        type: string
      responses:
        200:
          description: OK
      tags:
      - Folders
  /?Action=DescribeNotificationSubscriptions:
    get:
      summary: Describe Notification Subscriptions
      description: Lists the specified notification subscriptions.
      operationId: describeNotificationSubscriptions
      x-api-path-slug: actiondescribenotificationsubscriptions-get
      parameters:
      - in: query
        name: Limit
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: OrganizationId
        description: The ID of the organization
        type: string
      responses:
        200:
          description: OK
      tags:
      - Notifications
  /?Action=DescribeResourcePermissions:
    get:
      summary: Describe Resource Permissions
      description: Describes the permissions of a specified resource.
      operationId: describeResourcePermissions
      x-api-path-slug: actiondescriberesourcepermissions-get
      parameters:
      - in: query
        name: ResourceId
        description: The ID of the resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permissions
  /?Action=DescribeUsers:
    get:
      summary: Describe Users
      description: Describes the specified users.
      operationId: describeUsers
      x-api-path-slug: actiondescribeusers-get
      parameters:
      - in: query
        name: Fields
        description: A comma-separated list of values
        type: string
      - in: query
        name: Include
        description: The state of the users
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Order
        description: The order for the results
        type: string
      - in: query
        name: OrganizationId
        description: The ID of the organization
        type: string
      - in: query
        name: Query
        description: A query to filter users by user name
        type: string
      - in: query
        name: Sort
        description: The sorting criteria
        type: string
      - in: query
        name: UserIds
        description: The IDs of the users
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
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
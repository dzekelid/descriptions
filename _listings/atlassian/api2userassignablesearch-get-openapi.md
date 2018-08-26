---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Find users assignable to issues
  description: |-
    Returns a list of users that can be assigned to an issue. Use this method to find the list of users who can be assigned to:

    *   a new issue, by providing the `projectKeyOrId`.
    *   an updated issue, by providing the `issueKey`.
    *   to an issue during a transition (workflow action), by providing the `issueKey` and the transition id in `actionDescriptorId`. You can obtain the IDs of an issue's valid transitions using the `transitions` option in the `expand` parameter of [Get issue](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issue-issueIdOrKey-get).

    In all these cases, you can pass a username to determine if a user can be assigned to an issue. The user is returned in the response if they can be assigned to the issue or issue transition. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/user/assignable/search:
    get:
      summary: Find users assignable to issues
      description: |-
        Returns a list of users that can be assigned to an issue. Use this method to find the list of users who can be assigned to:

        *   a new issue, by providing the `projectKeyOrId`.
        *   an updated issue, by providing the `issueKey`.
        *   to an issue during a transition (workflow action), by providing the `issueKey` and the transition id in `actionDescriptorId`. You can obtain the IDs of an issue's valid transitions using the `transitions` option in the `expand` parameter of [Get issue](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issue-issueIdOrKey-get).

        In all these cases, you can pass a username to determine if a user can be assigned to an issue. The user is returned in the response if they can be assigned to the issue or issue transition. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
      operationId: com.atlassian.jira.rest.v2.issue.UserResource.findAssignableUsers_get
      x-api-path-slug: api2userassignablesearch-get
      parameters:
      - in: query
        name: actionDescriptorId
        description: The ID of the transition
      - in: header
        name: force-account-id
      - in: query
        name: issueKey
        description: The key of the issue
      - in: query
        name: maxResults
        description: The maximum number of items to return per page
      - in: query
        name: project
        description: The project ID or project key (case sensitive)
      - in: query
        name: query
        description: A search input that is matched against appropriate user attributes
          to find relevant users
      - in: query
        name: startAt
        description: The index of the first item to return in a page of results (page
          offset)
      - in: query
        name: username
        description: The username of the user
      responses:
        200:
          description: OK
      tags:
      - Find
      - Users
      - Assignable
      - To
      - Issues
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
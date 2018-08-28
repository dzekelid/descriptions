---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 0
info:
  title: Data2CRM DESCRIBE for Contact
  description: Returns describe for contacts
  version: "1"
host: api.data2crm.com:80
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/describe:
    get:
      summary: DESCRIBE for Account
      description: Returns describe for accounts
      operationId: getAccountDescribe
      x-api-path-slug: accountdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Describe
  /attachment/describe:
    get:
      summary: DESCRIBE for Attachment
      description: Returns describe for attachments
      operationId: getAttachmentDescribe
      x-api-path-slug: attachmentdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
      - Describe
  /call/describe:
    get:
      summary: DESCRIBE for Call
      description: Returns describe for calls
      operationId: getCallDescribe
      x-api-path-slug: calldescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
      - Describe
  /contact/describe:
    get:
      summary: DESCRIBE for Contact
      description: Returns describe for contacts
      operationId: getContactDescribe
      x-api-path-slug: contactdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Describe
  /email/describe:
    get:
      summary: DESCRIBE for Email
      description: Returns describe for emails
      operationId: getEmailDescribe
      x-api-path-slug: emaildescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Emails
      - Describe
  /event/describe:
    get:
      summary: DESCRIBE for Event
      description: Returns describe for events
      operationId: getEventDescribe
      x-api-path-slug: eventdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Events
      - Describe
  /lead/describe:
    get:
      summary: DESCRIBE for Lead
      description: Returns describe for leads
      operationId: getLeadDescribe
      x-api-path-slug: leaddescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Describe
  /meeting/describe:
    get:
      summary: DESCRIBE for Meeting
      description: Returns describe for meetings
      operationId: getMeetingDescribe
      x-api-path-slug: meetingdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Meeting
      - Describe
  /note/describe:
    get:
      summary: DESCRIBE for Note
      description: Returns describe for notes
      operationId: getNoteDescribe
      x-api-path-slug: notedescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Note
      - Describe
  /opportunity/describe:
    get:
      summary: DESCRIBE for Opportunity
      description: Returns describe for opportunities
      operationId: getOpportunityDescribe
      x-api-path-slug: opportunitydescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Opportunities
      - Describe
  /task/describe:
    get:
      summary: DESCRIBE for Task
      description: Returns describe for tasks
      operationId: getTaskDescribe
      x-api-path-slug: taskdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Tasks
      - Describe
  /user/describe:
    get:
      summary: DESCRIBE for User
      description: Returns describe for users
      operationId: getUserDescribe
      x-api-path-slug: userdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Describe
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
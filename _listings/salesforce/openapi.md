---
swagger: "2.0"
x-collection-name: Salesforce
x-complete: 1
info:
  title: Salesforce Sandbox
  description: create-sandbox-copies-of-your-environments-for-development-testing-and-training-without-compromising-the-data-and-applications-in-your-production-environment-
  version: 1.0.0
host: na14.salesforce.com
basePath: /services/data/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{version}/sobjects/{sobject}/describe:
    get:
      summary: Get Version Sobjects Sobject Describe
      description: Completely describes the individual metadata at all levels for
        the specified object. For example, this can be used to retrieve the fields,
        URLs, and child relationships for the Account object.
      operationId: getVersionSobjectsSobjectDescribe
      x-api-path-slug: versionsobjectssobjectdescribe-get
      parameters:
      - in: path
        name: sobject
        description: A Salesforces object
      - in: path
        name: version
        description: An API version
      responses:
        200:
          description: OK
      tags:
      - Version
      - Sobjects
      - Sobject
      - Describe
---
---
swagger: "2.0"
x-collection-name: AWS CloudHSM
x-complete: 1
info:
  title: AWS CloudHSM API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeHapg:
    get:
      summary: Describe HAPG
      description: Retrieves information about a high-availability partition group.
      operationId: describeHapg
      x-api-path-slug: actiondescribehapg-get
      parameters:
      - in: query
        name: HapgArn
        description: The ARN of the high-availability partition group to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - High-Availability Partition Group
  /?Action=DescribeHsm:
    get:
      summary: Describe HSM
      description: Retrieves information about an HSM.
      operationId: describeHsm
      x-api-path-slug: actiondescribehsm-get
      parameters:
      - in: query
        name: HsmArn
        description: The ARN of the HSM
        type: string
      - in: query
        name: HsmSerialNumber
        description: The serial number of the HSM
        type: string
      responses:
        200:
          description: OK
      tags:
      - HSM Instances
  /?Action=DescribeLunaClient:
    get:
      summary: Describe Luna Client
      description: Retrieves information about an HSM client.
      operationId: describeLunaClient
      x-api-path-slug: actiondescribelunaclient-get
      parameters:
      - in: query
        name: CertificateFingerprint
        description: The certificate fingerprint
        type: string
      - in: query
        name: ClientArn
        description: The ARN of the client
        type: string
      responses:
        200:
          description: OK
      tags:
      - Luna Clients
---
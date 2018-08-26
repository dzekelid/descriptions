---
swagger: "2.0"
x-collection-name: AWS Kinesis
x-complete: 1
info:
  title: AWS Kinesis Firehose API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeDeliveryStream:
    get:
      summary: Describe Delivery Stream
      description: describes the specified delivery stream and gets the status.
      operationId: DescribeDeliveryStream
      x-api-path-slug: actiondescribedeliverystream-get
      parameters:
      - in: query
        name: DeliveryStreamName
        description: The name of the delivery stream
        type: string
      - in: query
        name: ExclusiveStartDestinationId
        description: The ID of the destination to start returning the destination
          information
        type: string
      - in: query
        name: Limit
        description: The limit on the number of destinations to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Delivery Streams
---
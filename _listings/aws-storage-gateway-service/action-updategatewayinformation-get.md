---
swagger: "2.0"
info:
  title: AWS Storage Gateway Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateGatewayInformation&k=1:
    get:
      summary: ' Update Gateway Information '
      description: Updates a gateway's metadata, which includes the gateway's name
        and time zone
      operationId: updateGatewayInformation
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: GatewayName
        description: The name you configured for your gateway
        type: string
      - in: query
        name: GatewayTimezone
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - gateway
definitions: []
x-collection-name: AWS Storage Gateway Service
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
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
  /?Action=RetrieveTapeRecoveryPoint:
    get:
      summary: ' Retrieve Tape Recovery Point '
      description: Retrieves the recovery point for the specified virtual tape
      operationId: retrieveTapeRecoveryPoint
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: TapeARN
        description: The Amazon Resource Name (ARN) of the virtual tape for which
          you want to retrieve the         recovery point
        type: string
      responses:
        200:
          description: OK
      tags:
      - tape recovery
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
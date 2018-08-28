---
swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 0
info:
  title: Logic Broker CommerceAPI Execute custom handler.
  version: 1.0.0
  description: Request rate limited to 2 requests per second with bursts up to 25
    requests.
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Document/Script/{ScriptName}:
    get:
      summary: Execute custom handler.
      description: Request rate limited to 2 requests per second with bursts up to
        25 requests.
      operationId: Document_GetCustomScript
      x-api-path-slug: apiv1documentscriptscriptname-get
      parameters:
      - in: path
        name: ScriptName
        description: The custom script name
      responses:
        200:
          description: OK
      tags:
      - Execute
      - Custom
      - Handler
    post:
      summary: Execute custom handler.
      description: Request rate limited to 2 requests per second with bursts up to
        25 requests.
      operationId: Document_PostCustomScript
      x-api-path-slug: apiv1documentscriptscriptname-post
      parameters:
      - in: path
        name: ScriptName
        description: The custom script name
      responses:
        200:
          description: OK
      tags:
      - Execute
      - Custom
      - Handler
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
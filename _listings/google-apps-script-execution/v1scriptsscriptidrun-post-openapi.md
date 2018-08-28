---
swagger: "2.0"
x-collection-name: Google Apps Script Execution
x-complete: 0
info:
  title: Google Apps Script Execution API Run Script
  description: |-
    Runs a function in an Apps Script project. The project must be deployed
    for use with the Apps Script Execution API.

    This method requires authorization with an OAuth 2.0 token that includes at
    least one of the scopes listed in the [Authorization](#authorization)
    section; script projects that do not require authorization cannot be
    executed through this API. To find the correct scopes to include in the
    authentication token, open the project in the script editor, then select
    **File > Project properties** and click the **Scopes** tab.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: script.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/scripts/{scriptId}:run:
    post:
      summary: Run Script
      description: |-
        Runs a function in an Apps Script project. The project must be deployed
        for use with the Apps Script Execution API.

        This method requires authorization with an OAuth 2.0 token that includes at
        least one of the scopes listed in the [Authorization](#authorization)
        section; script projects that do not require authorization cannot be
        executed through this API. To find the correct scopes to include in the
        authentication token, open the project in the script editor, then select
        **File > Project properties** and click the **Scopes** tab.
      operationId: script.scripts.run
      x-api-path-slug: v1scriptsscriptidrun-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: scriptId
        description: The project key of the script to be executed
      responses:
        200:
          description: OK
      tags:
      - Script
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
---
swagger: "2.0"
info:
  title: Google Apps Script Execution
  description: Executes Google Apps Script projects.
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
      description: Runs a function in an Apps Script project
      operationId: script.scripts.run
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
      - script
definitions:
  ExecutionError:
    properties:
      errorMessage:
        description: This is a default description.
        type: post
      errorType:
        description: This is a default description.
        type: post
      scriptStackTraceElements:
        description: This is a default description.
        type: post
  ExecutionRequest:
    properties:
      devMode:
        description: This is a default description.
        type: post
      function:
        description: This is a default description.
        type: post
      parameters:
        description: This is a default description.
        type: post
      sessionState:
        description: This is a default description.
        type: post
  ExecutionResponse:
    properties: []
  Operation:
    properties:
      done:
        description: This is a default description.
        type: post
      metadata:
        description: This is a default description.
        type: post
      name:
        description: This is a default description.
        type: post
      response:
        description: This is a default description.
        type: post
  ScriptStackTraceElement:
    properties:
      function:
        description: This is a default description.
        type: post
      lineNumber:
        description: This is a default description.
        type: post
  Status:
    properties:
      code:
        description: This is a default description.
        type: post
      details:
        description: This is a default description.
        type: post
      message:
        description: This is a default description.
        type: post
x-collection-name: Google Apps Script Execution
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
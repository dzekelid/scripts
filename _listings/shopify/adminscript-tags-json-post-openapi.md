---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify create a new script tag
  description: Create a new script tag.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/script_tags/373484.json:
    get:
      summary: Get a single  script tag
      description: Get a single  script tag.
      operationId: getAdminScriptTags373484.json
      x-api-path-slug: adminscript-tags373484-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Script
      - Tag
  /admin/script_tags.json:
    get:
      summary: Get a list of all script tags
      description: Get a list of all script tags.
      operationId: getAdminScriptTags.json
      x-api-path-slug: adminscript-tags-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Script
      - Tags
    post:
      summary: create a new script tag
      description: Create a new script tag.
      operationId: postAdminScriptTags.json
      x-api-path-slug: adminscript-tags-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Create
      - New
      - Script
      - Tag
  /admin/script_tags/108074126.json:
    put:
      summary: update a script tag
      description: Update a script tag.
      operationId: putAdminScriptTags108074126.json
      x-api-path-slug: adminscript-tags108074126-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Update
      - Script
      - Tag
    delete:
      summary: remove a script tag
      description: Remove a script tag.
      operationId: deleteAdminScriptTags108074126.json
      x-api-path-slug: adminscript-tags108074126-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Remove
      - Script
      - Tag
  /admin/script_tags/count.json:
    get:
      summary: Get a count of all script tags
      description: Get a count of all script tags.
      operationId: getAdminScriptTagsCount.json
      x-api-path-slug: adminscript-tagscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Script
      - Tags
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
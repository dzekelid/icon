---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Update Icon
  description: Update icon Update the properties of icon object.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/tables(&lt;id|name&gt;)/sort/fields/icon:
    get:
      summary: Get Icon
      description: Get Icon Retrieve the properties and relationships of icon object.
      operationId: GetIcon
      x-api-path-slug: workbooktablesltidnamegtsortfieldsicon-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Icon
    patch:
      summary: Update Icon
      description: Update icon Update the properties of icon object.
      operationId: UpdateIcon
      x-api-path-slug: workbooktablesltidnamegtsortfieldsicon-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Icon
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/fields/icon:
    get:
      summary: Get Icon
      description: Get Icon Retrieve the properties and relationships of icon object.
      operationId: GetIcon
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortfieldsicon-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Icon
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
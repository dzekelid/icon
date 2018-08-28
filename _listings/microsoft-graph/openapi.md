swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
    patch:
      summary: Update Icon
      description: Update icon Update the properties of icon object.
      operationId: UpdateIcon
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtsortfieldsicon-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Icon
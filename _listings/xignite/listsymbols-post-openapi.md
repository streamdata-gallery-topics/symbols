---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Logos List Symbols
  description: List available logos on market.
  version: 1.0.0
host: www.xignite.com
basePath: xLogos.json/XigniteLogos
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListSymbols:
    post:
      summary: List Symbols
      description: List available logos on market.
      operationId: postListsymbols
      x-api-path-slug: listsymbols-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Symbols
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
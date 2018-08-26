---
swagger: "2.0"
x-collection-name: HitBTC
x-complete: 0
info:
  title: HitBTC Get A Single Order By ClientOrderId
  description: Get a single order by clientorderid.
  version: 1.0.0
basePath: /api/2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /order/{clientOrderId}:
    get:
      summary: Get A Single Order By ClientOrderId
      description: Get a single order by clientorderid.
      operationId: getOrderClientorder
      x-api-path-slug: orderclientorderid-get
      parameters:
      - in: path
        name: clientOrderId
      - in: query
        name: wait
        description: Long polling wait timeout in milliseconds
      responses:
        200:
          description: OK
      tags:
      - Single
      - Order
      - By
      - ClientOrderId
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
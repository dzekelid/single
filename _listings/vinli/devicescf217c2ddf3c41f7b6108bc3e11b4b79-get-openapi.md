---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli get a single device
  description: Get a single device.
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79:
    get:
      summary: get a single device
      description: Get a single device.
      operationId: DevicesCf217c2dDf3c41f7B6108bc3e11b4b79Get
      x-api-path-slug: devicescf217c2ddf3c41f7b6108bc3e11b4b79-get
      responses:
        200:
          description: OK
      tags:
      - Get
      - Single
      - Device
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
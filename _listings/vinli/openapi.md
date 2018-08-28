swagger: "2.0"
x-collection-name: Vinli
x-complete: 1
info:
  title: Vinli
  description: todo-add-description
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
---
swagger: "2.0"
x-collection-name: HitBTC
x-complete: 1
info:
  title: HitBTC API
  description: create-api-keys-in-your-profile-httpshitbtc-comsettingsapikeys-and-use-public-api-key-as-username-and-secret-as-password-to-authorize-
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
---
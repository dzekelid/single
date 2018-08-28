swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 1
info:
  title: CommerceAPI
  version: 1.0.0
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Inventory/{partnerId}/Item/{sku}:
    get:
      summary: Get a single item by SKU
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Inventory_GetItem
      x-api-path-slug: apiv1inventorypartneriditemsku-get
      parameters:
      - in: path
        name: partnerId
        description: Partner account number
      - in: path
        name: sku
        description: Item SKU
      responses:
        200:
          description: OK
      tags:
      - Single
      - Item
      - By
      - SKU
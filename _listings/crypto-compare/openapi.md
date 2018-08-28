swagger: "2.0"
x-collection-name: Crypto Compare
x-complete: 1
info:
  title: Cryptocompare
  description: todo-add-description
  version: 1.0.0
host: min-api.cryptocompare.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /data/price:
    get:
      summary: Get Single Price
      description: Get single price.
      operationId: DataPriceGet
      x-api-path-slug: dataprice-get
      parameters:
      - in: query
        name: fsym
      - in: query
        name: tsyms
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Single
      - Price
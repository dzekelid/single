---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Get a single customer by ID
  description: Get a single customer by id.
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
  /admin/smart_collections/401912846.json:
    get:
      summary: Get a single collection
      description: Get a single collection.
      operationId: getAdminSmartCollections401912846.json
      x-api-path-slug: adminsmart-collections401912846-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Collection
    put:
      summary: Update a single collection
      description: Update a single collection.
      operationId: putAdminSmartCollections401912846.json
      x-api-path-slug: adminsmart-collections401912846-json-put
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
      - Single
      - Collection
  /admin/blogs/62581763/articles/196805774.json:
    get:
      summary: Get a single article by its ID and the ID of the parent blog
      description: Get a single article by its id and the id of the parent blog.
      operationId: getAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Article
      - By
      - Its
      - ID
      - ID
      - Parent
      - Blog
  /admin/metafields/33145232974.json:
    get:
      summary: Get a single store metafield by ID
      description: Get a single store metafield by id.
      operationId: getAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Store
      - Metafield
      - By
      - ID
  /admin/custom_collections/246409795.json:
    get:
      summary: Get a single custom collections
      description: Get a single custom collections.
      operationId: getAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Custom
      - Collections
  /admin/comments/#{id}.json:
    get:
      summary: Get a single comment
      description: Get a single comment.
      operationId: getAdminComments#.json
      x-api-path-slug: admincommentsid-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Comment
  /admin/orders/4602125518/risks/8609858574.json:
    get:
      summary: Get a single Order Risk
      description: Get a single order risk.
      operationId: getAdminOrders4602125518Risks8609858574.json
      x-api-path-slug: adminorders4602125518risks8609858574-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Order
      - Risk
  /admin/orders/4554953422.json:
    get:
      summary: Get a representation of a single order
      description: Get a representation of a single order.
      operationId: getAdminOrders4554953422.json
      x-api-path-slug: adminorders4554953422-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Representation
      - Single
      - Order
  /admin/locations/8790723.json:
    get:
      summary: Get a single location
      description: Get a single location.
      operationId: getAdminLocations8790723.json
      x-api-path-slug: adminlocations8790723-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Location
  /admin/fulfillment_services/1357646.json:
    get:
      summary: Get a single fulfillment service by its ID
      description: Get a single fulfillment service by its id.
      operationId: getAdminFulfillmentServices1357646.json
      x-api-path-slug: adminfulfillment-services1357646-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Fulfillment
      - Service
      - By
      - Its
      - ID
  /admin/products/7990943555/images/19489404942.json:
    get:
      summary: Get a single product image by id
      description: Get a single product image by id.
      operationId: getAdminProducts7990943555Images19489404942.json
      x-api-path-slug: adminproducts7990943555images19489404942-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Product
      - Image
      - By
      - Id
  /admin/themes/110163843.json:
    get:
      summary: Get a single theme
      description: Get a single theme.
      operationId: getAdminThemes110163843.json
      x-api-path-slug: adminthemes110163843-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Theme
  /admin/customers/3989659651.json:
    get:
      summary: Get a single customer by ID
      description: Get a single customer by id.
      operationId: getAdminCustomers3989659651.json
      x-api-path-slug: admincustomers3989659651-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Customer
      - By
      - ID
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
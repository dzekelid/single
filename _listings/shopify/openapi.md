swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
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
  /admin/blogs/62581763.json:
    get:
      summary: Get a single blog by its ID
      description: Get a single blog by its id.
      operationId: getAdminBlogs62581763.json
      x-api-path-slug: adminblogs62581763-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Blog
      - By
      - Its
      - ID
  /admin/products/7990943555/metafields/33058305934.json:
    get:
      summary: Get a single product metafield using the metafield's nested resource
        path
      description: Get a single product metafield using the metafield's nested resource
        path.
      operationId: getAdminProducts7990943555Metafields33058305934.json
      x-api-path-slug: adminproducts7990943555metafields33058305934-json-get
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
      - Metafield
      - Using
      - Metafields
      - Nested
      - Resource
      - Path
  /admin/redirects/count/7376372.json:
    get:
      summary: Get a single URL redirect
      description: Get a single url redirect.
      operationId: getAdminRedirectsCount7376372.json
      x-api-path-slug: adminredirectscount7376372-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - URL
      - Redirect
  /admin/orders/4554953422/refunds/646546.json:
    get:
      summary: Get a representation of a single refund
      description: Get a representation of a single refund.
      operationId: getAdminOrders4554953422Refunds646546.json
      x-api-path-slug: adminorders4554953422refunds646546-json-get
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
      - Refund
  /admin/countries/261414723/provinces/4003640003.json:
    get:
      summary: get a single province
      description: Get a single province.
      operationId: getAdminCountries261414723Provinces4003640003.json
      x-api-path-slug: admincountries261414723provinces4003640003-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Get
      - Single
      - Province
  /admin/smart_collections/408154574.json:
    delete:
      summary: Delete a single collection
      description: Delete a single collection.
      operationId: deleteAdminSmartCollections408154574.json
      x-api-path-slug: adminsmart-collections408154574-json-delete
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
  /admin/products/7990943555.json:
    get:
      summary: Get a single product
      description: Get a single product.
      operationId: getAdminProducts7990943555.json
      x-api-path-slug: adminproducts7990943555-json-get
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
  /admin/webhooks/93838927.json:
    get:
      summary: Get a single webhook by its id.
      description: Get a single webhook by its id..
      operationId: getAdminWebhooks93838927.json
      x-api-path-slug: adminwebhooks93838927-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Webhook
      - By
      - Its
      - Id
  /admin/customers/3989659651/addresses/5436816654.json:
    get:
      summary: Get a single customers address
      description: Get a single customers address.
      operationId: getAdminCustomers3989659651Addresses5436816654.json
      x-api-path-slug: admincustomers3989659651addresses5436816654-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Customers
      - Address
  /admin/pages/169722563.json:
    get:
      summary: Get a single page by its ID
      description: Get a single page by its id.
      operationId: getAdminPages169722563.json
      x-api-path-slug: adminpages169722563-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Page
      - By
      - Its
      - ID
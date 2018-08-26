---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Get a single custom collections
  description: Get a single custom collections.
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
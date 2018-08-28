---
swagger: "2.0"
x-collection-name: BigCommerce
x-complete: 0
info:
  title: BigCommerce Retrieve a single variant
  description: Get a `Variant` object.
  version: 1.0.0
host: api.bigcommerce.com
basePath: /stores
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{store-hash}/v3/catalog/products/{id}/images:
    get:
      summary: Retrieve images for a single product
      description: GET request for retrieving images associated with a product
      operationId: V3CatalogProductsImagesByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsidimages-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Imagesa
      - Single
      - Product
    post:
      summary: Upload a new product image to a single product
      description: Adds a new product image from a publicly accessible URL. May fail
        if the hosting website is forcing HTTPS connections with TLS 1.0 (as this
        has been deprecated).
      operationId: V3CatalogProductsImagesByStoreHashAndIdPost
      x-api-path-slug: storehashv3catalogproductsidimages-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Upload
      - New
      - Product
      - Image
      - To
      - Single
      - Product
  /{store-hash}/v3/catalog/products/{id}:
    get:
      summary: Retrieve a single product with expanded sub-resources
      description: Request a single product with expanded variant information
      operationId: V3CatalogProductsByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsid-get
      parameters:
      - in: path
        name: id
      - in: query
        name: include
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Single
      - Product
      - Expanded
      - Sub-resources
    delete:
      summary: Delete a single product by ID
      description: Deleting a single product from the catalog by product ID
      operationId: V3CatalogProductsByStoreHashAndIdDelete
      x-api-path-slug: storehashv3catalogproductsid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Product
      - By
      - ID
  /{store_hash}/v3/catalog/products/{id}/videos:
    get:
      summary: Retrieve all videos for a single product
      description: ""
      operationId: V3CatalogProductsVideosByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogproductsidvideos-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - ""
      - Videosa
      - Single
      - Product
  /{store_hash}/v3/catalog/categories/{id}:
    get:
      summary: Retrieve a single category
      description: ""
      operationId: V3CatalogCategoriesByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogcategoriesid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Single
      - Category
    delete:
      summary: Delete a single category
      description: ""
      operationId: V3CatalogCategoriesByStoreHashAndIdDelete
      x-api-path-slug: store-hashv3catalogcategoriesid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Category
  /{store-hash}/v3/catalog/products/{id}/images/{id}:
    get:
      summary: Retrieve a single product image's data
      description: GET request for a specific product image by ID
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsidimagesid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Single
      - Product
      - Images
      - Data
    delete:
      summary: Delete a single product image
      description: Delete a product image and it's description
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdDelete
      x-api-path-slug: storehashv3catalogproductsidimagesid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Product
      - Image
  /{store_hash}/v3/catalog/products/{id}/variants/{id}:
    get:
      summary: Retrieve a single variant
      description: Get a `Variant` object.
      operationId: V3CatalogProductsVariantsIdByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogproductsidvariantsid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Single
      - Variant
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
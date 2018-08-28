swagger: "2.0"
x-collection-name: aWhere
x-complete: 1
info:
  title: aWhere API Platform
  description: todo-add-description
  version: 1.0.0
host: api.awhere.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/fields/field1:
    get:
      summary: Get a Single Field by ID
      description: |-
        ####Request
        This API call retrieves a single field by ID.

        [Get Fields Documentation](http://developer.awhere.com/api/reference/fields/get-fields)


        ####Security
        This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
      operationId: V2FieldsField1Get
      x-api-path-slug: v2fieldsfield1-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Single
      - Field
      - By
      - ID
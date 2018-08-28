---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Remove a single object from frontend storage.
  description: Remove a single object from frontend storage..
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/contacts/{contactId}/document:
    get:
      summary: Get a single storage object from contact documents
      description: Get a single storage object from contact documents.
      operationId: getRestAccountsContactsContactDocument
      x-api-path-slug: restaccountscontactscontactiddocument-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key of the object to get from contact documents
      responses:
        200:
          description: OK
      tags:
      - Single
      - Storage
      - Object
      - From
      - Contact
      - Documents
  /rest/accounts/contacts/{contactId}/document/url:
    get:
      summary: Get a temporary url for a single document
      description: Get a temporary url for a single document.
      operationId: getRestAccountsContactsContactDocumentUrl
      x-api-path-slug: restaccountscontactscontactiddocumenturl-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key to get temporary url for
      responses:
        200:
          description: OK
      tags:
      - Temporary
      - Urla
      - Single
      - Document
  /rest/accounts/contacts/{contactId}/documents:
    get:
      summary: List documents for a single contact
      description: List documents for a single contact.
      operationId: getRestAccountsContactsContactDocuments
      x-api-path-slug: restaccountscontactscontactiddocuments-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: continuationToken
        description: token from previous request to continue listing documents
      responses:
        200:
          description: OK
      tags:
      - List
      - Documentsa
      - Single
      - Contact
  /rest/boards/{boardId}:
    get:
      summary: Gets a single board by its ID
      description: Gets a single board by its id.
      operationId: getRestBoardsBoard
      x-api-path-slug: restboardsboardid-get
      parameters:
      - in: path
        name: boardId
      - in: query
        name: tasksPerPage
        description: Maximum number of tasks to list per column
      responses:
        200:
          description: OK
      tags:
      - S
      - Single
      - Board
      - By
      - Its
      - ID
  /rest/customer_contracts/{contractId}:
    get:
      summary: Returns a single contract
      description: Returns a single contract.
      operationId: getRestCustomerContractsContract
      x-api-path-slug: restcustomer-contractscontractid-get
      parameters:
      - in: path
        name: contractId
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Single
      - Contract
  /rest/storage/frontend/file:
    delete:
      summary: Remove a single object from frontend storage.
      description: Remove a single object from frontend storage..
      operationId: deleteRestStorageFrontendFile
      x-api-path-slug: reststoragefrontendfile-delete
      parameters:
      - in: query
        name: key
        description: The key of the object to delete
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Single
      - Object
      - From
      - Frontend
      - Storage
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
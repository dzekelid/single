swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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
    get:
      summary: Get file information for a single object in frontend storage. Append
        public cloudfront url to retrieved object.
      description: Get file information for a single object in frontend storage. append
        public cloudfront url to retrieved object..
      operationId: getRestStorageFrontendFile
      x-api-path-slug: reststoragefrontendfile-get
      parameters:
      - in: query
        name: key
        description: The key of the object to get information about
      responses:
        200:
          description: OK
      tags:
      - File
      - Informationa
      - Single
      - Object
      - In
      - Frontend
      - Storage
      - ""
      - Append
      - Public
      - Cloudfront
      - Url
      - To
      - Retrieved
      - Object
    post:
      summary: Upload a single file to frontend storage.
      description: If file is an image, generate a thumbnail and store dimensions
        in metadata.
      operationId: postRestStorageFrontendFile
      x-api-path-slug: reststoragefrontendfile-post
      parameters:
      - in: query
        name: key
        description: The key for the uploaded object
      - in: query
        name: maxAge
        description: Number of seconds until the content of the file expires
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Single
      - File
      - To
      - Frontend
      - Storage
  /rest/storage/frontend/file/metadata:
    get:
      summary: Get assigend metadata for a single storage object
      description: Get assigend metadata for a single storage object.
      operationId: getRestStorageFrontendFileMetadata
      x-api-path-slug: reststoragefrontendfilemetadata-get
      parameters:
      - in: query
        name: key
        description: The key of the object to get metadata for
      responses:
        200:
          description: OK
      tags:
      - Assigend
      - Metadataa
      - Single
      - Storage
      - Object
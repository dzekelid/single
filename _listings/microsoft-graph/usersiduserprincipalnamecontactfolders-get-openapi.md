---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Get Single Value Legacy Extended Property
  description: Get singleValueLegacyExtendedProperty Get resource instances that contain
    a single-value extended property by using $expand or $filter.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/messages:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: memessages-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /me/mailFolders:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: memailfolders-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/mailFolders:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamemailfolders-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /me/events:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: meevents-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: 'Prefer: outlook.timezone'
        description: The default time zone for events in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /me/calendars:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: mecalendars-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/calendars:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecalendars-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders/{id}/contacts:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfoldersidcontacts-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /me/contactfolders:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: mecontactfolders-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
  /users/{id|userPrincipalName}/contactFolders:
    get:
      summary: Get Single Value Legacy Extended Property
      description: Get singleValueLegacyExtendedProperty Get resource instances that
        contain a single-value extended property by using $expand or $filter.
      operationId: GetSingleValueLegacyExtendedProperty
      x-api-path-slug: usersiduserprincipalnamecontactfolders-get
      parameters:
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Single
      - Value
      - Legacy
      - Extended
      - Property
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
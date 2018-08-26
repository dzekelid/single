---
swagger: "2.0"
x-collection-name: Quovo
x-complete: 0
info:
  title: Quovo Get a single manual account
  description: Returns a single Manual Account.
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
  /connections/{connection_id}:
    get:
      summary: Get a single connection
      description: Provides information on a specific connection.
      operationId: ConnectionsByConnectionIdGet
      x-api-path-slug: connectionsconnection-id-get
      parameters:
      - in: path
        name: connection_id
      responses:
        200:
          description: OK
      tags:
      - Single
      - Connection
  /users/{user_id}:
    get:
      summary: Get a single user
      description: Provides information on a single User.
      operationId: UsersByUserIdGet
      x-api-path-slug: usersuser-id-get
      parameters:
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Single
      - User
  /manual_accounts/{manual_account_id}:
    get:
      summary: Get a single manual account
      description: Returns a single Manual Account.
      operationId: ManualAccountsByManualAccountIdGet
      x-api-path-slug: manual-accountsmanual-account-id-get
      parameters:
      - in: path
        name: manual_account_id
      responses:
        200:
          description: OK
      tags:
      - Single
      - Manual
      - Account
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
---
swagger: "2.0"
x-collection-name: Quovo
x-complete: 1
info:
  title: Quovo API v3
  description: todo-add-description
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
  /transactions/{transaction_id}:
    get:
      summary: Get a single transaction
      description: Provides information on a single historical transaction.
      operationId: TransactionsByTransactionIdGet
      x-api-path-slug: transactionstransaction-id-get
      parameters:
      - in: path
        name: transaction_id
      responses:
        200:
          description: OK
      tags:
      - Single
      - Transaction
  /accounts/{account_id}:
    get:
      summary: Get a single account
      description: Provides information on a single account.
      operationId: AccountsByAccountIdGet
      x-api-path-slug: accountsaccount-id-get
      parameters:
      - in: path
        name: account_id
      responses:
        200:
          description: OK
      tags:
      - Single
      - Account
  /institutions/{institution_id}:
    get:
      summary: Get a single institution
      description: Provides information on a single Quovo-supported institution.
      operationId: InstitutionsByInstitutionIdGet
      x-api-path-slug: institutionsinstitution-id-get
      parameters:
      - in: path
        name: institution_id
      responses:
        200:
          description: OK
      tags:
      - Single
      - Institution
---
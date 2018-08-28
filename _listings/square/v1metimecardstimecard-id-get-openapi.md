---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API Provides the details for a single timecard.
  description: Provides the details for a single timecard.
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/me/employees/{employee_id}:
    get:
      summary: Provides the details for a single employee.
      description: Provides the details for a single employee.
      operationId: RetrieveEmployee
      x-api-path-slug: v1meemployeesemployee-id-get
      parameters:
      - in: path
        name: employee_id
        description: The employees ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Employee
  /v1/me/roles/{role_id}:
    get:
      summary: Provides the details for a single employee role.
      description: Provides the details for a single employee role.
      operationId: RetrieveEmployeeRole
      x-api-path-slug: v1merolesrole-id-get
      parameters:
      - in: path
        name: role_id
        description: The roles ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Employee
      - Role
  /v1/me/timecards:
    post:
      summary: Creates a timecard for an employee. Each timecard corresponds to a
        single shift.
      description: Creates a timecard for an employee. Each timecard corresponds to
        a single shift.
      operationId: CreateTimecard
      x-api-path-slug: v1metimecards-post
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Timecardan
      - Employee
      - ""
      - Each
      - Timecard
      - Corresponds
      - To
      - Single
      - Shift
  /v1/me/timecards/{timecard_id}:
    get:
      summary: Provides the details for a single timecard.
      description: Provides the details for a single timecard.
      operationId: RetrieveTimecard
      x-api-path-slug: v1metimecardstimecard-id-get
      parameters:
      - in: path
        name: timecard_id
        description: The timecards ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Timecard
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
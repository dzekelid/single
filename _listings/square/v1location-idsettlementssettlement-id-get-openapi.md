---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API Provides comprehensive information for a single settlement,
    including the entries that contribute to the settlement's total.
  description: Provides comprehensive information for a single settlement, including
    the entries that contribute to the settlement's total.
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
  /v1/{location_id}/cash-drawer-shifts/{shift_id}:
    get:
      summary: Provides the details for a single cash drawer shift, including all
        events that occurred during the shift.
      description: Provides the details for a single cash drawer shift, including
        all events that occurred during the shift.
      operationId: RetrieveCashDrawerShift
      x-api-path-slug: v1location-idcashdrawershiftsshift-id-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list cash drawer shifts for
      - in: path
        name: shift_id
        description: The shifts ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Cash
      - Drawer
      - Shift
      - ""
      - Including
      - ""
      - Events
      - That
      - Occurred
      - During
      - Shift
  /v1/{location_id}/items/{item_id}:
    get:
      summary: Provides the details for a single item, including associated modifier
        lists and fees.
      description: Provides the details for a single item, including associated modifier
        lists and fees.
      operationId: RetrieveItem
      x-api-path-slug: v1location-iditemsitem-id-get
      parameters:
      - in: path
        name: item_id
        description: The items ID
      - in: path
        name: location_id
        description: The ID of the items associated location
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Item
      - ""
      - Including
      - Associated
      - Modifier
      - Lists
      - Fees
  /v1/{location_id}/modifier-lists/{modifier_list_id}:
    get:
      summary: Provides the details for a single modifier list.
      description: Provides the details for a single modifier list.
      operationId: RetrieveModifierList
      x-api-path-slug: v1location-idmodifierlistsmodifier-list-id-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the items associated location
      - in: path
        name: modifier_list_id
        description: The modifier lists ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Single
      - Modifier
      - List
  /v1/{location_id}/orders/{order_id}:
    get:
      summary: Provides comprehensive information for a single online store order,
        including the order's history.
      description: Provides comprehensive information for a single online store order,
        including the order's history.
      operationId: RetrieveOrder
      x-api-path-slug: v1location-idordersorder-id-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the orders associated location
      - in: path
        name: order_id
        description: The orders Square-issued ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Comprehensive
      - Informationa
      - Single
      - Online
      - Store
      - Order
      - ""
      - Including
      - Orders
      - History
  /v1/{location_id}/payments/{payment_id}:
    get:
      summary: Provides comprehensive information for a single payment.
      description: Provides comprehensive information for a single payment.
      operationId: RetrievePayment
      x-api-path-slug: v1location-idpaymentspayment-id-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the payments associated location
      - in: path
        name: payment_id
        description: The payments Square-issued ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Comprehensive
      - Informationa
      - Single
      - Payment
  /v1/{location_id}/settlements/{settlement_id}:
    get:
      summary: Provides comprehensive information for a single settlement, including
        the entries that contribute to the settlement's total.
      description: Provides comprehensive information for a single settlement, including
        the entries that contribute to the settlement's total.
      operationId: RetrieveSettlement
      x-api-path-slug: v1location-idsettlementssettlement-id-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the settlementss associated location
      - in: path
        name: settlement_id
        description: The settlements Square-issued ID
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Comprehensive
      - Informationa
      - Single
      - Settlement
      - ""
      - Including
      - Entries
      - That
      - Contribute
      - To
      - Settlements
      - Total
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
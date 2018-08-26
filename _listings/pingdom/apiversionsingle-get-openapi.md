---
swagger: "2.0"
x-collection-name: Pingdom
x-complete: 0
info:
  title: Single API Make A Single Test
  description: Performs a single test using a specified Pingdom probe against a specified
    target. Please note that this method is meant to be used sparingly, not to set
    up your own monitoring solution.
  version: 1.0.0
host: api.pingdom.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? |2-

        /api/{version}/single
  : ? |2-

          get
    : summary: Make A Single Test
      description: Performs a single test using a specified Pingdom probe against
        a specified target. Please note that this method is meant to be used sparingly,
        not to set up your own monitoring solution.
      operationId: make-a-single-test
      x-api-path-slug: apiversionsingle-get
      parameters:
      - in: query
        name: host
        description: Target host
        type: <td>string</td>
      - in: query
        name: ipv6
        description: Use ipv6 instead of ipv4
        type: <td>boolean</td>
      - in: query
        name: probeid
        description: Probe identifier
        type: <td>integer</td>
      - in: query
        name: type
        description: Type of test
        type: <td>string (http, httpcustom, tcp, ping, dns,
      responses:
        200:
          description: OK
      tags:
      - Single
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
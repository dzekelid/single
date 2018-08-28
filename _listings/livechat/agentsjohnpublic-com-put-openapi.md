---
swagger: "2.0"
x-collection-name: LiveChat
x-complete: 0
info:
  title: LiveChat Get a single agent details
  description: Returns complete details of the agent for the given LOGIN.
  version: 1.0.0
host: api.livechatinc.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tickets/5FUED:
    get:
      summary: Get single ticket
      description: Returns a single ticket item for the given TICKET_ID
      operationId: Tickets5FUEDGet
      x-api-path-slug: tickets5fued-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Ticket
  /goals/ABC123:
    get:
      summary: Get a single goal details
      description: Returns the goal details for the given GOAL_ID.
      operationId: GoalsABC123Get
      x-api-path-slug: goalsabc123-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Goal
      - Details
  /groups/{group_id}:
    get:
      summary: Get a single group details
      description: Returns group details for the given GROUP_ID.
      operationId: GroupsByGroupIdGet
      x-api-path-slug: groupsgroup-id-get
      parameters:
      - in: path
        name: group_id
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Group
      - Details
  /greetings/ABC123:
    get:
      summary: Get a single greeting
      description: Returns the specified greeting.
      operationId: GreetingsABC123Get
      x-api-path-slug: greetingsabc123-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Greeting
  /chats/ABC123:
    get:
      summary: Get single chat
      description: Returns a single chat item for the given CHAT_ID.
      operationId: ChatsABC123Get
      x-api-path-slug: chatsabc123-get
      parameters:
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Chat
  /agents/john@public.com:
    put:
      summary: Get a single agent details
      description: Returns complete details of the agent for the given LOGIN.
      operationId: AgentsJohnPublicComPut
      x-api-path-slug: agentsjohnpublic-com-put
      parameters:
      - in: formData
        name: job_title
      - in: header
        name: X-API-Version
      responses:
        200:
          description: OK
      tags:
      - Single
      - Agent
      - Details
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
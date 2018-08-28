---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: 'Steem WARNING: can only be used in Steem node or in scripts set_pending_transaction_callback'
  description: set_pending_transaction_callback
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /broadcast_transaction_with_callback:
    get:
      summary: 'WARNING: can only be used in Steem node or in scripts broadcast_transaction_with_callback'
      description: broadcast_transaction_with_callback
      operationId: broadcast-transaction-with-callback
      x-api-path-slug: broadcast-transaction-with-callback-get
      parameters:
      - in: query
        name: confirmationCallback
        description: confirmationCallback function
      - in: query
        name: trx
        description: transaction
      responses:
        200:
          description: OK
      tags:
      - 'WARNING:'
      - Can
      - Only
      - Be
      - Used
      - In
      - Steem
      - Node
      - In
      - Scripts
      - Broadcast
      - Transaction
      - Callback
  /set_max_block_age:
    get:
      summary: 'WARNING: can only be used in Steem node or in scripts set_max_block_age'
      description: set_max_block_age
      operationId: set-max-block-age
      x-api-path-slug: set-max-block-age-get
      parameters:
      - in: query
        name: maxBlockAge
        description: maxBlockAge
      responses:
        200:
          description: OK
      tags:
      - 'WARNING:'
      - Can
      - Only
      - Be
      - Used
      - In
      - Steem
      - Node
      - In
      - Scripts
      - Set
      - Max
      - Block
      - Age
  /set_subscribe_callback:
    get:
      summary: 'WARNING: can only be used in Steem node or in scripts set_subscribe_callback'
      description: set_subscribe_callback
      operationId: set-subscribe-callback-
      x-api-path-slug: set-subscribe-callback-get
      parameters:
      - in: query
        name: callback
        description: callback function
      - in: query
        name: clearFilter
        description: clearFilter
      responses:
        200:
          description: OK
      tags:
      - 'WARNING:'
      - Can
      - Only
      - Be
      - Used
      - In
      - Steem
      - Node
      - In
      - Scripts
      - Set
      - Subscribe
      - Callback
  /set_pending_transaction_callback:
    get:
      summary: 'WARNING: can only be used in Steem node or in scripts set_pending_transaction_callback'
      description: set_pending_transaction_callback
      operationId: set-pending-transaction-callback-
      x-api-path-slug: set-pending-transaction-callback-get
      parameters:
      - in: query
        name: cb
        description: callback function
      responses:
        200:
          description: OK
      tags:
      - 'WARNING:'
      - Can
      - Only
      - Be
      - Used
      - In
      - Steem
      - Node
      - In
      - Scripts
      - Set
      - Pending
      - Transaction
      - Callback
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
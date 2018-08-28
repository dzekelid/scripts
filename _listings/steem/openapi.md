swagger: "2.0"
x-collection-name: Steem
x-complete: 1
info:
  title: Interactive Steem API
  description: interactive-steem-api-lets-you-interact-with-steem-blockchain-and-make-a-request-get-output-and-start-implementing-new-apps-apis-have-default-parameters-set-to-get-you-started-and-see-how-request-works--api-list-is-compiled-from-steem-githubhttpsgithub-comsteemitsteem-1httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappapi-hpp-and-2httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappdatabase-api-hpp--if-you-want-to-contribute-documenting-detail-of-properties-and-output-contact-goodkarmahttpssteemit-chatdirectgoodkarma--you-can-also-check-full-list-here-steem-jshttpssteemjs-com
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
  /set_block_applied_callback:
    get:
      summary: 'WARNING: can only be used in Steem node or in scripts set_block_applied_callback'
      description: set_block_applied_callback
      operationId: set-block-applied-callback-
      x-api-path-slug: set-block-applied-callback-get
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
      - Block
      - Applied
      - Callback
  /cancel_all_subscriptions:
    get:
      summary: 'WARNING: can only be used in Steem node or in scripts cancel_all_subscriptions'
      description: cancel_all_subscriptions
      operationId: cancel-all-subscriptions-
      x-api-path-slug: cancel-all-subscriptions-get
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
      - Cancel
      - ""
      - Subscriptions
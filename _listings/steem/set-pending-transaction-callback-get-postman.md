{
  "info": {
    "name": "Steem WARNING: can only be used in Steem node or in scripts set_pending_transaction_callback",
    "_postman_id": "f0bb95c9-b1b8-4a69-8f30-410b49fd2875",
    "description": "set_pending_transaction_callback",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "WARNING:",
      "item": [
        {
          "id": "a3ec0aff-2bb8-43e1-bd8c-81f25d54a92b",
          "name": "broadcast-transaction-with-callback",
          "request": {
            "url": "http://api.steemjs.com/broadcast_transaction_with_callback?confirmationCallback=%7B%7D&trx=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "broadcast_transaction_with_callback"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf5954f2-ca2f-4c00-99c2-bb700f99d1bd"
            }
          ]
        },
        {
          "id": "06e9849f-46ef-485c-9d81-8090837d3093",
          "name": "set-subscribe-callback-",
          "request": {
            "url": "http://api.steemjs.com/set_subscribe_callback?callback=%7B%7D&clearFilter=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "set_subscribe_callback"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afbb8718-199b-446a-aa11-b16ad074b69f"
            }
          ]
        },
        {
          "id": "d1af2609-7c35-458b-91ab-2a97819ab876",
          "name": "set-pending-transaction-callback-",
          "request": {
            "url": "http://api.steemjs.com/set_pending_transaction_callback?cb=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "set_pending_transaction_callback"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef0e39e3-d23a-4ce7-84e0-7b469cb3d02e"
            }
          ]
        }
      ]
    }
  ]
}
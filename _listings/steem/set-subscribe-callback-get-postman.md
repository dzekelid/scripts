{
  "info": {
    "name": "Steem WARNING: can only be used in Steem node or in scripts set_subscribe_callback",
    "_postman_id": "88423ccd-481f-4612-a64b-0f12727314be",
    "description": "set_subscribe_callback",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "WARNING:",
      "item": [
        {
          "id": "ffc8d241-b73d-4ddb-8351-8db37f27b0fd",
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
              "id": "05ff9627-1748-4170-b261-4b0594e82604"
            }
          ]
        },
        {
          "id": "4d13935f-df9f-4d19-95c4-82332a8d8757",
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
              "id": "949fd693-b4f0-459c-990e-7bb9ec9f5358"
            }
          ]
        }
      ]
    }
  ]
}
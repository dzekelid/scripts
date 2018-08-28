{
  "info": {
    "name": "Steem WARNING: can only be used in Steem node or in scripts broadcast_transaction_with_callback",
    "_postman_id": "811d5911-0a64-4be1-b359-b353fbac0361",
    "description": "broadcast_transaction_with_callback",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Broadcast",
      "item": [
        {
          "id": "24af9f9e-7bad-4be4-b7c2-ebb1ab2de648",
          "name": "broadcast-transaction",
          "request": {
            "url": "http://api.steemjs.com/broadcast_transaction?trx=%7B%7D",
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
            "description": "broadcast_transaction"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53286124-a9ed-4d7f-af6f-a0fd24cabe00"
            }
          ]
        },
        {
          "id": "25f17659-bfcd-422f-8a26-19faf67ec517",
          "name": "broadcast-transaction-synchronous",
          "request": {
            "url": "http://api.steemjs.com/broadcast_transaction_synchronous?trx=%7B%7D",
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
            "description": "broadcast_transaction_synchronous"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88545d0c-2a54-49fb-83dd-fba72f2cca31"
            }
          ]
        },
        {
          "id": "6542fe3f-f217-4c88-9a4a-492bcc47c92a",
          "name": "broadcast-block",
          "request": {
            "url": "http://api.steemjs.com/broadcast_block?b=%7B%7D",
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
            "description": "broadcast_block"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2542b97-e30e-457a-9fd1-8b38b1f28d76"
            }
          ]
        }
      ]
    },
    {
      "name": "WARNING:",
      "item": [
        {
          "id": "a3bc4488-294d-473c-a10b-7729affcb6f1",
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
              "id": "474e04cb-c831-4884-b703-b089fd89deb7"
            }
          ]
        }
      ]
    }
  ]
}
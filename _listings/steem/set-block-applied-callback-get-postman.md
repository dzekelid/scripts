{
  "info": {
    "name": "Steem WARNING: can only be used in Steem node or in scripts set_block_applied_callback",
    "_postman_id": "c8ad5f85-7428-40b7-987a-4195d6080fdd",
    "description": "set_block_applied_callback",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "5eb9dc56-eb1f-46c8-b2d8-8c67d4eb9408",
          "name": "get-block",
          "request": {
            "url": "http://api.steemjs.com/get_block?blockNum=%7B%7D",
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
            "description": "get block"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9f165f9-9c58-4bce-a042-681709753103"
            }
          ]
        },
        {
          "id": "71543c2c-24e2-41f8-87a2-614cd3f56dbd",
          "name": "get-block-header",
          "request": {
            "url": "http://api.steemjs.com/get_block_header?blockNum=%7B%7D",
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
            "description": "get block header"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c7ca2afe-4570-4f85-b27f-1ff057ce9661"
            }
          ]
        },
        {
          "id": "67f6348f-179c-4118-8882-c0a04235c0a0",
          "name": "get-ops-in-block",
          "request": {
            "url": "http://api.steemjs.com/get_ops_in_block?blockNum=%7B%7D&onlyVirtual=%7B%7D",
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
            "description": "get_ops_in_block"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be5450f7-45d5-47f0-89ce-75eaa0d4bb54"
            }
          ]
        }
      ]
    },
    {
      "name": "Broadcast",
      "item": [
        {
          "id": "4892dc72-9cd9-4cd6-9d15-b454fd3c7885",
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
              "id": "29036ad8-f08e-42f8-acea-db46a41d7129"
            }
          ]
        }
      ]
    },
    {
      "name": "WARNING:",
      "item": [
        {
          "id": "cd636524-2df3-453a-8670-7814e1d985c0",
          "name": "set-max-block-age",
          "request": {
            "url": "http://api.steemjs.com/set_max_block_age?maxBlockAge=%7B%7D",
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
            "description": "set_max_block_age"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64e8d28a-91e1-44c2-b546-73ea4059cf7f"
            }
          ]
        },
        {
          "id": "74f0791f-fde5-4855-b558-09d7208d7e11",
          "name": "set-block-applied-callback-",
          "request": {
            "url": "http://api.steemjs.com/set_block_applied_callback?cb=%7B%7D",
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
            "description": "set_block_applied_callback"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1178c41b-6ee7-48cb-8253-f77359c1b466"
            }
          ]
        }
      ]
    }
  ]
}
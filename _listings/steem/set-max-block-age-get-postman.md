{
  "info": {
    "name": "Steem WARNING: can only be used in Steem node or in scripts set_max_block_age",
    "_postman_id": "d2a1eb97-8e5f-42ec-858c-fe7331b38e80",
    "description": "set_max_block_age",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "d6c97607-e18f-4433-8162-fa9e70da539a",
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
              "id": "92d2f42f-3469-4372-98d2-eee3fe5bcb36"
            }
          ]
        },
        {
          "id": "36429eef-1d29-412e-816b-199bdc76b2f1",
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
              "id": "e4ba11f6-2816-4398-851b-5d56f6d53e0c"
            }
          ]
        },
        {
          "id": "5ac31d72-f4f1-41f8-b191-9709c3aee490",
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
              "id": "0ed4efb3-50d1-4906-8a53-f7772b3be1d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Broadcast",
      "item": [
        {
          "id": "8ac9c5ca-76d7-402b-b572-d8ec6d5ca969",
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
              "id": "3ee9ff62-6d63-44b8-bd59-7337b47d2be1"
            }
          ]
        }
      ]
    },
    {
      "name": "WARNING:",
      "item": [
        {
          "id": "0f9d85d4-e63d-4400-80cf-d113efcbc9d6",
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
              "id": "1986584b-6e22-46c6-80e6-c55a7c42a6cb"
            }
          ]
        }
      ]
    }
  ]
}
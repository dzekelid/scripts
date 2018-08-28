{
  "info": {
    "name": "Steem WARNING: can only be used in Steem node or in scripts cancel_all_subscriptions",
    "_postman_id": "96fbdc36-7e33-45fa-8702-bc67006da2a4",
    "description": "cancel_all_subscriptions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "WARNING:",
      "item": [
        {
          "id": "22365839-03c9-44b5-972b-c3f005dae003",
          "name": "cancel-all-subscriptions-",
          "request": {
            "url": "http://api.steemjs.com/cancel_all_subscriptions",
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
            "description": "cancel_all_subscriptions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d5f2f89-4dd3-4bea-87e5-7d4c0ee786cf"
            }
          ]
        }
      ]
    }
  ]
}
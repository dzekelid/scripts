{
  "info": {
    "name": "Azure HDInsight API Script Actions Delete",
    "_postman_id": "0b7f5c0f-0c43-4679-9924-917fba950574",
    "description": "Deletes a given persisted script action of the cluster.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Script Actions",
      "item": [
        {
          "id": "af8dcca6-ecf6-4eb7-8fae-f6cb81828631",
          "name": "ScriptActions_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.HDInsight/clusters/:clusterName/scriptActions/:scriptName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "clusterName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "scriptName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a given persisted script action of the cluster."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd7e2e51-e0b3-4a70-b44d-c48bdf687b2f"
            }
          ]
        }
      ]
    }
  ]
}
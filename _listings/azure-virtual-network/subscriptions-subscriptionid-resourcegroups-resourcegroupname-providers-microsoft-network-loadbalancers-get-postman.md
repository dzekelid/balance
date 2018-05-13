{
  "info": {
    "name": "Azure Virtual Network API Load Balancers List",
    "_postman_id": "364773e5-66d1-472d-af58-5e706ab551ff",
    "description": "Gets all the load balancers in a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "load balancers",
      "item": [
        {
          "id": "f5a7dcf0-c99a-4034-994a-13762e2c3eef",
          "name": "LoadBalancers_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/loadBalancers"
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
                  "id": "resourceGroupName",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets all the load balancers in a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c1cc37f-5885-4c80-bbf2-3a8e3ed99b53"
            }
          ]
        }
      ]
    }
  ]
}
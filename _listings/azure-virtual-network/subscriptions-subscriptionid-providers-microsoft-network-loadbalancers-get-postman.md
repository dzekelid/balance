{
  "info": {
    "name": "Azure Virtual Network API Load Balancers List All",
    "_postman_id": "b63596fe-24f8-4f1d-9fa9-2b74db3f7006",
    "description": "Gets all the load balancers in a subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "load balancers all",
      "item": [
        {
          "id": "396a5e9c-6f08-4435-a893-c2fa3e6bfd0e",
          "name": "LoadBalancers_ListAll",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.Network/loadBalancers"
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
            "description": "Gets all the load balancers in a subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3da9e66f-07d6-47dc-9cdc-619ee1f1be21"
            }
          ]
        }
      ]
    }
  ]
}
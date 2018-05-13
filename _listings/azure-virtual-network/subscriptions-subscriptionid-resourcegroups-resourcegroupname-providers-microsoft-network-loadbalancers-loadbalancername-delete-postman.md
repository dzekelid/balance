{
  "info": {
    "name": "Azure Virtual Network API Load Balancers Delete",
    "_postman_id": "88bfe7cd-191b-4ad4-a555-7f0074cf3fad",
    "description": "Deletes the specified load balancer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "load balancers",
      "item": [
        {
          "id": "4416876c-c6c8-4c4e-a487-51ae3dc420cf",
          "name": "LoadBalancers_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/loadBalancers/:loadBalancerName"
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
                  "id": "loadBalancerName",
                  "value": "{}",
                  "type": "string"
                },
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified load balancer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54aec21f-e299-4844-965f-804384b1ed71"
            }
          ]
        }
      ]
    }
  ]
}
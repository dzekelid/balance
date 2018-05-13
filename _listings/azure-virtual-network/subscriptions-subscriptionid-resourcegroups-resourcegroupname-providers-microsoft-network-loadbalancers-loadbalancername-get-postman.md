{
  "info": {
    "name": "Azure Virtual Network API Load Balancers Get",
    "_postman_id": "3c50e104-f003-4427-b162-3beaade67362",
    "description": "Gets the specified load balancer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "load balancers",
      "item": [
        {
          "id": "5d52e4bd-1bfd-4aa0-8e7f-5ffa9525ab78",
          "name": "LoadBalancers_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/loadBalancers/:loadBalancerName"
              ],
              "query": [
                {
                  "key": "$expand",
                  "value": "%7B%7D",
                  "disabled": false
                },
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the specified load balancer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a4ef003-ab51-4e66-bde0-be78ab24d013"
            }
          ]
        }
      ]
    }
  ]
}
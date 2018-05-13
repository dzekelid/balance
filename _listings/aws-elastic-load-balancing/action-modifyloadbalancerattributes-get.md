---
swagger: "2.0"
info:
  title: AWS Elastic Load Balancing API Modify Load Balancer Attributes
  version: 1.0.0
  description: Modifies the specified attributes of the specified Application Load
    Balancer.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ModifyLoadBalancerAttributes:
    get:
      summary: ' Modify Load Balancer Attributes '
      description: Modifies the specified attributes of the specified Application
        Load Balancer
      operationId: modifyLoadBalancerAttributes
      parameters:
      - in: query
        name: Attributes.member.N
        description: The load balancer attributes
        type: string
      - in: query
        name: LoadBalancerArn
        description: The Amazon Resource Name (ARN) of the load balancer
        type: string
      responses:
        200:
          description: OK
      tags:
      - load balancers
definitions: []
x-collection-name: AWS Elastic Load Balancing
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
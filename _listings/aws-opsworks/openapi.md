---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AttachElasticLoadBalancer:
    get:
      summary: Attach Elastic Load Balancer
      description: Attaches an Elastic Load Balancing load balancer to a specified
        layer.
      operationId: attachElasticLoadBalancer
      x-api-path-slug: actionattachelasticloadbalancer-get
      parameters:
      - in: query
        name: ElasticLoadBalancerName
        description: The Elastic Load Balancing instances name
        type: string
      - in: query
        name: LayerId
        description: The ID of the layer that the Elastic Load Balancing instance
          is to be attached to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attach
      - Elastic
      - Load
      - Balancer
  /?Action=DescribeElasticLoadBalancers:
    get:
      summary: Describe Elastic Load Balancers
      description: Describes a stack's Elastic Load Balancing instances.
      operationId: describeElasticLoadBalancers
      x-api-path-slug: actiondescribeelasticloadbalancers-get
      parameters:
      - in: query
        name: LayerIds
        description: A list of layer IDs
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Elastic
      - Load
      - Balancers
  /?Action=DetachElasticLoadBalancer:
    get:
      summary: Detach Elastic Load Balancer
      description: Detaches a specified Elastic Load Balancing instance from its layer.
      operationId: detachElasticLoadBalancer
      x-api-path-slug: actiondetachelasticloadbalancer-get
      parameters:
      - in: query
        name: ElasticLoadBalancerName
        description: The Elastic Load Balancing instances name
        type: string
      - in: query
        name: LayerId
        description: The ID of the layer that the Elastic Load Balancing instance
          is attached to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Detach
      - Elastic
      - Load
      - Balancer
---
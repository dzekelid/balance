---
swagger: "2.0"
x-collection-name: Neblio
x-complete: 1
info:
  title: Neblio REST API Suite
  description: apis-for-interacting-with-ntp1-tokens--the-neblio-blockchain
  version: 1.0.0
host: ntp1node.nebl.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ins/addr/{address}/balance:
    get:
      summary: Returns address balance in sats
      description: Returns NEBL address balance in satoshis
      operationId: getAddressBalance
      x-api-path-slug: insaddraddressbalance-get
      parameters:
      - in: path
        name: address
        description: Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Returns
      - Address
      - Balance
      - In
      - Sats
  /ins/addr/{address}/unconfirmedBalance:
    get:
      summary: Returns address unconfirmed balance in sats
      description: Returns NEBL address unconfirmed balance in satoshis
      operationId: getAddressUnconfirmedBalance
      x-api-path-slug: insaddraddressunconfirmedbalance-get
      parameters:
      - in: path
        name: address
        description: Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Returns
      - Address
      - Unconfirmed
      - Balance
      - In
      - Sats
  /testnet/ins/addr/{address}/balance:
    get:
      summary: Returns address balance in sats
      description: Returns NEBL address balance in satoshis
      operationId: testnet_getAddressBalance
      x-api-path-slug: testnetinsaddraddressbalance-get
      parameters:
      - in: path
        name: address
        description: Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Returns
      - Address
      - Balance
      - In
      - Sats
  /testnet/ins/addr/{address}/unconfirmedBalance:
    get:
      summary: Returns address unconfirmed balance in sats
      description: Returns NEBL address unconfirmed balance in satoshis
      operationId: testnet_getAddressUnconfirmedBalance
      x-api-path-slug: testnetinsaddraddressunconfirmedbalance-get
      parameters:
      - in: path
        name: address
        description: Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Returns
      - Address
      - Unconfirmed
      - Balance
      - In
      - Sats
---
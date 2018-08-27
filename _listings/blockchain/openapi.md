swagger: "2.0"
x-collection-name: Blockchain
x-complete: 1
info:
  title: Blockchain
  version: 1.0.0
host: blockchain.info
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /balance:
    get:
      summary: Balance
      description: Returns current balance
      operationId: getBalance
      x-api-path-slug: balance-get
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Balance
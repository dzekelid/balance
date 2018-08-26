---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/account/{id}/balances:
    get:
      summary: Get balance of an account
      description: Get balance of an account.
      operationId: Account_GetAccountBalancesByidBystartDateByendDate
      x-api-path-slug: apiaccountidbalances-get
      parameters:
      - in: query
        name: endDate
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: startDate
      responses:
        200:
          description: OK
      tags:
      - Balance
      - Of
      - Account
  /api/accountingsystem/systembalance:
    get:
      summary: Gets accounting system balance
      description: Gets accounting system balance.
      operationId: AccountingSystem_GetSystemBalance
      x-api-path-slug: apiaccountingsystemsystembalance-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Accounting
      - System
      - Balance
---
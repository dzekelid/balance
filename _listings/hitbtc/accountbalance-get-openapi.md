---
swagger: "2.0"
x-collection-name: HitBTC
x-complete: 0
info:
  title: HitBTC Get Main Acccount Balance
  description: Get main acccount balance.
  version: 1.0.0
basePath: /api/2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /trading/balance:
    get:
      summary: Get Trading Balance
      description: Get trading balance.
      operationId: getTradingBalance
      x-api-path-slug: tradingbalance-get
      responses:
        200:
          description: OK
      tags:
      - Trading
      - Balance
  /account/balance:
    get:
      summary: Get Main Acccount Balance
      description: Get main acccount balance.
      operationId: getAccountBalance
      x-api-path-slug: accountbalance-get
      responses:
        200:
          description: OK
      tags:
      - Main
      - Acccount
      - Balance
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
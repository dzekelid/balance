swagger: "2.0"
x-collection-name: HitBTC
x-complete: 1
info:
  title: HitBTC API
  description: create-api-keys-in-your-profile-httpshitbtc-comsettingsapikeys-and-use-public-api-key-as-username-and-secret-as-password-to-authorize-
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
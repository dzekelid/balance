---
swagger: "2.0"
x-collection-name: Intuit
x-complete: 1
info:
  title: QuickBooks Online V3 API
  description: the-quickbooks-online-accounting-api-is-a-restful-api-that-is-used-to-access-quickbooks-companies-docs-
  version: 1.0.0
host: DefaultParameterValue
basePath: /v3/company/DefaultParameterValue
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reports/CustomerBalanceDetail:
    get:
      summary: Get Reports Customer Balance Detail
      description: |-
        Report - CustomerBalance Detail
        Method : GET

        The information below provides a reference on how to access the Customer Balance Detail report from the QuickBooks Online Report Service.
      operationId: getReportsCustomerbalancedetail
      x-api-path-slug: reportscustomerbalancedetail-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Reports
      - Customer
      - Balance
      - Detail
  /reports/VendorBalance:
    get:
      summary: Get Reports Vendor Balance
      description: "Report - Vendor Balance \nMethod : GET\n\nDocs - https://developer.intuit.com/docs/api/accounting/vendor%20balance"
      operationId: getReportsVendorbalance
      x-api-path-slug: reportsvendorbalance-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Reports
      - Vendor
      - Balance
  /reports/CustomerBalance:
    get:
      summary: Get Reports Customer Balance
      description: |-
        Report - CustomerBalance
        Method : GET
      operationId: getReportsCustomerbalance
      x-api-path-slug: reportscustomerbalance-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Reports
      - Customer
      - Balance
  /reports/TrialBalance:
    get:
      summary: Get Reports Trial Balance
      description: "Report - Trial Balance \nMethod : GET\n\nDocs - https://developer.intuit.com/docs/api/accounting/trial%20balance"
      operationId: getReportsTrialbalance
      x-api-path-slug: reportstrialbalance-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Reports
      - Trial
      - Balance
---
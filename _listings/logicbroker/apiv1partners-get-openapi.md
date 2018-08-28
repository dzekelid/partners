---
swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 0
info:
  title: Logic Broker CommerceAPI Retrieve a list of trading partners.
  version: 1.0.0
  description: Request rate limited to 10 requests per second with bursts up to 100
    requests.
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Partners:
    get:
      summary: Retrieve a list of trading partners.
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Partner_GetPartners
      x-api-path-slug: apiv1partners-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Trading
      - Partners
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
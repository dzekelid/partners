---
swagger: "2.0"
x-collection-name: Netatmo
x-complete: 0
info:
  title: Netatmo Get Partnerdevices
  description: The method partnerdevices returns the list of device_id to which your
    partner application has access to.
  termsOfService: https://dev.netatmo.com/dev/resources/legal/introduction
  contact:
    name: Netatmo
    email: contact-api@netatmo.com
  version: 1.1.1
host: api.netatmo.net
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /partnerdevices:
    get:
      summary: Get Partnerdevices
      description: The method partnerdevices returns the list of device_id to which
        your partner application has access to.
      operationId: partnerdevices
      x-api-path-slug: partnerdevices-get
      responses:
        200:
          description: OK
      tags:
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
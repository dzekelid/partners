---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Delete Event Eventid Partner
  version: 1.0.0
  description: Delete event eventid partner.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/event/{eventId}/partner:
    post:
      summary: Post Event Eventid Partner
      description: Post event eventid partner.
      operationId: postApiV1EventEventPartner
      x-api-path-slug: apiv1eventeventidpartner-post
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: file
      responses:
        200:
          description: OK
      tags:
      - Event
      - Eventid
      - Partner
    delete:
      summary: Delete Event Eventid Partner
      description: Delete event eventid partner.
      operationId: deleteApiV1EventEventPartner
      x-api-path-slug: apiv1eventeventidpartner-delete
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: eventId
      responses:
        200:
          description: OK
      tags:
      - Event
      - Eventid
      - Partner
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
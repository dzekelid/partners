swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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
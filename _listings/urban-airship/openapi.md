swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 1
info:
  title: Urban Airship
  description: the-urban-airships-api-powers-mobile-applications-with-push-rich-push-inapp-purchases-and-subscription-services-
  version: v3
host: go.urbanairship.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /partner/apps:
    get:
      summary: Get Partner Apps
      description: List applications.
      operationId: partner.apps.get
      x-api-path-slug: partnerapps-get
      parameters:
      - in: query
        name: device_token
        description: A specific device token
      - in: query
        name: tag
        description: Tags can be of any format you wish, but we recommend that they
          be URL-safe in order to make less work for you
      responses:
        200:
          description: OK
      tags:
      - Partner
      - Apps
    post:
      summary: Post Partner Apps
      description: Adds a new application.
      operationId: partner.apps.post
      x-api-path-slug: partnerapps-post
      parameters:
      - in: header
        name: Content-Type
        description: Content type
      - in: query
        name: Content-Type
        description: Content type
      responses:
        200:
          description: OK
      tags:
      - Partner
      - Apps
  /partner/apps/{app_id}:
    put:
      summary: Put Partner Apps App
      description: Updates an application.
      operationId: partner.apps.app_id.put
      x-api-path-slug: partnerappsapp-id-put
      parameters:
      - in: query
        name: app_id
        description: A specific application
      - in: path
        name: app_id
      - in: header
        name: Content-Type
        description: Content type
      - in: query
        name: Content-Type
        description: Content type
      responses:
        200:
          description: OK
      tags:
      - Partner
      - Apps
      - App
      - Id
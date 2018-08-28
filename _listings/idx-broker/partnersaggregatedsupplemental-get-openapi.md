---
swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 0
info:
  title: IDX Broker Get Partners Aggregated Supplemental
  description: Get a list of supplemental (non-MLS) properties.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /partners/aggregatedagents:
    get:
      summary: Get Partners Aggregated Agents
      description: Get a list of all agents for your clients.
      operationId: PartnersAggregatedagentsGet
      x-api-path-slug: partnersaggregatedagents-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Agents
  /partners/aggregatedfeatured:
    get:
      summary: Get Partners Aggregated Featured
      description: Get a list of featured MLS properties.
      operationId: PartnersAggregatedfeaturedGet
      x-api-path-slug: partnersaggregatedfeatured-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Featured
  /partners/aggregatedleads:
    get:
      summary: Get Partners Aggregated Leads
      description: Get a list of all leads.
      operationId: PartnersAggregatedleadsGet
      x-api-path-slug: partnersaggregatedleads-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Leads
  /partners/aggregatedleadtraffic:
    get:
      summary: Get Partners Aggregated Lead Traffic
      description: Get a list of all leads traffic history.
      operationId: PartnersAggregatedleadtrafficGet
      x-api-path-slug: partnersaggregatedleadtraffic-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Lead
      - Traffic
  /partners/aggregatedlistingstatus:
    get:
      summary: Get Partners Aggregated Listing Status
      description: This method gives the status for all MLS listings (not supplemental)
        broken down by client account ID. This includes sold/pending listings with
        an unknown status which are not usually returned by sold/pending api methods.
        This is helpful if you need to know when previously gathered featured properties
        have left the market.
      operationId: PartnersAggregatedlistingstatusGet
      x-api-path-slug: partnersaggregatedlistingstatus-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Listing
      - Status
  /partners/aggregatedproperties:
    get:
      summary: Get Partners Aggregated Properties
      description: Get a list of all lead saved properties.
      operationId: PartnersAggregatedpropertiesGet
      x-api-path-slug: partnersaggregatedproperties-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Properties
  /partners/aggregatedsearches:
    get:
      summary: Get Partners Aggregated Searches
      description: Get a list of all lead saved searches.
      operationId: PartnersAggregatedsearchesGet
      x-api-path-slug: partnersaggregatedsearches-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Searches
  /partners/aggregatedsoldpending:
    get:
      summary: Get Partners Aggregated Sold Pending
      description: Get a list of sold/pending MLS properties.
      operationId: PartnersAggregatedsoldpendingGet
      x-api-path-slug: partnersaggregatedsoldpending-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Sold
      - Pending
  /partners/aggregatedsupplemental:
    get:
      summary: Get Partners Aggregated Supplemental
      description: Get a list of supplemental (non-MLS) properties.
      operationId: PartnersAggregatedsupplementalGet
      x-api-path-slug: partnersaggregatedsupplemental-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Aggregated
      - Supplemental
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
swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 1
info:
  title: IDX API 1.4.0 Test Runner
  description: idx-broker-api-calls-in-version-1-4-0required-environment-variable-url-environment-variable-for-request-headers-environment-variable-partner-key-client-account-with-at-least-one-featured-listingtests-are-in-this-order-as-variables-such-as-listing-id-and-approved-mls-are-passed-to-subsequent-api-calls-
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
  /partners/clients:
    get:
      summary: Get Partners Clients
      description: A list of clients available to a given partner. The list of clients
        can be filtered by GET values.
      operationId: PartnersClientsGet
      x-api-path-slug: partnersclients-get
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
      - Clients
  /partners/listcomponents:
    get:
      summary: Get Partners List Components
      description: This is a simple, access anywhere, method for getting a list of
        all API components available.
      operationId: PartnersListcomponentsGet
      x-api-path-slug: partnerslistcomponents-get
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
      - List
      - Components
  /partners/listmethods:
    get:
      summary: Get Partners List Methods
      description: A simple method for listing all available methods in the current
        API component.
      operationId: PartnersListmethodsGet
      x-api-path-slug: partnerslistmethods-get
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
      - List
      - Methods
  /partners/propertytypes:
    get:
      summary: Get Partners Property Types
      description: Gives the names and IDs of all available property types. This method
        differs from the property type lookup method in the client API component in
        that it can look up property types for any active Platinum MLS, not just those
        for which the client is a member.
      operationId: PartnersPropertytypesGet
      x-api-path-slug: partnerspropertytypes-get
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
      - Property
      - Types
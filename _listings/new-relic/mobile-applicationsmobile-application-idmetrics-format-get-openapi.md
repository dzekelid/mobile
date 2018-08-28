---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Get Mobile Applications Mobile Application  Metrics. Format
  version: 1.0.0
  description: |-
    Return a list of known metrics and their value names for the given resource.

    See our documentation for a discussion
    on  output pagination
    and for examples of requesting and using metric values.
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mobile_applications.{format}:
    get:
      summary: Get Mobile Applications. Format
      description: |-
        This API endpoint returns a list of the Mobile Applications associated with your New Relic account.

        MobileApplications can be filtered by their name, or by the application IDs.
      operationId: getMobileApplications.Format
      x-api-path-slug: mobile-applications-format-get
      responses:
        200:
          description: OK
      tags:
      - Mobile
      - Applications.
      - Format
  /mobile_applications/{id}.{format}:
    get:
      summary: Get Mobile Applications  . Format
      description: This API endpoint returns a single Mobile Application, identified
        by ID. The time range for summary data is the last 30 minutes.
      operationId: getMobileApplications.Format
      x-api-path-slug: mobile-applicationsid-format-get
      parameters:
      - in: path
        name: id
        description: Mobile Application ID
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Mobile
      - Applications
      - ""
      - .
      - Format
  /mobile_applications/{mobile_application_id}/metrics.{format}:
    get:
      summary: Get Mobile Applications Mobile Application  Metrics. Format
      description: |-
        Return a list of known metrics and their value names for the given resource.

        See our documentation for a discussion
        on  output pagination
        and for examples of requesting and using metric values.
      operationId: getMobileApplicationsMobileApplicationMetrics.Format
      x-api-path-slug: mobile-applicationsmobile-application-idmetrics-format-get
      parameters:
      - in: query
        name: cursor
        description: Cursor for next page (replacing page param)
        type: string
      - in: path
        name: mobile_application_id
        description: Mobile application ID
        type: integer
      - in: query
        name: name
        description: Filter metrics by name
        type: string
      - in: query
        name: page
        description: Pagination index (will be deprecated)
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Mobile
      - Applications
      - Mobile
      - Application
      - ""
      - Metrics.
      - Format
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
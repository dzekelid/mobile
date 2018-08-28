---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Get Mobile Applications. Format
  version: 1.0.0
  description: |-
    This API endpoint returns a list of the Mobile Applications associated with your New Relic account.

    MobileApplications can be filtered by their name, or by the application IDs.
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
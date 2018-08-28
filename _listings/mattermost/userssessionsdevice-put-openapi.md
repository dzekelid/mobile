---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Attach mobile device
  description: |-
    Attach a mobile device id to the currently logged in session. This will enable push notiofications for a user, if configured by the server.
    ##### Permissions
    Must be authenticated.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/sessions/device:
    put:
      summary: Attach mobile device
      description: |-
        Attach a mobile device id to the currently logged in session. This will enable push notiofications for a user, if configured by the server.
        ##### Permissions
        Must be authenticated.
      operationId: attach-a-mobile-device-id-to-the-currently-logged-in-session-this-will-enable-push-notiofications-fo
      x-api-path-slug: userssessionsdevice-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Attach
      - Mobile
      - Device
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
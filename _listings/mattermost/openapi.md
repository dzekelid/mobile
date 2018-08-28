swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
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
---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Confirm identity registration
  description: Confirm identity registration
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/v1/identities/forgot_password:
    post:
      summary: Forgot identity password
      description: Forgot identity password
      operationId: postUserV1IdentitiesForgot_password
      x-api-path-slug: userv1identitiesforgot-password-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Forgot
      - identity
      - password
  /user/v1/identities/register:
    post:
      summary: Register identity
      description: Register identity
      operationId: postUserV1IdentitiesRegister
      x-api-path-slug: userv1identitiesregister-post
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Register
      - identity
  /user/v1/identities/forgot_password/confirm:
    post:
      summary: Confirm identity password change
      description: Confirm identity password change
      operationId: postUserV1IdentitiesForgot_passwordConfirm
      x-api-path-slug: userv1identitiesforgot-passwordconfirm-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Confirm
      - identity
      - password
      - change
  /user/v1/identities/register/confirm:
    post:
      summary: Confirm identity registration
      description: Confirm identity registration
      operationId: postUserV1IdentitiesRegisterConfirm
      x-api-path-slug: userv1identitiesregisterconfirm-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Confirm
      - identity
      - registration
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
---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 0
info:
  title: AWS Simple Email Service API Delete Identity Policy
  version: 1.0.0
  description: Deletes the specified sending authorization policy for the given identity
    (an email address or a domain).
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteIdentity:
    get:
      summary: Delete Identity
      description: Deletes the specified identity (an email address or a domain) from
        the list of verified identities.
      operationId: deleteIdentity
      x-api-path-slug: actiondeleteidentity-get
      parameters:
      - in: query
        name: Identity
        description: The identity to be removed from the list of identities for the
          AWS Account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=DeleteIdentityPolicy:
    get:
      summary: Delete Identity Policy
      description: Deletes the specified sending authorization policy for the given
        identity (an email address or a domain).
      operationId: deleteIdentityPolicy
      x-api-path-slug: actiondeleteidentitypolicy-get
      parameters:
      - in: query
        name: Identity
        description: The identity that is associated with the policy that you want
          to delete
        type: string
      - in: query
        name: PolicyName
        description: The name of the policy to be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
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
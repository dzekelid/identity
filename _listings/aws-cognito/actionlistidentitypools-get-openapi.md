---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API List Identity Pools
  version: 1.0.0
  description: Lists all of the Cognito identity pools registered for your account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateIdentityPool:
    get:
      summary: Create Identity Pool
      description: Creates a new identity pool.
      operationId: createIdentityPool
      x-api-path-slug: actioncreateidentitypool-get
      parameters:
      - in: query
        name: AllowUnauthenticatedIdentities
        description: TRUE if the identity pool supports unauthenticated logins
        type: string
      - in: query
        name: CognitoIdentityProviders
        description: An array of Amazon Cognito Identity user pools and their client
          IDs
        type: string
      - in: query
        name: DeveloperProviderName
        description: The domain by which Cognito will refer to your users
        type: string
      - in: query
        name: IdentityPoolName
        description: A string that you provide
        type: string
      - in: query
        name: OpenIdConnectProviderARNs
        description: A list of OpendID Connect provider ARNs
        type: string
      - in: query
        name: SamlProviderARNs
        description: An array of Amazon Resource Names (ARNs) of the SAML provider
          for your identity         pool
        type: string
      - in: query
        name: SupportedLoginProviders
        description: Optional key:value pairs mapping provider names to provider app
          IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=DeleteIdentityPool:
    get:
      summary: Delete Identity Pool
      description: Deletes a user pool.
      operationId: deleteIdentityPool
      x-api-path-slug: actiondeleteidentitypool-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=DescribeIdentityPool:
    get:
      summary: Describe Identity Pool
      description: |-
        Gets details about a particular identity pool, including the pool name, ID
                 description, creation date, and current number of users.
      operationId: describeIdentityPool
      x-api-path-slug: actiondescribeidentitypool-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=GetIdentityPoolRoles:
    get:
      summary: Get Identity Pool Roles
      description: Gets the roles for an identity pool.
      operationId: getIdentityPoolRoles
      x-api-path-slug: actiongetidentitypoolroles-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool Roles
  /?Action=ListIdentityPools:
    get:
      summary: List Identity Pools
      description: Lists all of the Cognito identity pools registered for your account.
      operationId: listIdentityPools
      x-api-path-slug: actionlistidentitypools-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of identities to return
        type: string
      - in: query
        name: NextToken
        description: A pagination token
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
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
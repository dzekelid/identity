---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 0
info:
  title: Azure API Management API IdentityProviders Update
  description: Updates an existing IdentityProvider configuration.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders
  : get:
      summary: IdentityProviders ListByService
      description: Lists a collection of Identity Provider configured in the specified
        service instance.
      operationId: IdentityProviders_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityproviders-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  : get:
      summary: IdentityProviders Get
      description: Gets the configuration details of the identity Provider configured
        in specified service instance.
      operationId: IdentityProviders_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
    put:
      summary: IdentityProviders CreateOrUpdate
      description: Creates or Updates the IdentityProvider configuration.
      operationId: IdentityProviders_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
    patch:
      summary: IdentityProviders Update
      description: Updates an existing IdentityProvider configuration.
      operationId: IdentityProviders_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the identity provider configuration
          to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
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
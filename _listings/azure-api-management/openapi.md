---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 1
info:
  title: ApiManagementClient
  description: use-these-rest-apis-for-performing-operations-on-user-entity-in-azure-api-management-deployment--the-user-entity-in-api-management-represents-the-developers-that-call-the-apis-of-the-products-to-which-they-are-subscribed-
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
    delete:
      summary: IdentityProviders Delete
      description: Deletes the specified identity provider configuration.
      operationId: IdentityProviders_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the backend to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
---
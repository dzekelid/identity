---
name: AWS Cognito
x-slug: aws-cognito
description: Amazon Cognito lets you easily add user sign-up and sign-in to your mobile
  and web apps. With Amazon Cognito, you also have the options to authenticate users
  through social identity providers such as Facebook, Twitter, or Amazon, with SAML
  identity solutions, or by using your own identity system. In addition, Amazon Cognito
  enables you to save data locally on users devices, allowing your applications to
  work even when the devices are offline. You can then synchronize data across users
  devices so that their app experience remains consistent regardless of the device
  they use. With Amazon Cognito, you can focus on creating great app experiences instead
  of worrying about building, securing, and scaling a solution to handle user management,
  authentication, and sync across devices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Identity
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Cognito API Create Identity Pool
  x-api-slug: aws-cognito-api
  description: Creates a new identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=CreateIdentityPool
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actioncreateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actioncreateidentitypool-get-openapi.md
- name: AWS Cognito API Delete Identity Pool
  x-api-slug: aws-cognito-api
  description: Deletes a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DeleteIdentityPool
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiondeleteidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiondeleteidentitypool-get-openapi.md
- name: AWS Cognito API Describe Identity Pool
  x-api-slug: aws-cognito-api
  description: |-
    Gets details about a particular identity pool, including the pool name, ID
             description, creation date, and current number of users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeIdentityPool
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiondescribeidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiondescribeidentitypool-get-openapi.md
- name: AWS Cognito API Get Identity Pool Roles
  x-api-slug: aws-cognito-api
  description: Gets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetIdentityPoolRoles
  tags: Identity Pool Roles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiongetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiongetidentitypoolroles-get-openapi.md
- name: AWS Cognito API List Identity Pools
  x-api-slug: aws-cognito-api
  description: Lists all of the Cognito identity pools registered for your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListIdentityPools
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionlistidentitypools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionlistidentitypools-get-openapi.md
- name: AWS Cognito API Set Identity Pool Roles
  x-api-slug: aws-cognito-api
  description: Sets the roles for an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=SetIdentityPoolRoles
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionsetidentitypoolroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionsetidentitypoolroles-get-openapi.md
- name: AWS Cognito API Update Identity Pool
  x-api-slug: aws-cognito-api
  description: Updates a user pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=UpdateIdentityPool
  tags: Identity Pool
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionupdateidentitypool-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionupdateidentitypool-get-openapi.md
- name: AWS Cognito API Describe Identity Pool Usage
  x-api-slug: aws-cognito-api
  description: Gets usage details (for example, data storage) about a particular identity
    pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeIdentityPoolUsage
  tags: Identity Pool Usage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiondescribeidentitypoolusage-get-openapi.md
- name: AWS Cognito API Describe Identity Usage
  x-api-slug: aws-cognito-api
  description: Gets usage information for an identity, including number of datasets
    and data usage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=DescribeIdentityUsage
  tags: Identity Pool Usage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiondescribeidentityusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiondescribeidentityusage-get-openapi.md
- name: AWS Cognito API Get Identity Pool Configuration
  x-api-slug: aws-cognito-api
  description: Gets the configuration settings of an identity pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=GetIdentityPoolConfiguration
  tags: Identity Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actiongetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito API List Identity Pool Usage
  x-api-slug: aws-cognito-api
  description: Gets a list of identity pools registered with Cognito.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=ListIdentityPoolUsage
  tags: Identity Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionlistidentitypoolusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionlistidentitypoolusage-get-openapi.md
- name: AWS Cognito API Set Identity Pool Configuration
  x-api-slug: aws-cognito-api
  description: Sets the necessary configuration for push sync.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https://///?Action=SetIdentityPoolConfiguration
  tags: Identity Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/actionsetidentitypoolconfiguration-get-openapi.md
- name: AWS Cognito API
  x-api-slug: aws-cognito-api
  description: Amazon Cognito lets you easily add user sign-up and sign-in to your
    mobile and web apps. With Amazon Cognito, you also have the options to authenticate
    users through social identity providers such as Facebook, Twitter, or Amazon,
    with SAML identity solutions, or by using your own identity system. In addition,
    Amazon Cognito enables you to save data locally on users devices, allowing your
    applications to work even when the devices are offline. You can then synchronize
    data across users devices so that their app experience remains consistent regardless
    of the device they use. With Amazon Cognito, you can focus on creating great app
    experiences instead of worrying about building, securing, and scaling a solution
    to handle user management, authentication, and sync across devices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-cognito.png
  humanURL: https://aws.amazon.com/cognito/
  baseURL: https:///
  tags: Identity
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-cognito/openapi.md
x-common:
- type: x-blog
  url: https://aws.amazon.com/cognito/dev-resources/#blogposts
- type: x-documentation
  url: http://docs.aws.amazon.com/cognito-user-identity-pools/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitoidentity/latest/APIReference/Welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/cognitosync/latest/APIReference/Welcome.html
- type: x-faq
  url: http://aws.amazon.com/cognito/faqs
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=173
- type: x-pricing
  url: http://aws.amazon.com/cognito/pricing
- type: x-sdk
  url: https://aws.amazon.com/cognito/dev-resources/#documentation
- type: x-slides
  url: https://aws.amazon.com/cognito/dev-resources/#slides
- type: x-videos
  url: https://aws.amazon.com/cognito/dev-resources/#videos
- type: x-website
  url: https://aws.amazon.com/cognito/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
---
name: AWS Simple Email Service
x-slug: aws-simple-email-service
description: Amazon Simple Email Service (Amazon SES) is a cost-effective email service
  built on the reliable and scalable infrastructure that Amazon.com developed to serve
  its own customer base. With Amazon SES, you can send and receive email with no required
  minimum commitments &ndash; you pay as you go, and you only pay for what you use.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Identity
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Simple Email Service API Delete Identity
  x-api-slug: aws-simple-email-service-api
  description: Deletes the specified identity (an email address or a domain) from
    the list of verified identities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=DeleteIdentity
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiondeleteidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiondeleteidentity-get-openapi.md
- name: AWS Simple Email Service API Delete Identity Policy
  x-api-slug: aws-simple-email-service-api
  description: Deletes the specified sending authorization policy for the given identity
    (an email address or a domain).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=DeleteIdentityPolicy
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiondeleteidentitypolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiondeleteidentitypolicy-get-openapi.md
- name: AWS Simple Email Service API Get Identity Dkim Attributes
  x-api-slug: aws-simple-email-service-api
  description: Returns the current status of Easy DKIM signing for an entity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=GetIdentityDkimAttributes
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentitydkimattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentitydkimattributes-get-openapi.md
- name: AWS Simple Email Service API Get Identity Mail From Domain Attributes
  x-api-slug: aws-simple-email-service-api
  description: Returns the custom MAIL FROM attributes for a list of identities (email
    addresses and/or domains).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=GetIdentityMailFromDomainAttributes
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentitymailfromdomainattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentitymailfromdomainattributes-get-openapi.md
- name: AWS Simple Email Service API Get Identity Notification Attributes
  x-api-slug: aws-simple-email-service-api
  description: Given a list of verified identities (email addresses and/or domains),
    returns a structure describing identity notification attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=GetIdentityNotificationAttributes
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentitynotificationattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentitynotificationattributes-get-openapi.md
- name: AWS Simple Email Service API Get Identity Policies
  x-api-slug: aws-simple-email-service-api
  description: Returns the requested sending authorization policies for the given
    identity (an email address or a domain).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=GetIdentityPolicies
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentitypolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentitypolicies-get-openapi.md
- name: AWS Simple Email Service API Get Identity Verification Attributes
  x-api-slug: aws-simple-email-service-api
  description: Given a list of identities (email addresses and/or domains), returns
    the verification status and (for domain identities) the verification token for
    each identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=GetIdentityVerificationAttributes
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentityverificationattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actiongetidentityverificationattributes-get-openapi.md
- name: AWS Simple Email Service API List Identities
  x-api-slug: aws-simple-email-service-api
  description: Returns a list containing all of the identities (email addresses and
    domains) for your AWS account, regardless of verification status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=ListIdentities
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionlistidentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionlistidentities-get-openapi.md
- name: AWS Simple Email Service API List Identity Policies
  x-api-slug: aws-simple-email-service-api
  description: Returns a list of sending authorization policies that are attached
    to the given identity (an email address or a domain).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=ListIdentityPolicies
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionlistidentitypolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionlistidentitypolicies-get-openapi.md
- name: AWS Simple Email Service API Put Identity Policy
  x-api-slug: aws-simple-email-service-api
  description: Adds or updates a sending authorization policy for the specified identity
    (an email address or a domain).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=PutIdentityPolicy
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionputidentitypolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionputidentitypolicy-get-openapi.md
- name: AWS Simple Email Service API Set Identity Dkim Enabled
  x-api-slug: aws-simple-email-service-api
  description: |-
    Enables or disables Easy DKIM signing of email sent from an identity:If Easy DKIM
                signing is enabled for a domain name identity (e.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=SetIdentityDkimEnabled
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentitydkimenabled-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentitydkimenabled-get-openapi.md
- name: AWS Simple Email Service API Set Identity Feedback Forwarding Enabled
  x-api-slug: aws-simple-email-service-api
  description: Given an identity (an email address or a domain), enables or disables
    whether Amazon SES forwards bounce and complaint notifications as email.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=SetIdentityFeedbackForwardingEnabled
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentityfeedbackforwardingenabled-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentityfeedbackforwardingenabled-get-openapi.md
- name: AWS Simple Email Service API Set Identity Headers In Notifications Enabled
  x-api-slug: aws-simple-email-service-api
  description: "Given an identity (an email address or a domain), sets whether Amazon
    SES includes \n            the original email headers in the Amazon Simple Notification
    Service (Amazon SNS) notifications \n            of a specified type."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=SetIdentityHeadersInNotificationsEnabled
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentityheadersinnotificationsenabled-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentityheadersinnotificationsenabled-get-openapi.md
- name: AWS Simple Email Service API Set Identity Mail From Domain
  x-api-slug: aws-simple-email-service-api
  description: Enables or disables the custom MAIL FROM domain setup for a verified
    identity (an email address or a domain).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=SetIdentityMailFromDomain
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentitymailfromdomain-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentitymailfromdomain-get-openapi.md
- name: AWS Simple Email Service API Set Identity Notification Topic
  x-api-slug: aws-simple-email-service-api
  description: |-
    Given an identity (an email address or a domain), sets the Amazon Simple Notification Service (Amazon SNS) topic to which Amazon SES will publish
            bounce, complaint, and/or delivery notifications for emails sent with that identity as the Source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=SetIdentityNotificationTopic
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentitynotificationtopic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionsetidentitynotificationtopic-get-openapi.md
- name: AWS Simple Email Service API Verify Domain Identity
  x-api-slug: aws-simple-email-service-api
  description: Verifies a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=VerifyDomainIdentity
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionverifydomainidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionverifydomainidentity-get-openapi.md
- name: AWS Simple Email Service API Verify Email Identity
  x-api-slug: aws-simple-email-service-api
  description: Verifies an email address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: ://///?Action=VerifyEmailIdentity
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionverifyemailidentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/actionverifyemailidentity-get-openapi.md
- name: AWS Simple Email Service API
  x-api-slug: aws-simple-email-service-api
  description: Amazon Simple Email Service (Amazon SES) is a cost-effective email
    service built on the reliable and scalable infrastructure that Amazon.com developed
    to serve its own customer base. With Amazon SES, you can send and receive email
    with no required minimum commitments &ndash; you pay as you go, and you only pay
    for what you use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSES.png
  humanURL: https://aws.amazon.com/ses/
  baseURL: :///
  tags: Identity
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/identity/master/_listings/aws-simple-email-service/openapi.md
x-common:
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/Amazon-SES
- type: x-documentation
  url: http://docs.aws.amazon.com/ses/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/ses/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=90
- type: x-getting-started
  url: https://aws.amazon.com/ses/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/ses/pricing/
- type: x-sdk
  url: http://aws.amazon.com/tools
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-tools
  url: http://aws.amazon.com/developertools/Amazon-SES
- type: x-website
  url: https://aws.amazon.com/ses/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
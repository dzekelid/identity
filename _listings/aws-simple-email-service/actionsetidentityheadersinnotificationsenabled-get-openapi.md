---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 0
info:
  title: AWS Simple Email Service API Set Identity Headers In Notifications Enabled
  version: 1.0.0
  description: "Given an identity (an email address or a domain), sets whether Amazon
    SES includes \n            the original email headers in the Amazon Simple Notification
    Service (Amazon SNS) notifications \n            of a specified type."
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
  /?Action=GetIdentityDkimAttributes:
    get:
      summary: Get Identity Dkim Attributes
      description: Returns the current status of Easy DKIM signing for an entity.
      operationId: getIdentityDkimAttributes
      x-api-path-slug: actiongetidentitydkimattributes-get
      parameters:
      - in: query
        name: Identities.member.N
        description: A list of one or more verified identities - email addresses,
          domains, or both
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=GetIdentityMailFromDomainAttributes:
    get:
      summary: Get Identity Mail From Domain Attributes
      description: Returns the custom MAIL FROM attributes for a list of identities
        (email addresses and/or domains).
      operationId: getIdentityMailFromDomainAttributes
      x-api-path-slug: actiongetidentitymailfromdomainattributes-get
      parameters:
      - in: query
        name: Identities.member.N
        description: A list of one or more identities
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=GetIdentityNotificationAttributes:
    get:
      summary: Get Identity Notification Attributes
      description: Given a list of verified identities (email addresses and/or domains),
        returns a structure describing identity notification attributes.
      operationId: getIdentityNotificationAttributes
      x-api-path-slug: actiongetidentitynotificationattributes-get
      parameters:
      - in: query
        name: Identities.member.N
        description: A list of one or more identities
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=GetIdentityPolicies:
    get:
      summary: Get Identity Policies
      description: Returns the requested sending authorization policies for the given
        identity (an email address or a domain).
      operationId: getIdentityPolicies
      x-api-path-slug: actiongetidentitypolicies-get
      parameters:
      - in: query
        name: Identity
        description: The identity for which the policies will be retrieved
        type: string
      - in: query
        name: PolicyNames.member.N
        description: A list of the names of policies to be retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=GetIdentityVerificationAttributes:
    get:
      summary: Get Identity Verification Attributes
      description: Given a list of identities (email addresses and/or domains), returns
        the verification status and (for domain identities) the verification token
        for each identity.
      operationId: getIdentityVerificationAttributes
      x-api-path-slug: actiongetidentityverificationattributes-get
      parameters:
      - in: query
        name: Identities.member.N
        description: A list of identities
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=ListIdentities:
    get:
      summary: List Identities
      description: Returns a list containing all of the identities (email addresses
        and domains) for your AWS account, regardless of verification status.
      operationId: listIdentities
      x-api-path-slug: actionlistidentities-get
      parameters:
      - in: query
        name: IdentityType
        description: The type of the identities to list
        type: string
      - in: query
        name: MaxItems
        description: The maximum number of identities per page
        type: string
      - in: query
        name: NextToken
        description: The token to use for pagination
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=ListIdentityPolicies:
    get:
      summary: List Identity Policies
      description: Returns a list of sending authorization policies that are attached
        to the given identity (an email address or a domain).
      operationId: listIdentityPolicies
      x-api-path-slug: actionlistidentitypolicies-get
      parameters:
      - in: query
        name: Identity
        description: The identity that is associated with the policy for which the
          policies will be listed
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=PutIdentityPolicy:
    get:
      summary: Put Identity Policy
      description: Adds or updates a sending authorization policy for the specified
        identity (an email address or a domain).
      operationId: putIdentityPolicy
      x-api-path-slug: actionputidentitypolicy-get
      parameters:
      - in: query
        name: Identity
        description: The identity to which the policy will apply
        type: string
      - in: query
        name: Policy
        description: The text of the policy in JSON format
        type: string
      - in: query
        name: PolicyName
        description: The name of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=SetIdentityDkimEnabled:
    get:
      summary: Set Identity Dkim Enabled
      description: |-
        Enables or disables Easy DKIM signing of email sent from an identity:If Easy DKIM
                    signing is enabled for a domain name identity (e.
      operationId: setIdentityDkimEnabled
      x-api-path-slug: actionsetidentitydkimenabled-get
      parameters:
      - in: query
        name: DkimEnabled
        description: Sets whether DKIM signing is enabled for an identity
        type: string
      - in: query
        name: Identity
        description: The identity for which DKIM signing should be enabled or disabled
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=SetIdentityFeedbackForwardingEnabled:
    get:
      summary: Set Identity Feedback Forwarding Enabled
      description: Given an identity (an email address or a domain), enables or disables
        whether Amazon SES forwards bounce and complaint notifications as email.
      operationId: setIdentityFeedbackForwardingEnabled
      x-api-path-slug: actionsetidentityfeedbackforwardingenabled-get
      parameters:
      - in: query
        name: ForwardingEnabled
        description: Sets whether Amazon SES will forward bounce and complaint notifications
          as email
        type: string
      - in: query
        name: Identity
        description: The identity for which to set bounce and complaint notification
          forwarding
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
  /?Action=SetIdentityHeadersInNotificationsEnabled:
    get:
      summary: Set Identity Headers In Notifications Enabled
      description: "Given an identity (an email address or a domain), sets whether
        Amazon SES includes \n            the original email headers in the Amazon
        Simple Notification Service (Amazon SNS) notifications \n            of a
        specified type."
      operationId: setIdentityHeadersInNotificationsEnabled
      x-api-path-slug: actionsetidentityheadersinnotificationsenabled-get
      parameters:
      - in: query
        name: Enabled
        description: Sets whether Amazon SES includes the original email headers in
          Amazon SNS notifications             of the specified notification type
        type: string
      - in: query
        name: Identity
        description: The identity for which to enable or disable headers in notifications
        type: string
      - in: query
        name: NotificationType
        description: The notification type for which to enable or disable headers
          in notifications
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
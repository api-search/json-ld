---
class_count: 13
classes:
- CreateRequestBody
- CreateSecretRequest
- CredentialResponse
- ManagedAccount
- ManagedSystem
- Request
- Secret
- SecretWithValue
- SessionResponse
- SignAppInRequest
- UpdateRequestBody
- EmailAddress
- Name
context_file: json-ld/beyondtrust-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/json-ld/beyondtrust-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Beyondtrust from BeyondTrust.
layout: jsonld
name: Beyondtrust Context
namespaces:
- prefix: bt
  uri: https://beyondtrust.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: SystemID
  type: integer
- container: ''
  name: AccountID
  type: integer
- container: ''
  name: DurationMinutes
  type: integer
- container: ''
  name: Reason
  type: string
- container: ''
  name: AccessType
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: folderName
  type: string
- container: ''
  name: Password
  type: string
- container: ''
  name: PrivateKey
  type: string
- container: ''
  name: AccountName
  type: string
- container: ''
  name: SystemName
  type: string
- container: ''
  name: DomainName
  type: string
- container: ''
  name: AccountType
  type: string
- container: ''
  name: LastChangeDate
  type: dateTime
- container: ''
  name: PasswordFallbackFlag
  type: boolean
- container: ''
  name: ManagedSystemID
  type: integer
- container: ''
  name: IPAddress
  type: string
- container: ''
  name: Platform
  type: string
- container: ''
  name: NetworkAddress
  type: string
- container: ''
  name: ContactEmail
  type: string
- container: ''
  name: RequestID
  type: integer
- container: ''
  name: Status
  type: string
- container: ''
  name: ExpiresDate
  type: dateTime
- container: ''
  name: RequestedDurationMinutes
  type: integer
- container: ''
  name: RequestDate
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: UserId
  type: integer
- container: ''
  name: UserName
  type: string
- container: ''
  name: ApplicationID
  type: string
- container: ''
  name: APIKey
  type: string
- container: ''
  name: Action
  type: string
property_count: 37
provider_name: BeyondTrust
provider_slug: beyondtrust
slug: beyondtrust-context
tags:
- Access
- Access Management
- Compliance
- Credentials
- Privileged Access
- Security
- Secrets
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---

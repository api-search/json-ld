---
api_specs:
- filename: beyondtrust-password-safe-api.yaml
  format: yaml
  label: BeyondTrust Password Safe API
  slug: beyondtrust-password-safe-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/openapi/beyondtrust-password-safe-api.yaml
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
source_filename: beyondtrust-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bt\": \"https://beyondtrust.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateRequestBody\": \"bt:CreateRequestBody\",\n    \"CreateSecretRequest\": \"bt:CreateSecretRequest\",\n    \"CredentialResponse\": \"bt:CredentialResponse\",\n    \"ManagedAccount\": \"bt:ManagedAccount\",\n    \"ManagedSystem\": \"bt:ManagedSystem\",\n    \"Request\": \"bt:Request\",\n    \"Secret\": \"bt:Secret\",\n    \"SecretWithValue\": \"bt:SecretWithValue\",\n    \"SessionResponse\": \"bt:SessionResponse\",\n    \"SignAppInRequest\": \"bt:SignAppInRequest\",\n    \"UpdateRequestBody\": \"bt:UpdateRequestBody\",\n    \"SystemID\": {\n      \"@id\": \"bt:SystemID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AccountID\": {\n      \"@id\": \"bt:AccountID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DurationMinutes\"\
  : {\n      \"@id\": \"bt:DurationMinutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Reason\": {\n      \"@id\": \"bt:Reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccessType\": {\n      \"@id\": \"bt:AccessType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"bt:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"bt:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"bt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"bt:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"bt:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"folderName\": {\n      \"@id\": \"bt:folderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Password\": {\n      \"@id\": \"bt:Password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrivateKey\": {\n      \"@id\": \"bt:PrivateKey\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"AccountName\": {\n      \"@id\": \"bt:AccountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SystemName\": {\n      \"@id\": \"bt:SystemName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DomainName\": {\n      \"@id\": \"bt:DomainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountType\": {\n      \"@id\": \"bt:AccountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastChangeDate\": {\n      \"@id\": \"bt:LastChangeDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PasswordFallbackFlag\": {\n      \"@id\": \"bt:PasswordFallbackFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ManagedSystemID\": {\n      \"@id\": \"bt:ManagedSystemID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"IPAddress\": {\n      \"@id\": \"bt:IPAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Platform\": {\n      \"@id\": \"bt:Platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkAddress\": {\n      \"@id\": \"\
  bt:NetworkAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ContactEmail\": {\n      \"@id\": \"bt:ContactEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestID\": {\n      \"@id\": \"bt:RequestID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Status\": {\n      \"@id\": \"bt:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpiresDate\": {\n      \"@id\": \"bt:ExpiresDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"RequestedDurationMinutes\": {\n      \"@id\": \"bt:RequestedDurationMinutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"RequestDate\": {\n      \"@id\": \"bt:RequestDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"bt:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"bt:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModified\": {\n      \"@id\": \"bt:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"UserId\": {\n      \"\
  @id\": \"bt:UserId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"EmailAddress\": \"schema:email\",\n    \"UserName\": {\n      \"@id\": \"bt:UserName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": \"schema:name\",\n    \"ApplicationID\": {\n      \"@id\": \"bt:ApplicationID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APIKey\": {\n      \"@id\": \"bt:APIKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Action\": {\n      \"@id\": \"bt:Action\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/beyondtrust/refs/heads/main/json-ld/beyondtrust-context.jsonld
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

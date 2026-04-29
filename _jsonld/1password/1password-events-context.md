---
api_specs:
- filename: 1password-connect-openapi.yml
  format: yaml
  label: 1Password Connect Server API
  slug: 1password-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/openapi/1password-connect-openapi.yml
- filename: 1password-events-openapi.yml
  format: yaml
  label: 1Password Events API
  slug: 1password-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/openapi/1password-events-openapi.yml
- filename: 1password-partnership-openapi.yml
  format: yaml
  label: 1Password Partnership API
  slug: 1password-partnership-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/openapi/1password-partnership-openapi.yml
class_count: 13
classes:
- AuditEventResponse
- AuditEvent
- EventClient
- EventLocation
- EventRequest
- EventUser
- ItemUsageResponse
- ItemUsage
- SignInAttemptResponse
- SignInAttempt
- TokenIntrospection
- email
- name
context_file: json-ld/1password-events-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/json-ld/1password-events-context.jsonld
description: JSON-LD context defining the semantic vocabulary for 1Password Events from 1Password.
layout: jsonld
name: 1Password Events Context
namespaces:
- prefix: onepassword
  uri: https://1password.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: action
  type: string
- container: ''
  name: actorDetails
  type: string
- container: ''
  name: actorUuid
  type: string
- container: ''
  name: appName
  type: string
- container: ''
  name: appVersion
  type: string
- container: ''
  name: auxDetails
  type: reference
- container: ''
  name: auxId
  type: integer
- container: ''
  name: auxInfo
  type: string
- container: ''
  name: auxUuid
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: client
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: cursor
  type: string
- container: ''
  name: deviceUuid
  type: string
- container: set
  name: features
  type: string
- container: ''
  name: hasMore
  type: boolean
- container: ''
  name: ip
  type: string
- container: ''
  name: itemUuid
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: limit
  type: integer
- container: ''
  name: location
  type: string
- container: ''
  name: loginTime
  type: dateTime
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: objectDetails
  type: reference
- container: ''
  name: objectType
  type: string
- container: ''
  name: objectUuid
  type: string
- container: ''
  name: osName
  type: string
- container: ''
  name: osVersion
  type: string
- container: ''
  name: platformName
  type: string
- container: ''
  name: platformVersion
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: session
  type: reference
- container: ''
  name: sessionUuid
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: targetUser
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: type
  type: string
- container: ''
  name: usedVersion
  type: integer
- container: ''
  name: user
  type: string
- container: ''
  name: uuid
  type: string
- container: ''
  name: vaultUuid
  type: string
property_count: 43
provider_name: 1Password
provider_slug: 1password
slug: 1password-events-context
source_filename: 1password-events-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"onepassword\": \"https://1password.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuditEventResponse\": \"onepassword:AuditEventResponse\",\n    \"AuditEvent\": \"onepassword:AuditEvent\",\n    \"EventClient\": \"onepassword:EventClient\",\n    \"EventLocation\": \"onepassword:EventLocation\",\n    \"EventRequest\": \"onepassword:EventRequest\",\n    \"EventUser\": \"onepassword:EventUser\",\n    \"ItemUsageResponse\": \"onepassword:ItemUsageResponse\",\n    \"ItemUsage\": \"onepassword:ItemUsage\",\n    \"SignInAttemptResponse\": \"onepassword:SignInAttemptResponse\",\n    \"SignInAttempt\": \"onepassword:SignInAttempt\",\n    \"TokenIntrospection\": \"onepassword:TokenIntrospection\",\n    \"action\": {\n      \"@id\": \"onepassword:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorDetails\"\
  : {\n      \"@id\": \"onepassword:actor_details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actorUuid\": {\n      \"@id\": \"onepassword:actor_uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appName\": {\n      \"@id\": \"onepassword:app_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appVersion\": {\n      \"@id\": \"onepassword:app_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auxDetails\": {\n      \"@id\": \"onepassword:aux_details\",\n      \"@type\": \"@id\"\n    },\n    \"auxId\": {\n      \"@id\": \"onepassword:aux_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"auxInfo\": {\n      \"@id\": \"onepassword:aux_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auxUuid\": {\n      \"@id\": \"onepassword:aux_uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"onepassword:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"onepassword:city\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"client\": {\n      \"@id\": \"onepassword:client\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"onepassword:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cursor\": {\n      \"@id\": \"onepassword:cursor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceUuid\": {\n      \"@id\": \"onepassword:device_uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"features\": {\n      \"@id\": \"onepassword:features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasMore\": {\n      \"@id\": \"onepassword:has_more\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ip\": {\n      \"@id\": \"onepassword:ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemUuid\": {\n      \"@id\": \"onepassword:item_uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"onepassword:items\",\n      \"@container\": \"@set\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"onepassword:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"limit\": {\n      \"@id\": \"onepassword:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"location\": {\n      \"@id\": \"onepassword:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loginTime\": {\n      \"@id\": \"onepassword:login_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"longitude\": {\n      \"@id\": \"onepassword:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"name\": \"schema:name\",\n    \"objectDetails\": {\n      \"@id\": \"onepassword:object_details\",\n      \"@type\": \"@id\"\n    },\n    \"objectType\": {\n      \"@id\": \"onepassword:object_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectUuid\": {\n      \"@id\": \"onepassword:object_uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osName\": {\n      \"@id\": \"onepassword:os_name\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"osVersion\": {\n      \"@id\": \"onepassword:os_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformName\": {\n      \"@id\": \"onepassword:platform_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformVersion\": {\n      \"@id\": \"onepassword:platform_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"onepassword:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"session\": {\n      \"@id\": \"onepassword:session\",\n      \"@type\": \"@id\"\n    },\n    \"sessionUuid\": {\n      \"@id\": \"onepassword:session_uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"onepassword:start_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"targetUser\": {\n      \"@id\": \"onepassword:target_user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"onepassword:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"type\": {\n  \
  \    \"@id\": \"onepassword:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usedVersion\": {\n      \"@id\": \"onepassword:used_version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"user\": {\n      \"@id\": \"onepassword:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uuid\": {\n      \"@id\": \"onepassword:uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vaultUuid\": {\n      \"@id\": \"onepassword:vault_uuid\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/json-ld/1password-events-context.jsonld
tags:
- Password Manager
- Passwords
- Security
- Secrets
- JSON-LD
- Linked Data
- Semantic Web
---

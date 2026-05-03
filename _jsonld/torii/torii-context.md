---
api_specs:
- filename: torii-torii-openapi.yml
  format: yaml
  label: Torii SaaS Management API
  slug: torii
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/torii/refs/heads/main/openapi/torii-torii-openapi.yml
class_count: 48
classes:
- scim
- id
- type
- App
- User
- Contract
- AuditLogEntry
- FieldMetadata
- ParsingRequest
- ScimUser
- name
- email
- url
- description
- category
- state
- activeUsers
- totalUsers
- totalLicenses
- annualCost
- owner
- firstName
- lastName
- status
- department
- isExternal
- appsCount
- appId
- appName
- startDate
- endDate
- renewalDate
- currency
- action
- actor
- actorEmail
- target
- details
- createdAt
- key
- isCustom
- isRequired
- fileId
- columns
- userName
- displayName
- active
- externalId
context_file: json-ld/torii-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/torii/refs/heads/main/json-ld/torii-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Torii from Torii.
layout: jsonld
name: Torii Context
namespaces:
- prefix: torii
  uri: https://api.toriihq.com/v1.1/
properties: []
property_count: 0
provider_name: Torii
provider_slug: torii
slug: torii-context
source_filename: torii-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"torii\": \"https://api.toriihq.com/v1.1/\",\n    \"scim\": \"urn:ietf:params:scim:schemas:core:2.0:\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"App\": \"torii:App\",\n    \"User\": \"torii:User\",\n    \"Contract\": \"torii:Contract\",\n    \"AuditLogEntry\": \"torii:AuditLogEntry\",\n    \"FieldMetadata\": \"torii:FieldMetadata\",\n    \"ParsingRequest\": \"torii:ParsingRequest\",\n    \"ScimUser\": \"scim:User\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"url\": \"schema:url\",\n    \"description\": \"schema:description\",\n    \"category\": \"schema:category\",\n    \"state\": \"torii:state\",\n    \"activeUsers\": \"torii:activeUsers\",\n    \"totalUsers\": \"torii:totalUsers\",\n    \"totalLicenses\": \"torii:totalLicenses\",\n    \"annualCost\": \"torii:annualCost\",\n    \"owner\": \"torii:owner\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\"\
  : \"schema:familyName\",\n    \"status\": \"torii:status\",\n    \"department\": \"torii:department\",\n    \"isExternal\": \"torii:isExternal\",\n    \"appsCount\": \"torii:appsCount\",\n    \"appId\": \"torii:appId\",\n    \"appName\": \"torii:appName\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"renewalDate\": \"torii:renewalDate\",\n    \"currency\": \"schema:priceCurrency\",\n    \"action\": \"schema:actionStatus\",\n    \"actor\": \"torii:actor\",\n    \"actorEmail\": \"torii:actorEmail\",\n    \"target\": \"torii:target\",\n    \"details\": \"torii:details\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"key\": \"torii:key\",\n    \"isCustom\": \"torii:isCustom\",\n    \"isRequired\": \"torii:isRequired\",\n    \"fileId\": \"torii:fileId\",\n    \"columns\": \"torii:columns\",\n    \"userName\": \"scim:userName\",\n    \"displayName\": \"schema:name\",\n    \"active\": \"torii:active\",\n    \"externalId\": \"torii:externalId\"\n\
  \  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/torii/refs/heads/main/json-ld/torii-context.jsonld
tags:
- Apps
- Compliance
- Cost Optimization
- Governance
- IT Management
- SaaS Management
- JSON-LD
- Linked Data
- Semantic Web
---

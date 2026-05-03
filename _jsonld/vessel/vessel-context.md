---
api_specs:
- filename: vessel-platform-openapi.yml
  format: yaml
  label: Vessel Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/openapi/vessel-platform-openapi.yml
- filename: vessel-crm-openapi.yml
  format: yaml
  label: Vessel CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/openapi/vessel-crm-openapi.yml
class_count: 9
classes:
- Contact
- Deal
- Account
- Lead
- Note
- Task
- User
- Connection
- Integration
context_file: json-ld/vessel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/json-ld/vessel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vessel from Vessel.
layout: jsonld
name: Vessel Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: vessel
  uri: https://www.vessel.dev/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: stage
  type: string
- container: ''
  name: closeDate
  type: dateTime
- container: ''
  name: content
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: industry
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: connectionId
  type: string
- container: ''
  name: integrationId
  type: string
- container: ''
  name: accessToken
  type: string
- container: ''
  name: status
  type: string
property_count: 20
provider_name: Vessel
provider_slug: vessel
slug: vessel-context
source_filename: vessel-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"vessel\": \"https://www.vessel.dev/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Contact\": \"schema:Person\",\n    \"Deal\": \"schema:Offer\",\n    \"Account\": \"schema:Organization\",\n    \"Lead\": \"vessel:Lead\",\n    \"Note\": \"schema:Comment\",\n    \"Task\": \"schema:Action\",\n    \"User\": \"schema:Person\",\n    \"Connection\": \"vessel:Connection\",\n    \"Integration\": \"schema:SoftwareApplication\",\n\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"schema:telephone\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:jobTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"schema:worksFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"stage\": {\n      \"@id\": \"vessel:dealStage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closeDate\": {\n      \"@id\": \"vessel:closeDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"content\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"industry\": {\n      \"@id\": \"schema:industry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"connectionId\": {\n      \"@id\": \"vessel:connectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integrationId\": {\n      \"@id\": \"vessel:integrationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessToken\": {\n      \"@id\": \"vessel:accessToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"vessel:connectionStatus\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/json-ld/vessel-context.jsonld
tags:
- CRM
- Embedded Integrations
- GTM
- Integrations
- iPaaS
- Sales Engagement
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---

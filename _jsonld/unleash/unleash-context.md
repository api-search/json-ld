---
api_specs:
- filename: unleash-admin-api-openapi.yml
  format: yaml
  label: Unleash Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-admin-api-openapi.yml
- filename: unleash-client-api-openapi.yml
  format: yaml
  label: Unleash Client API
  slug: client-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-client-api-openapi.yml
- filename: unleash-frontend-api-openapi.yml
  format: yaml
  label: Unleash Frontend API
  slug: frontend-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/openapi/unleash-frontend-api-openapi.yml
class_count: 11
classes:
- FeatureFlag
- Project
- Environment
- Strategy
- Segment
- Variant
- User
- APIToken
- Constraint
- name
- description
context_file: json-ld/unleash-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/json-ld/unleash-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unleash from Unleash.
layout: jsonld
name: Unleash Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: unleash
  uri: https://getunleash.io/ontology#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: lastSeenAt
  type: dateTime
- container: ''
  name: project
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: stale
  type: boolean
- container: ''
  name: impressionData
  type: boolean
- container: set
  name: environments
  type: ''
- container: set
  name: strategies
  type: ''
- container: set
  name: constraints
  type: ''
- container: ''
  name: parameters
  type: ''
- container: set
  name: segments
  type: ''
- container: set
  name: variants
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: context
  type: ''
- container: ''
  name: contextName
  type: string
- container: ''
  name: operator
  type: string
- container: set
  name: values
  type: ''
- container: ''
  name: weight
  type: integer
- container: ''
  name: weightType
  type: string
- container: ''
  name: payload
  type: ''
- container: ''
  name: email
  type: string
- container: ''
  name: rootRole
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: secret
  type: string
- container: ''
  name: version
  type: string
property_count: 27
provider_name: Unleash
provider_slug: unleash
slug: unleash-context
source_filename: unleash-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"unleash\": \"https://getunleash.io/ontology#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"FeatureFlag\": \"unleash:FeatureFlag\",\n    \"Project\": \"schema:Project\",\n    \"Environment\": \"unleash:Environment\",\n    \"Strategy\": \"unleash:Strategy\",\n    \"Segment\": \"unleash:Segment\",\n    \"Variant\": \"unleash:Variant\",\n    \"User\": \"schema:Person\",\n    \"APIToken\": \"unleash:APIToken\",\n    \"Constraint\": \"unleash:Constraint\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"enabled\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastSeenAt\": {\n \
  \     \"@id\": \"unleash:lastSeenAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"project\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"unleash:flagType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stale\": {\n      \"@id\": \"unleash:stale\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"impressionData\": {\n      \"@id\": \"unleash:impressionData\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"environments\": {\n      \"@id\": \"unleash:environments\",\n      \"@container\": \"@set\"\n    },\n    \"strategies\": {\n      \"@id\": \"unleash:strategies\",\n      \"@container\": \"@set\"\n    },\n    \"constraints\": {\n      \"@id\": \"unleash:constraints\",\n      \"@container\": \"@set\"\n    },\n    \"parameters\": {\n      \"@id\": \"schema:additionalProperty\"\n    },\n    \"segments\": {\n      \"@id\": \"unleash:segments\",\n      \"@container\": \"@set\"\n    },\n    \"variants\": {\n      \"@id\"\
  : \"unleash:variants\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"context\": {\n      \"@id\": \"unleash:context\"\n    },\n    \"contextName\": {\n      \"@id\": \"unleash:contextName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"unleash:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"schema:value\",\n      \"@container\": \"@set\"\n    },\n    \"weight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"weightType\": {\n      \"@id\": \"unleash:weightType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"schema:value\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rootRole\": {\n      \"@id\": \"schema:roleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n  \
  \    \"@id\": \"unleash:tokenType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secret\": {\n      \"@id\": \"unleash:secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unleash/refs/heads/main/json-ld/unleash-context.jsonld
tags:
- Feature Flags
- Feature Management
- Progressive Delivery
- A/B Testing
- Open Source
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: dynatrace-metrics-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Metrics API v2
  slug: dynatrace-metrics-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-metrics-api-v2-openapi.yml
- filename: dynatrace-log-monitoring-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Log Monitoring API v2
  slug: dynatrace-log-monitoring-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-log-monitoring-api-v2-openapi.yml
- filename: dynatrace-account-management-api-openapi.yml
  format: yaml
  label: Dynatrace Account Management API
  slug: dynatrace-account-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-account-management-api-openapi.yml
- filename: dynatrace-events-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Events API v2
  slug: dynatrace-events-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-events-api-v2-openapi.yml
- filename: dynatrace-problems-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Problems API v2
  slug: dynatrace-problems-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-problems-api-v2-openapi.yml
- filename: dynatrace-entities-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Entities API v2
  slug: dynatrace-entities-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-entities-api-v2-openapi.yml
class_count: 10
classes:
- ConstraintViolation
- EntityCollection
- EntityLookupRequest
- Entity
- EntityTag
- EntityTypeCollection
- EntityTypeProperty
- EntityTypeRelationship
- EntityType
- ManagementZone
context_file: json-ld/dynatrace-entities-api-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-entities-api-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Entities Api V2 from Dynatrace.
layout: jsonld
name: Dynatrace Entities Api V2 Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: path
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: parameterLocation
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: nextPageKey
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: set
  name: entities
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: entityId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: firstSeenTms
  type: integer
- container: ''
  name: lastSeenTms
  type: integer
- container: ''
  name: properties
  type: ''
- container: set
  name: tags
  type: ''
- container: set
  name: managementZones
  type: ''
- container: ''
  name: toRelationships
  type: ''
- container: ''
  name: fromRelationships
  type: ''
- container: ''
  name: context
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: stringRepresentation
  type: string
- container: set
  name: types
  type: ''
- container: ''
  name: id
  type: string
- container: set
  name: toTypes
  type: ''
- container: ''
  name: description
  type: string
property_count: 27
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-entities-api-v2-context
source_filename: dynatrace-entities-api-v2-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConstraintViolation\": \"dt:ConstraintViolation\",\n    \"path\": {\n      \"@id\": \"dt:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"dt:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameterLocation\": {\n      \"@id\": \"dt:parameterLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"dt:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityCollection\": \"dt:EntityCollection\",\n    \"nextPageKey\": {\n      \"@id\": \"dt:nextPageKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"dt:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"dt:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"entities\": {\n      \"@id\": \"dt:entities\",\n      \"@container\": \"@set\"\n    },\n    \"EntityLookupRequest\": \"dt:EntityLookupRequest\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"dt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Entity\": \"dt:Entity\",\n    \"entityId\": {\n      \"@id\": \"dt:entityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"dt:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstSeenTms\": {\n      \"@id\": \"dt:firstSeenTms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastSeenTms\": {\n      \"@id\": \"dt:lastSeenTms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"properties\": {\n      \"@id\": \"dt:properties\"\n    },\n    \"tags\": {\n      \"@id\": \"dt:tags\",\n      \"@container\": \"@set\"\n    },\n    \"managementZones\": {\n      \"@id\": \"dt:managementZones\",\n      \"@container\"\
  : \"@set\"\n    },\n    \"toRelationships\": {\n      \"@id\": \"dt:toRelationships\"\n    },\n    \"fromRelationships\": {\n      \"@id\": \"dt:fromRelationships\"\n    },\n    \"EntityTag\": \"dt:EntityTag\",\n    \"context\": {\n      \"@id\": \"dt:context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"dt:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"dt:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stringRepresentation\": {\n      \"@id\": \"dt:stringRepresentation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityTypeCollection\": \"dt:EntityTypeCollection\",\n    \"types\": {\n      \"@id\": \"dt:types\",\n      \"@container\": \"@set\"\n    },\n    \"EntityTypeProperty\": \"dt:EntityTypeProperty\",\n    \"id\": {\n      \"@id\": \"dt:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityTypeRelationship\": \"dt:EntityTypeRelationship\",\n    \"toTypes\": {\n      \"@id\": \"dt:toTypes\",\n\
  \      \"@container\": \"@set\"\n    },\n    \"EntityType\": \"dt:EntityType\",\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManagementZone\": \"dt:ManagementZone\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-entities-api-v2-context.jsonld
tags:
- AI Operations
- Analytics
- APM
- Application Performance Monitoring
- Application Security
- Automation
- Cloud Monitoring
- Digital Experience Management
- Intelligence
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---

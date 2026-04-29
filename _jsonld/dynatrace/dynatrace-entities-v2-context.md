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
class_count: 0
classes: []
context_file: json-ld/dynatrace-entities-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-entities-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Entities V2 from Dynatrace.
layout: jsonld
name: Dynatrace Entities V2 Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Entity
  type: ''
- container: ''
  name: EntityCollection
  type: ''
- container: ''
  name: EntityType
  type: ''
- container: ''
  name: EntityTypeProperty
  type: ''
- container: ''
  name: EntityTypeRelationship
  type: ''
- container: ''
  name: EntityTypeCollection
  type: ''
- container: ''
  name: EntityLookupRequest
  type: ''
- container: ''
  name: EntityTag
  type: ''
- container: ''
  name: ManagementZone
  type: ''
- container: ''
  name: ErrorEnvelope
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ConstraintViolation
  type: ''
property_count: 12
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-entities-v2-context
source_filename: dynatrace-entities-v2-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Entity\": {\n      \"@id\": \"ns:Entity\",\n      \"@context\": {\n        \"entityId\": {\n          \"@id\": \"ns:entityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"ns:displayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstSeenTms\": {\n          \"@id\": \"ns:firstSeenTms\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastSeenTms\": {\n          \"@id\": \"ns:lastSeenTms\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"properties\": \"ns:properties\",\n        \"tags\": \"ns:tags\",\n        \"managementZones\": \"ns:managementZones\",\n        \"toRelationships\": \"ns:toRelationships\",\n        \"fromRelationships\"\
  : \"ns:fromRelationships\"\n      }\n    },\n    \"EntityCollection\": {\n      \"@id\": \"ns:EntityCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"pageSize\": {\n          \"@id\": \"ns:pageSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"entities\": \"ns:entities\"\n      }\n    },\n    \"EntityType\": {\n      \"@id\": \"ns:EntityType\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"ns:displayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n\
  \        \"fromRelationships\": \"ns:fromRelationships\",\n        \"toRelationships\": \"ns:toRelationships\"\n      }\n    },\n    \"EntityTypeProperty\": {\n      \"@id\": \"ns:EntityTypeProperty\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"ns:displayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"EntityTypeRelationship\": {\n      \"@id\": \"ns:EntityTypeRelationship\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"toTypes\": \"ns:toTypes\"\n      }\n    },\n    \"EntityTypeCollection\": {\n      \"@id\": \"ns:EntityTypeCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"types\": \"ns:types\"\n      }\n    },\n    \"EntityLookupRequest\": {\n      \"@id\": \"ns:EntityLookupRequest\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"EntityTag\": {\n      \"@id\": \"ns:EntityTag\",\n      \"@context\": {\n        \"context\": {\n          \"@id\": \"ns:context\",\n          \"@type\": \"xsd:string\"\n        },\n        \"key\": {\n          \"@id\": \"ns:key\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"stringRepresentation\": {\n          \"@id\": \"ns:stringRepresentation\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ManagementZone\": {\n      \"@id\": \"ns:ManagementZone\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorEnvelope\": {\n      \"@id\": \"ns:ErrorEnvelope\",\n      \"@context\": {\n        \"error\": {\n          \"@id\": \"ns:error\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"constraintViolations\": \"ns:constraintViolations\"\n      }\n    },\n    \"ConstraintViolation\": {\n      \"@id\": \"ns:ConstraintViolation\"\
  ,\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"ns:path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameterLocation\": {\n          \"@id\": \"ns:parameterLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"ns:location\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-entities-v2-context.jsonld
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

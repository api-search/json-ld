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
context_file: json-ld/dynatrace-account-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-account-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Account Management from Dynatrace.
layout: jsonld
name: Dynatrace Account Management Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: UserCreateRequest
  type: ''
- container: ''
  name: UserCollection
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: GroupCreateRequest
  type: ''
- container: ''
  name: GroupCollection
  type: ''
- container: ''
  name: Permission
  type: ''
- container: ''
  name: PermissionCollection
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: EnvironmentCollection
  type: ''
- container: ''
  name: ErrorEnvelope
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 12
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-account-management-context
source_filename: dynatrace-account-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"User\": {\n      \"@id\": \"ns:User\",\n      \"@context\": {\n        \"uid\": {\n          \"@id\": \"ns:uid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"ns:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstName\": {\n          \"@id\": \"ns:firstName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastName\": {\n          \"@id\": \"ns:lastName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"groups\": \"ns:groups\",\n        \"userStatus\": {\n          \"@id\": \"ns:userStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"UserCreateRequest\": {\n      \"@id\": \"ns:UserCreateRequest\",\n      \"@context\": {\n        \"email\": {\n          \"@id\": \"ns:email\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"firstName\": {\n          \"@id\": \"ns:firstName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastName\": {\n          \"@id\": \"ns:lastName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"groups\": \"ns:groups\"\n      }\n    },\n    \"UserCollection\": {\n      \"@id\": \"ns:UserCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"items\": \"ns:items\"\n      }\n    },\n    \"Group\": {\n      \"@id\": \"ns:Group\",\n      \"@context\": {\n        \"groupId\": {\n          \"@id\": \"ns:groupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"owner\": {\n          \"@id\": \"ns:owner\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"GroupCreateRequest\": {\n      \"@id\": \"ns:GroupCreateRequest\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"GroupCollection\": {\n      \"@id\": \"ns:GroupCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"items\": \"ns:items\"\n      }\n    },\n    \"Permission\": {\n      \"@id\": \"ns:Permission\",\n      \"@context\": {\n        \"permissionName\": {\n          \"@id\": \"ns:permissionName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scope\": {\n          \"@id\": \"ns:scope\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scopeType\": {\n          \"@id\": \"ns:scopeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"groupId\": {\n          \"@id\": \"ns:groupId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PermissionCollection\": {\n      \"@id\": \"ns:PermissionCollection\",\n      \"@context\": {\n        \"permissions\": \"ns:permissions\"\n      }\n    },\n    \"Environment\": {\n      \"@id\": \"ns:Environment\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n    \
  \    \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"trial\": {\n          \"@id\": \"ns:trial\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"EnvironmentCollection\": {\n      \"@id\": \"ns:EnvironmentCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"environments\": \"ns:environments\"\n      }\n    },\n    \"ErrorEnvelope\": {\n      \"@id\": \"ns:ErrorEnvelope\",\n      \"@context\": {\n        \"error\": {\n          \"@id\": \"ns:error\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\"\
  : {\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-account-management-context.jsonld
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

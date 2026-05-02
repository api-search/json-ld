---
api_specs:
- filename: openapi
  format: yaml
  label: Mixpanel Ingestion API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.mixpanel.com/reference/openapi
- filename: openapi
  format: yaml
  label: Mixpanel Query API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.mixpanel.com/reference/openapi
- filename: openapi
  format: yaml
  label: Mixpanel Data Pipelines API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.mixpanel.com/reference/openapi
- filename: mixpanel-identity-openapi.yml
  format: yaml
  label: Mixpanel Identity API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-identity-openapi.yml
- filename: mixpanel-event-export-openapi.yml
  format: yaml
  label: Mixpanel Event Export API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-event-export-openapi.yml
- filename: mixpanel-lexicon-schemas-openapi.yml
  format: yaml
  label: Mixpanel Lexicon Schemas API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-lexicon-schemas-openapi.yml
- filename: mixpanel-service-accounts-openapi.yml
  format: yaml
  label: Mixpanel Service Accounts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-service-accounts-openapi.yml
- filename: mixpanel-annotations-openapi.yml
  format: yaml
  label: Mixpanel Annotations API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-annotations-openapi.yml
- filename: mixpanel-gdpr-ccpa-openapi.yml
  format: yaml
  label: Mixpanel GDPR and CCPA API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-gdpr-ccpa-openapi.yml
- filename: mixpanel-warehouse-connectors-openapi.yml
  format: yaml
  label: Mixpanel Warehouse Connectors API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/openapi/mixpanel-warehouse-connectors-openapi.yml
class_count: 0
classes: []
context_file: json-ld/mixpanel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/json-ld/mixpanel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Mixpanel from Mixpanel.
layout: jsonld
name: Mixpanel Context
namespaces:
- prefix: mixpanel
  uri: https://developer.mixpanel.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Event
  type: ''
- container: ''
  name: UserProfile
  type: ''
- container: ''
  name: GroupProfile
  type: ''
- container: ''
  name: Funnel
  type: ''
- container: ''
  name: Cohort
  type: ''
- container: ''
  name: Annotation
  type: ''
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: ServiceAccount
  type: ''
- container: ''
  name: LookupTable
  type: ''
- container: ''
  name: WarehouseSource
  type: ''
property_count: 10
provider_name: Mixpanel
provider_slug: mixpanel
slug: mixpanel-context
source_filename: mixpanel-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mixpanel\": \"https://developer.mixpanel.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Event\": {\n      \"@id\": \"mixpanel:Event\",\n      \"@context\": {\n        \"event\": \"schema:name\",\n        \"distinctId\": \"mixpanel:distinctId\",\n        \"time\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"insertId\": \"mixpanel:insertId\",\n        \"token\": \"mixpanel:projectToken\"\n      }\n    },\n\n    \"UserProfile\": {\n      \"@id\": \"mixpanel:UserProfile\",\n      \"@context\": {\n        \"distinctId\": \"mixpanel:distinctId\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n\
  \        \"avatar\": \"schema:image\",\n        \"city\": \"schema:addressLocality\",\n        \"region\": \"schema:addressRegion\",\n        \"countryCode\": \"schema:addressCountry\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastSeen\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"GroupProfile\": {\n      \"@id\": \"mixpanel:GroupProfile\",\n      \"@context\": {\n        \"groupKey\": \"mixpanel:groupKey\",\n        \"groupId\": \"mixpanel:groupId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Funnel\": {\n      \"@id\": \"mixpanel:Funnel\",\n      \"@context\": {\n        \"funnelId\": \"mixpanel:funnelId\",\n        \"name\": \"schema:name\",\n        \"steps\": \"mixpanel:funnelSteps\"\n      }\n    },\n\n    \"Cohort\": {\n      \"@id\": \"mixpanel:Cohort\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"count\": {\n          \"@id\": \"mixpanel:memberCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Annotation\": {\n      \"@id\": \"mixpanel:Annotation\",\n      \"@context\": {\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"description\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Pipeline\": {\n      \"@id\": \"mixpanel:Pipeline\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"mixpanel:destinationType\",\n        \"status\": \"mixpanel:pipelineStatus\",\n        \"frequency\": \"mixpanel:exportFrequency\"\
  ,\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ServiceAccount\": {\n      \"@id\": \"mixpanel:ServiceAccount\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"username\": \"mixpanel:serviceAccountUsername\",\n        \"organizationId\": \"mixpanel:organizationId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"LookupTable\": {\n      \"@id\": \"mixpanel:LookupTable\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"rowCount\": {\n          \"@id\": \"mixpanel:rowCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"columnCount\": {\n          \"@id\": \"mixpanel:columnCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n  \
  \      }\n      }\n    },\n\n    \"WarehouseSource\": {\n      \"@id\": \"mixpanel:WarehouseSource\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"mixpanel:warehouseType\",\n        \"status\": \"mixpanel:connectionStatus\",\n        \"schedule\": \"mixpanel:importSchedule\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mixpanel/refs/heads/main/json-ld/mixpanel-context.jsonld
tags:
- Analytics
- Data Analysis
- Event Tracking
- Product Analytics
- User Behavior
- JSON-LD
- Linked Data
- Semantic Web
---

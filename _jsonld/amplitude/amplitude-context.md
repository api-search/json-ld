---
api_specs:
- filename: amplitude-http-v2-api-openapi.yml
  format: yaml
  label: Amplitude HTTP V2 API
  slug: http-v2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-http-v2-api-openapi.yml
- filename: amplitude-identify-api-openapi.yml
  format: yaml
  label: Amplitude Identify API
  slug: identify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-identify-api-openapi.yml
- filename: amplitude-dashboard-rest-api-openapi.yml
  format: yaml
  label: Amplitude Dashboard REST API
  slug: dashboard-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-dashboard-rest-api-openapi.yml
- filename: amplitude-export-api-openapi.yml
  format: yaml
  label: Amplitude Export API
  slug: export-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-export-api-openapi.yml
- filename: amplitude-behavioral-cohorts-api-openapi.yml
  format: yaml
  label: Amplitude Behavioral Cohorts API
  slug: behavioral-cohorts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-behavioral-cohorts-api-openapi.yml
- filename: amplitude-taxonomy-api-openapi.yml
  format: yaml
  label: Amplitude Taxonomy API
  slug: taxonomy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-taxonomy-api-openapi.yml
- filename: amplitude-attribution-api-openapi.yml
  format: yaml
  label: Amplitude Attribution API
  slug: attribution-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-attribution-api-openapi.yml
- filename: amplitude-chart-annotations-api-openapi.yml
  format: yaml
  label: Amplitude Chart Annotations API
  slug: chart-annotations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-chart-annotations-api-openapi.yml
- filename: amplitude-user-profile-api-openapi.yml
  format: yaml
  label: Amplitude User Profile API
  slug: user-profile-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-user-profile-api-openapi.yml
- filename: amplitude-user-mapping-api-openapi.yml
  format: yaml
  label: Amplitude User Mapping API
  slug: user-mapping-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-user-mapping-api-openapi.yml
- filename: amplitude-scim-api-openapi.yml
  format: yaml
  label: Amplitude SCIM API
  slug: scim-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-scim-api-openapi.yml
- filename: amplitude-dsar-api-openapi.yml
  format: yaml
  label: Amplitude Data Subject Access Request API
  slug: dsar-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-dsar-api-openapi.yml
- filename: amplitude-experiment-evaluation-api-openapi.yml
  format: yaml
  label: Amplitude Experiment Evaluation API
  slug: experiment-evaluation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-experiment-evaluation-api-openapi.yml
- filename: amplitude-experiment-management-api-openapi.yml
  format: yaml
  label: Amplitude Experiment Management API
  slug: experiment-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/openapi/amplitude-experiment-management-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amplitude-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude from Amplitude.
layout: jsonld
name: Amplitude Context
namespaces:
- prefix: amp
  uri: https://amplitude.com/schemas/
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
  name: Cohort
  type: ''
- container: ''
  name: Experiment
  type: ''
- container: ''
  name: Variant
  type: ''
- container: ''
  name: Annotation
  type: ''
- container: ''
  name: Deployment
  type: ''
property_count: 7
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amp\": \"https://amplitude.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Event\": {\n      \"@id\": \"amp:Event\",\n      \"@context\": {\n        \"eventType\": \"amp:eventType\",\n        \"userId\": \"schema:identifier\",\n        \"deviceId\": \"amp:deviceId\",\n        \"time\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"eventProperties\": \"amp:eventProperties\",\n        \"userProperties\": \"amp:userProperties\",\n        \"platform\": \"amp:platform\",\n        \"osName\": \"amp:osName\",\n        \"osVersion\": \"amp:osVersion\",\n        \"deviceBrand\": \"amp:deviceBrand\",\n        \"deviceModel\": \"amp:deviceModel\",\n        \"country\": \"schema:addressCountry\",\n        \"region\": \"schema:addressRegion\",\n        \"city\"\
  : \"schema:addressLocality\",\n        \"language\": \"schema:inLanguage\",\n        \"revenue\": \"amp:revenue\",\n        \"price\": \"schema:price\",\n        \"quantity\": \"amp:quantity\",\n        \"productId\": \"schema:productID\",\n        \"sessionId\": \"amp:sessionId\",\n        \"ipAddress\": \"amp:ipAddress\",\n        \"appVersion\": \"schema:softwareVersion\"\n      }\n    },\n\n    \"UserProfile\": {\n      \"@id\": \"amp:UserProfile\",\n      \"@context\": {\n        \"userId\": \"schema:identifier\",\n        \"amplitudeId\": \"amp:amplitudeId\",\n        \"userProperties\": \"amp:userProperties\",\n        \"computedProperties\": \"amp:computedProperties\",\n        \"cohortIds\": {\n          \"@id\": \"amp:cohortIds\",\n          \"@container\": \"@set\"\n        },\n        \"recommendations\": {\n          \"@id\": \"amp:recommendations\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Cohort\": {\n      \"@id\": \"amp:Cohort\",\n     \
  \ \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"size\": \"amp:cohortSize\",\n        \"owner\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"lastComputed\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"archived\": \"amp:archived\",\n        \"appId\": \"amp:projectId\"\n      }\n    },\n\n    \"Experiment\": {\n      \"@id\": \"amp:Experiment\",\n      \"@context\": {\n        \"key\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"enabled\": \"amp:enabled\",\n        \"state\": \"amp:state\",\n        \"evaluationMode\": \"amp:evaluationMode\",\n        \"variants\": {\n          \"@id\": \"amp:variants\",\n          \"@container\": \"@set\"\n        },\n        \"segments\": {\n          \"@id\": \"amp:segments\",\n          \"@container\"\
  : \"@set\"\n        },\n        \"deployments\": {\n          \"@id\": \"amp:deployments\",\n          \"@container\": \"@set\"\n        },\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Variant\": {\n      \"@id\": \"amp:Variant\",\n      \"@context\": {\n        \"key\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"payload\": \"amp:payload\",\n        \"rolloutWeight\": \"amp:rolloutWeight\"\n      }\n    },\n\n    \"Annotation\": {\n      \"@id\": \"amp:Annotation\",\n      \"@context\": {\n        \"label\": \"schema:name\",\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n      \
  \    \"@type\": \"xsd:date\"\n        },\n        \"details\": \"schema:description\",\n        \"category\": \"schema:category\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"amp:Deployment\",\n      \"@context\": {\n        \"label\": \"schema:name\",\n        \"key\": \"schema:identifier\",\n        \"projectId\": \"amp:projectId\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-context.jsonld
tags:
- A/B Testing
- Analytics
- Experimentation
- Feature Flags
- Product Analytics
- User Behavior
- JSON-LD
- Linked Data
- Semantic Web
---

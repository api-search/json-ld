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
class_count: 6
classes:
- UpdateAnnotationRequest
- CreateAnnotationRequest
- AnnotationListResponse
- Annotation
- createdAt
- updatedAt
context_file: json-ld/amplitude-chart-annotations-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-chart-annotations-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Chart Annotations Api from Amplitude.
layout: jsonld
name: Amplitude Chart Annotations Api Context
namespaces:
- prefix: amplitude
  uri: https://amplitude.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: label
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: details
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: chartId
  type: integer
- container: set
  name: data
  type: reference
- container: ''
  name: id
  type: integer
property_count: 8
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-chart-annotations-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateAnnotationRequest\": \"amplitude:UpdateAnnotationRequest\",\n    \"CreateAnnotationRequest\": \"amplitude:CreateAnnotationRequest\",\n    \"AnnotationListResponse\": \"amplitude:AnnotationListResponse\",\n    \"Annotation\": \"amplitude:Annotation\",\n    \"label\": {\n      \"@id\": \"amplitude:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"amplitude:date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"amplitude:end_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"details\": {\n      \"@id\": \"amplitude:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"amplitude:category\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"chartId\": {\n      \"@id\": \"amplitude:chart_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"amplitude:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"amplitude:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-chart-annotations-api-context.jsonld
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

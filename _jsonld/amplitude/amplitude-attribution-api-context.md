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
class_count: 3
classes:
- AttributionEvent
- AttributionResponse
- AttributionRequest
context_file: json-ld/amplitude-attribution-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-attribution-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Attribution Api from Amplitude.
layout: jsonld
name: Amplitude Attribution Api Context
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
  name: userId
  type: string
- container: ''
  name: deviceId
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: osName
  type: string
- container: ''
  name: osVersion
  type: string
- container: ''
  name: deviceBrand
  type: string
- container: ''
  name: deviceManufacturer
  type: string
- container: ''
  name: deviceModel
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: adid
  type: string
- container: ''
  name: idfa
  type: string
- container: ''
  name: idfv
  type: string
- container: ''
  name: userProperties
  type: reference
- container: ''
  name: eventProperties
  type: reference
- container: ''
  name: time
  type: integer
- container: ''
  name: code
  type: integer
- container: ''
  name: eventsIngested
  type: integer
- container: ''
  name: serverUploadTime
  type: integer
- container: ''
  name: apiKey
  type: string
- container: ''
  name: event
  type: reference
property_count: 25
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-attribution-api-context
source_filename: amplitude-attribution-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AttributionEvent\": \"amplitude:AttributionEvent\",\n    \"AttributionResponse\": \"amplitude:AttributionResponse\",\n    \"AttributionRequest\": \"amplitude:AttributionRequest\",\n    \"userId\": {\n      \"@id\": \"amplitude:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceId\": {\n      \"@id\": \"amplitude:device_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"amplitude:event_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"amplitude:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osName\": {\n      \"@id\": \"amplitude:os_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osVersion\": {\n      \"@id\": \"amplitude:os_version\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceBrand\": {\n      \"@id\": \"amplitude:device_brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceManufacturer\": {\n      \"@id\": \"amplitude:device_manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceModel\": {\n      \"@id\": \"amplitude:device_model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"amplitude:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"amplitude:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"amplitude:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"amplitude:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"amplitude:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adid\": {\n      \"@id\": \"amplitude:adid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idfa\": {\n      \"@id\"\
  : \"amplitude:idfa\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idfv\": {\n      \"@id\": \"amplitude:idfv\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProperties\": {\n      \"@id\": \"amplitude:user_properties\",\n      \"@type\": \"@id\"\n    },\n    \"eventProperties\": {\n      \"@id\": \"amplitude:event_properties\",\n      \"@type\": \"@id\"\n    },\n    \"time\": {\n      \"@id\": \"amplitude:time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"code\": {\n      \"@id\": \"amplitude:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"eventsIngested\": {\n      \"@id\": \"amplitude:events_ingested\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serverUploadTime\": {\n      \"@id\": \"amplitude:server_upload_time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"apiKey\": {\n      \"@id\": \"amplitude:api_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"amplitude:event\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-attribution-api-context.jsonld
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

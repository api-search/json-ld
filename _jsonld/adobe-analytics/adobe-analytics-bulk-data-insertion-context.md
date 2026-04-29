---
api_specs:
- filename: adobe-analytics-api-openapi.yml
  format: yaml
  label: Adobe Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/openapi/adobe-analytics-api-openapi.yml
- filename: adobe-analytics-bulk-data-insertion-api-openapi.yml
  format: yaml
  label: Adobe Analytics Bulk Data Insertion API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/openapi/adobe-analytics-bulk-data-insertion-api-openapi.yml
- filename: adobe-analytics-livestream-asyncapi.yml
  format: yaml
  label: Adobe Analytics Livestream API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/asyncapi/adobe-analytics-livestream-asyncapi.yml
- filename: adobe-analytics-data-repair-api-openapi.yml
  format: yaml
  label: Adobe Analytics Data Repair API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/openapi/adobe-analytics-data-repair-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/adobe-analytics-bulk-data-insertion-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/json-ld/adobe-analytics-bulk-data-insertion-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Analytics Bulk Data Insertion from Adobe Analytics.
layout: jsonld
name: Adobe Analytics Bulk Data Insertion Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: UploadResponse
  type: ''
- container: ''
  name: ValidationResponse
  type: ''
- container: ''
  name: ValidationError
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
property_count: 4
provider_name: Adobe Analytics
provider_slug: adobe-analytics
slug: adobe-analytics-bulk-data-insertion-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"UploadResponse\": {\n      \"@id\": \"ns:UploadResponse\",\n      \"@context\": {\n        \"uploadTrackingCode\": {\n          \"@id\": \"ns:uploadTrackingCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fileSize\": {\n          \"@id\": \"ns:fileSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"receivedTime\": {\n          \"@id\": \"ns:receivedTime\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ValidationResponse\": {\n      \"@id\": \"ns:ValidationResponse\",\n      \"@context\": {\n        \"success\": {\n          \"@id\": \"ns:success\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\"\n      }\n    },\n    \"ValidationError\"\
  : {\n      \"@id\": \"ns:ValidationError\",\n      \"@context\": {\n        \"row\": {\n          \"@id\": \"ns:row\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"column\": {\n          \"@id\": \"ns:column\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"ns:ErrorResponse\",\n      \"@context\": {\n        \"errorCode\": {\n          \"@id\": \"ns:errorCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errorDescription\": {\n          \"@id\": \"ns:errorDescription\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/json-ld/adobe-analytics-bulk-data-insertion-context.jsonld
tags:
- Adobe
- Analytics
- Business Intelligence
- Customer Intelligence
- Digital Marketing
- Marketing
- Web Analytics
- JSON-LD
- Linked Data
- Semantic Web
---

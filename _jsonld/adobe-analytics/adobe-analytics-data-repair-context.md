---
api_specs:
- filename: swagger.json
  format: json
  label: Adobe Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/AdobeDocs/analytics-2.0-apis/main/docs/swagger.json
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
context_file: json-ld/adobe-analytics-data-repair-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/json-ld/adobe-analytics-data-repair-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Analytics Data Repair from Adobe Analytics.
layout: jsonld
name: Adobe Analytics Data Repair Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: ServerCallEstimate
  type: ''
- container: ''
  name: RepairJobDefinition
  type: ''
- container: ''
  name: RepairAction
  type: ''
- container: ''
  name: RepairFilter
  type: ''
- container: ''
  name: RepairJob
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
property_count: 6
provider_name: Adobe Analytics
provider_slug: adobe-analytics
slug: adobe-analytics-data-repair-context
source_filename: adobe-analytics-data-repair-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"ServerCallEstimate\": {\n      \"@id\": \"ns:ServerCallEstimate\",\n      \"@context\": {\n        \"reportSuiteId\": {\n          \"@id\": \"ns:reportSuiteId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateRangeStart\": {\n          \"@id\": \"ns:dateRangeStart\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateRangeEnd\": {\n          \"@id\": \"ns:dateRangeEnd\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serverCallEstimate\": {\n          \"@id\": \"ns:serverCallEstimate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"validationToken\": {\n          \"@id\": \"ns:validationToken\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RepairJobDefinition\": {\n      \"@id\": \"ns:RepairJobDefinition\",\n      \"@context\": {\n        \"variables\"\
  : \"ns:variables\"\n      }\n    },\n    \"RepairAction\": {\n      \"@id\": \"ns:RepairAction\",\n      \"@context\": {\n        \"action\": {\n          \"@id\": \"ns:action\",\n          \"@type\": \"xsd:string\"\n        },\n        \"setValue\": {\n          \"@id\": \"ns:setValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"filter\": {\n          \"@id\": \"ns:filter\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RepairFilter\": {\n      \"@id\": \"ns:RepairFilter\",\n      \"@context\": {\n        \"condition\": {\n          \"@id\": \"ns:condition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"matchValue\": {\n          \"@id\": \"ns:matchValue\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RepairJob\": {\n      \"@id\": \"ns:RepairJob\",\n      \"@context\": {\n        \"jobId\": {\n          \"@id\": \"ns:jobId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"reportSuiteId\"\
  : {\n          \"@id\": \"ns:reportSuiteId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateRangeStart\": {\n          \"@id\": \"ns:dateRangeStart\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateRangeEnd\": {\n          \"@id\": \"ns:dateRangeEnd\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"progress\": {\n          \"@id\": \"ns:progress\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"jobCreateTime\": {\n          \"@id\": \"ns:jobCreateTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobCompleteTime\": {\n          \"@id\": \"ns:jobCompleteTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serverCalls\": {\n          \"@id\": \"ns:serverCalls\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"nodesProcessed\": {\n          \"@id\": \"ns:nodesProcessed\",\n    \
  \      \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"ns:ErrorResponse\",\n      \"@context\": {\n        \"errorCode\": {\n          \"@id\": \"ns:errorCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errorDescription\": {\n          \"@id\": \"ns:errorDescription\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-analytics/refs/heads/main/json-ld/adobe-analytics-data-repair-context.jsonld
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

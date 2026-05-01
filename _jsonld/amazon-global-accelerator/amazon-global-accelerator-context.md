---
api_specs:
- filename: amazon-global-accelerator-openapi.yml
  format: yaml
  label: Amazon Global Accelerator API
  slug: amazon-global-accelerator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-global-accelerator/refs/heads/main/openapi/amazon-global-accelerator-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-global-accelerator-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-global-accelerator/refs/heads/main/json-ld/amazon-global-accelerator-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Global Accelerator from Amazon Global Accelerator.
layout: jsonld
name: Amazon Global Accelerator Context
namespaces:
- prefix: ga
  uri: https://docs.aws.amazon.com/global-accelerator/latest/api/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Accelerator
  type: ''
- container: ''
  name: Listener
  type: ''
property_count: 2
provider_name: Amazon Global Accelerator
provider_slug: amazon-global-accelerator
slug: amazon-global-accelerator-context
source_filename: amazon-global-accelerator-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ga\": \"https://docs.aws.amazon.com/global-accelerator/latest/api/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Accelerator\": {\n      \"@id\": \"ga:Accelerator\",\n      \"@context\": {\n        \"acceleratorArn\": \"ga:acceleratorArn\",\n        \"name\": \"schema:name\",\n        \"ipAddressType\": \"ga:ipAddressType\",\n        \"enabled\": \"ga:enabled\",\n        \"dnsName\": \"ga:dnsName\",\n        \"status\": \"ga:status\",\n        \"ipSets\": {\n          \"@id\": \"ga:ipSets\",\n          \"@container\": \"@set\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Listener\"\
  : {\n      \"@id\": \"ga:Listener\",\n      \"@context\": {\n        \"listenerArn\": \"ga:listenerArn\",\n        \"portRanges\": {\n          \"@id\": \"ga:portRanges\",\n          \"@container\": \"@set\"\n        },\n        \"protocol\": \"ga:protocol\",\n        \"clientAffinity\": \"ga:clientAffinity\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-global-accelerator/refs/heads/main/json-ld/amazon-global-accelerator-context.jsonld
tags:
- Availability
- CDN
- Global
- Load Balancing
- Networking
- Performance
- JSON-LD
- Linked Data
- Semantic Web
---

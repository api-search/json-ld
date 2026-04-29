---
class_count: 1
classes:
- DataSource
context_file: json-ld/amazon-q-openapi-data-source-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-data-source-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Q Openapi Data Source from Amazon Q.
layout: jsonld
name: Amazon Q Openapi Data Source Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: dataSourceId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: status
  type: string
property_count: 4
provider_name: Amazon Q
provider_slug: amazon-q
slug: amazon-q-openapi-data-source-context
source_filename: amazon-q-openapi-data-source-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DataSource\": \"aws:DataSource\",\n    \"dataSourceId\": {\n      \"@id\": \"aws:dataSourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"aws:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-data-source-context.jsonld
tags:
- Artificial Intelligence
- Assistant
- AWS
- Enterprise
- Generative AI
- JSON-LD
- Linked Data
- Semantic Web
---

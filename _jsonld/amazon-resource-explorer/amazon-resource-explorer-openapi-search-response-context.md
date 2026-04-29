---
class_count: 1
classes:
- SearchResponse
context_file: json-ld/amazon-resource-explorer-openapi-search-response-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-resource-explorer/refs/heads/main/json-ld/amazon-resource-explorer-openapi-search-response-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Resource Explorer Openapi Search Response from Amazon Resource Explorer.
layout: jsonld
name: Amazon Resource Explorer Openapi Search Response Context
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
  name: Count
  type: string
- container: ''
  name: NextToken
  type: string
- container: set
  name: Resources
  type: string
- container: ''
  name: ViewArn
  type: string
property_count: 4
provider_name: Amazon Resource Explorer
provider_slug: amazon-resource-explorer
slug: amazon-resource-explorer-openapi-search-response-context
source_filename: amazon-resource-explorer-openapi-search-response-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SearchResponse\": \"aws:SearchResponse\",\n    \"Count\": {\n      \"@id\": \"aws:Count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Resources\": {\n      \"@id\": \"aws:Resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ViewArn\": {\n      \"@id\": \"aws:ViewArn\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-resource-explorer/refs/heads/main/json-ld/amazon-resource-explorer-openapi-search-response-context.jsonld
tags:
- AWS
- Discovery
- Inventory
- Operations
- Resource Management
- JSON-LD
- Linked Data
- Semantic Web
---

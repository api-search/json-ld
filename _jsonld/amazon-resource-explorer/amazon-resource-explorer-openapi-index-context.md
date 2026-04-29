---
class_count: 1
classes:
- Index
context_file: json-ld/amazon-resource-explorer-openapi-index-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-resource-explorer/refs/heads/main/json-ld/amazon-resource-explorer-openapi-index-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Resource Explorer Openapi Index from Amazon Resource Explorer.
layout: jsonld
name: Amazon Resource Explorer Openapi Index Context
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
  name: Arn
  type: string
- container: ''
  name: Region
  type: string
- container: ''
  name: Type
  type: string
property_count: 3
provider_name: Amazon Resource Explorer
provider_slug: amazon-resource-explorer
slug: amazon-resource-explorer-openapi-index-context
source_filename: amazon-resource-explorer-openapi-index-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Index\": \"aws:Index\",\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Region\": {\n      \"@id\": \"aws:Region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"aws:Type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-resource-explorer/refs/heads/main/json-ld/amazon-resource-explorer-openapi-index-context.jsonld
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

---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: AWS Resource Explorer API
  slug: aws-resource-explorer-api
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/resource-explorer-2/2022-07-28/openapi.yaml
class_count: 1
classes:
- Resource
context_file: json-ld/amazon-resource-explorer-openapi-resource-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-resource-explorer/refs/heads/main/json-ld/amazon-resource-explorer-openapi-resource-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Resource Explorer Openapi Resource from Amazon Resource Explorer.
layout: jsonld
name: Amazon Resource Explorer Openapi Resource Context
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
  name: LastReportedAt
  type: dateTime
- container: ''
  name: OwningAccountId
  type: string
- container: ''
  name: Region
  type: string
- container: ''
  name: ResourceType
  type: string
- container: ''
  name: Service
  type: string
property_count: 6
provider_name: Amazon Resource Explorer
provider_slug: amazon-resource-explorer
slug: amazon-resource-explorer-openapi-resource-context
source_filename: amazon-resource-explorer-openapi-resource-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Resource\": \"aws:Resource\",\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastReportedAt\": {\n      \"@id\": \"aws:LastReportedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"OwningAccountId\": {\n      \"@id\": \"aws:OwningAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Region\": {\n      \"@id\": \"aws:Region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceType\": {\n      \"@id\": \"aws:ResourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Service\": {\n      \"@id\": \"aws:Service\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-resource-explorer/refs/heads/main/json-ld/amazon-resource-explorer-openapi-resource-context.jsonld
tags:
- Discovery
- Inventory
- Operations
- Resource Management
- JSON-LD
- Linked Data
- Semantic Web
---

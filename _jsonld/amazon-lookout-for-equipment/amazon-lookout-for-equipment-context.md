---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Amazon Lookout for Equipment API
  slug: amazon-lookout-for-equipment-api
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/lookoutequipment/2020-12-15/openapi.yaml
class_count: 2
classes:
- Dataset
- Model
context_file: json-ld/amazon-lookout-for-equipment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-equipment/refs/heads/main/json-ld/amazon-lookout-for-equipment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Lookout For Equipment from Amazon Lookout for Equipment.
layout: jsonld
name: Amazon Lookout For Equipment Context
namespaces:
- prefix: lookoutforequipment
  uri: https://lookoutforequipment.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 7
provider_name: Amazon Lookout for Equipment
provider_slug: amazon-lookout-for-equipment
slug: amazon-lookout-for-equipment-context
source_filename: amazon-lookout-for-equipment-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lookoutforequipment\": \"https://lookoutforequipment.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Dataset\": \"lookoutforequipment:Dataset\",\n    \"Model\": \"lookoutforequipment:Model\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"lookoutforequipment:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"lookoutforequipment:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\"\
  : {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-equipment/refs/heads/main/json-ld/amazon-lookout-for-equipment-context.jsonld
tags:
- Equipment Monitoring
- Industrial IoT
- Machine Learning
- Predictive Maintenance
- JSON-LD
- Linked Data
- Semantic Web
---

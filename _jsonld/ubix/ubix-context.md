---
class_count: 6
classes:
- InsightsAPI
- DataSpace
- ModelSpace
- AIModel
- DataPipeline
- Connector
context_file: json-ld/ubix-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ubix/refs/heads/main/json-ld/ubix-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ubix from UBIX Labs.
layout: jsonld
name: Ubix Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ubix
  uri: https://ubixlabs.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: modelType
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: industry
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: accuracy
  type: double
- container: ''
  name: version
  type: string
- container: ''
  name: connectorType
  type: string
- container: ''
  name: sourceSystem
  type: string
property_count: 11
provider_name: UBIX Labs
provider_slug: ubix
slug: ubix-context
source_filename: ubix-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ubix\": \"https://ubixlabs.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"InsightsAPI\": \"ubix:InsightsAPI\",\n    \"DataSpace\": \"ubix:DataSpace\",\n    \"ModelSpace\": \"ubix:ModelSpace\",\n    \"AIModel\": \"schema:SoftwareApplication\",\n    \"DataPipeline\": \"ubix:DataPipeline\",\n    \"Connector\": \"ubix:Connector\",\n\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"modelType\": { \"@id\": \"ubix:modelType\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"schema:status\", \"@type\": \"xsd:string\" },\n    \"industry\": { \"@id\": \"schema:industry\", \"@type\": \"xsd:string\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updatedAt\": { \"@id\": \"schema:dateModified\"\
  , \"@type\": \"xsd:dateTime\" },\n    \"accuracy\": { \"@id\": \"ubix:accuracy\", \"@type\": \"xsd:double\" },\n    \"version\": { \"@id\": \"schema:version\", \"@type\": \"xsd:string\" },\n    \"connectorType\": { \"@id\": \"ubix:connectorType\", \"@type\": \"xsd:string\" },\n    \"sourceSystem\": { \"@id\": \"ubix:sourceSystem\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ubix/refs/heads/main/json-ld/ubix-context.jsonld
tags:
- Artificial Intelligence
- Analytics
- Machine Learning
- Data Integration
- No-Code
- Enterprise
- Generative AI
- JSON-LD
- Linked Data
- Semantic Web
---

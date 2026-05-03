---
api_specs:
- filename: sophos-central-siem-openapi.yml
  format: yaml
  label: Sophos Central SIEM API
  slug: sophos-central-siem-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sophos/refs/heads/main/openapi/sophos-central-siem-openapi.yml
class_count: 4
classes:
- Alert
- Event
- SecurityEvent
- id
context_file: json-ld/sophos-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sophos/refs/heads/main/json-ld/sophos-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sophos from Sophos.
layout: jsonld
name: Sophos Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sophos
  uri: https://developer.sophos.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: when
  type: dateTime
- container: ''
  name: severity
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: customer_id
  type: string
- container: ''
  name: tenant_id
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: threat
  type: string
- container: ''
  name: endpoint_id
  type: string
- container: ''
  name: endpoint_type
  type: string
property_count: 11
provider_name: Sophos
provider_slug: sophos
slug: sophos-context
source_filename: sophos-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sophos\": \"https://developer.sophos.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Alert\": \"sophos:Alert\",\n    \"Event\": \"sophos:Event\",\n    \"SecurityEvent\": \"schema:Action\",\n\n    \"id\": \"@id\",\n    \"when\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"severity\": {\n      \"@id\": \"sophos:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"schema:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customer_id\": {\n      \"@id\": \"sophos:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenant_id\": {\n      \"@id\": \"sophos:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"schema:location\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"schema:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threat\": {\n      \"@id\": \"sophos:threat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint_id\": {\n      \"@id\": \"sophos:endpointId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint_type\": {\n      \"@id\": \"sophos:endpointType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sophos/refs/heads/main/json-ld/sophos-context.jsonld
tags:
- Cybersecurity
- Endpoint Protection
- Security
- SIEM
- Threat Detection
- Incident Response
- JSON-LD
- Linked Data
- Semantic Web
---

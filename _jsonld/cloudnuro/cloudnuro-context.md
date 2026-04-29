---
class_count: 0
classes: []
context_file: json-ld/cloudnuro-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudnuro/refs/heads/main/json-ld/cloudnuro-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudnuro from CloudNuro.
layout: jsonld
name: Cloudnuro Context
namespaces:
- prefix: cn
  uri: https://cloudnuro.ai/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: SaaSApplication
  type: ''
- container: ''
  name: License
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Contract
  type: ''
- container: ''
  name: Chargeback
  type: ''
property_count: 5
provider_name: CloudNuro
provider_slug: cloudnuro
slug: cloudnuro-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cn\": \"https://cloudnuro.ai/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"SaaSApplication\": {\n      \"@id\": \"cn:SaaSApplication\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"vendor\": \"schema:provider\",\n        \"category\": \"schema:applicationCategory\",\n        \"discoveredAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"License\": {\n      \"@id\": \"cn:License\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"applicationId\": \"cn:applicationId\",\n        \"type\": \"cn:licenseType\",\n        \"assigned\": \"cn:assigned\",\n        \"available\": \"cn:available\",\n        \"cost\": \"schema:price\"\n      }\n    },\n\n    \"User\"\
  : {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"department\": \"cn:department\",\n        \"manager\": \"cn:manager\",\n        \"lastActive\": {\n          \"@id\": \"cn:lastActive\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Contract\": {\n      \"@id\": \"cn:Contract\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"applicationId\": \"cn:applicationId\",\n        \"vendor\": \"schema:provider\",\n        \"renewalDate\": {\n          \"@id\": \"cn:renewalDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"amount\": \"schema:price\"\n      }\n    },\n\n    \"Chargeback\": {\n      \"@id\": \"cn:Chargeback\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"costCenter\": \"cn:costCenter\",\n        \"department\": \"cn:department\",\n        \"applicationId\": \"cn:applicationId\",\n \
  \       \"amount\": \"schema:price\",\n        \"period\": \"cn:period\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudnuro/refs/heads/main/json-ld/cloudnuro-context.jsonld
tags:
- Cloud FinOps
- Compliance
- Cost Optimization
- License Management
- SaaS Management
- Shadow IT
- SSPM
- JSON-LD
- Linked Data
- Semantic Web
---

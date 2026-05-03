---
class_count: 14
classes:
- id
- name
- description
- url
- folder
- status
- createdAt
- updatedAt
- key
- type
- plan
- endpointCount
- requestsThisMonth
- email
context_file: json-ld/stepzen-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stepzen/refs/heads/main/json-ld/stepzen-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stepzen from StepZen.
layout: jsonld
name: Stepzen Context
namespaces:
- prefix: stepzen
  uri: https://stepzen.com/vocab/
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Endpoint
  type: reference
- container: ''
  name: ApiKey
  type: reference
- container: ''
  name: Account
  type: reference
property_count: 3
provider_name: StepZen
provider_slug: stepzen
slug: stepzen-context
source_filename: stepzen-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"stepzen\": \"https://stepzen.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"Endpoint\": {\n      \"@id\": \"stepzen:Endpoint\",\n      \"@type\": \"@id\"\n    },\n    \"ApiKey\": {\n      \"@id\": \"stepzen:ApiKey\",\n      \"@type\": \"@id\"\n    },\n    \"Account\": {\n      \"@id\": \"stepzen:Account\",\n      \"@type\": \"@id\"\n    },\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"folder\": \"stepzen:schemaFolder\",\n    \"status\": \"stepzen:deploymentStatus\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"key\": \"stepzen:apiKey\",\n    \"type\": \"schema:additionalType\",\n    \"plan\": \"schema:priceSpecification\",\n    \"endpointCount\": \"stepzen:endpointCount\",\n    \"requestsThisMonth\": \"stepzen:monthlyRequests\",\n    \"email\": \"schema:email\"\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stepzen/refs/heads/main/json-ld/stepzen-context.jsonld
tags:
- Backend Integration
- GraphQL
- API Gateway
- REST to GraphQL
- IBM
- Data Federation
- JSON-LD
- Linked Data
- Semantic Web
---

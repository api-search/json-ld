---
class_count: 5
classes:
- Guideline
- Policy
- Review
- title
- description
context_file: json-ld/apigovernance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apigovernance-dev/refs/heads/main/json-ld/apigovernance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apigovernance from APIGovernance.Dev.
layout: jsonld
name: Apigovernance Context
namespaces:
- prefix: gov
  uri: https://apigovernance.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: score
  type: double
- container: ''
  name: status
  type: string
- container: ''
  name: enforcement
  type: string
- container: ''
  name: createdAt
  type: dateTime
property_count: 7
provider_name: APIGovernance.Dev
provider_slug: apigovernance-dev
slug: apigovernance-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gov\": \"https://apigovernance.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Guideline\": \"gov:Guideline\",\n    \"Policy\": \"gov:Policy\",\n    \"Review\": \"gov:Review\",\n    \"id\": {\n      \"@id\": \"gov:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"category\": {\n      \"@id\": \"gov:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"gov:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"score\": {\n      \"@id\": \"gov:score\",\n      \"@type\": \"xsd:double\"\n    },\n    \"status\": {\n      \"@id\": \"gov:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enforcement\": {\n      \"@id\": \"gov:enforcement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apigovernance-dev/refs/heads/main/json-ld/apigovernance-context.jsonld
tags:
- API Design
- API Governance
- Best Practices
- Compliance
- Guidelines
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 1
classes:
- Application
context_file: json-ld/amazon-q-openapi-application-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-application-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Q Openapi Application from Amazon Q.
layout: jsonld
name: Amazon Q Openapi Application Context
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
  name: applicationId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 5
provider_name: Amazon Q
provider_slug: amazon-q
slug: amazon-q-openapi-application-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Application\": \"aws:Application\",\n    \"applicationId\": {\n      \"@id\": \"aws:applicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"aws:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"aws:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/json-ld/amazon-q-openapi-application-context.jsonld
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

---
api_specs:
- filename: agrio-openapi-original.yml
  format: yaml
  label: Agrio Agriculture API
  slug: agrio
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agrio/refs/heads/main/openapi/agrio-openapi-original.yml
class_count: 7
classes:
- Credit Balance
- Diagnose Request
- Diagnosis Result
- Diagnosis
- Crop
- Supported Crops Response
- Error Response
context_file: json-ld/agrio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agrio/refs/heads/main/json-ld/agrio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agrio from agrio.
layout: jsonld
name: Agrio Context
namespaces:
- prefix: agrio
  uri: https://agrio.app/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: balance
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: cropId
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: confidence
  type: double
- container: ''
  name: commonName
  type: string
- container: ''
  name: scientificName
  type: string
- container: ''
  name: crop
  type: string
- container: ''
  name: cropConfidence
  type: string
- container: set
  name: idArray
  type: string
- container: set
  name: crops
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: status
  type: integer
property_count: 16
provider_name: agrio
provider_slug: agrio
slug: agrio-context
source_filename: agrio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agrio\": \"https://agrio.app/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Credit Balance\": \"agrio:Credit Balance\",\n    \"balance\": {\n      \"@id\": \"agrio:balance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currency\": {\n      \"@id\": \"agrio:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"agrio:account_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Diagnose Request\": \"agrio:Diagnose Request\",\n    \"cropId\": {\n      \"@id\": \"agrio:crop_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"agrio:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Diagnosis Result\": \"agrio:Diagnosis Result\",\n    \"id\": {\n      \"@id\": \"agrio:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confidence\": {\n\
  \      \"@id\": \"agrio:confidence\",\n      \"@type\": \"xsd:double\"\n    },\n    \"commonName\": {\n      \"@id\": \"agrio:commonName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scientificName\": {\n      \"@id\": \"agrio:scientificName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Diagnosis\": \"agrio:Diagnosis\",\n    \"crop\": {\n      \"@id\": \"agrio:crop\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cropConfidence\": {\n      \"@id\": \"agrio:cropConfidence\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idArray\": {\n      \"@id\": \"agrio:idArray\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Crop\": \"agrio:Crop\",\n    \"Supported Crops Response\": \"agrio:Supported Crops Response\",\n    \"crops\": {\n      \"@id\": \"agrio:crops\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Error Response\": \"agrio:Error Response\",\n    \"error\": {\n      \"@id\": \"agrio:error\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"agrio:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"agrio:status\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agrio/refs/heads/main/json-ld/agrio-context.jsonld
tags:
- Agriculture
- Plant Disease
- Pest Detection
- AI
- Crop Advisory
- JSON-LD
- Linked Data
- Semantic Web
---

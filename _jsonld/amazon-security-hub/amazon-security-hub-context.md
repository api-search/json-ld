---
api_specs:
- filename: amazon-security-hub-openapi.yml
  format: yaml
  label: AWS Security Hub API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-security-hub/refs/heads/main/openapi/amazon-security-hub-openapi.yml
class_count: 1
classes:
- Finding
context_file: json-ld/amazon-security-hub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-security-hub/refs/heads/main/json-ld/amazon-security-hub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Security Hub from Amazon Security Hub.
layout: jsonld
name: Amazon Security Hub Context
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
  name: SchemaVersion
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: ProductArn
  type: string
- container: ''
  name: GeneratorId
  type: string
- container: ''
  name: AwsAccountId
  type: string
- container: set
  name: Types
  type: string
- container: ''
  name: CreatedAt
  type: dateTime
- container: ''
  name: UpdatedAt
  type: dateTime
- container: ''
  name: Severity
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Description
  type: string
- container: set
  name: Resources
  type: string
- container: ''
  name: Compliance
  type: string
- container: ''
  name: Workflow
  type: string
- container: ''
  name: RecordState
  type: string
property_count: 15
provider_name: Amazon Security Hub
provider_slug: amazon-security-hub
slug: amazon-security-hub-context
source_filename: amazon-security-hub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Finding\": \"aws:Finding\",\n    \"SchemaVersion\": {\n      \"@id\": \"aws:SchemaVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"aws:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductArn\": {\n      \"@id\": \"aws:ProductArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GeneratorId\": {\n      \"@id\": \"aws:GeneratorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AwsAccountId\": {\n      \"@id\": \"aws:AwsAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Types\": {\n      \"@id\": \"aws:Types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedAt\": {\n      \"@id\": \"aws:CreatedAt\",\n      \"@type\": \"xsd:dateTime\"\n \
  \   },\n    \"UpdatedAt\": {\n      \"@id\": \"aws:UpdatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Severity\": {\n      \"@id\": \"aws:Severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"aws:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"aws:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Resources\": {\n      \"@id\": \"aws:Resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Compliance\": {\n      \"@id\": \"aws:Compliance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Workflow\": {\n      \"@id\": \"aws:Workflow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecordState\": {\n      \"@id\": \"aws:RecordState\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-security-hub/refs/heads/main/json-ld/amazon-security-hub-context.jsonld
tags:
- AWS
- Compliance
- Monitoring
- Security
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 6
classes:
- Tag
- Project
- CreateProjectRequest
- ListProjectsResponse
- createdAt
- updatedAt
context_file: json-ld/amazon-monitron-monitron-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-monitron/refs/heads/main/json-ld/amazon-monitron-monitron-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Monitron Monitron Api from Amazon Monitron.
layout: jsonld
name: Amazon Monitron Monitron Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: projectArn
  type: string
- container: ''
  name: projectName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: kmsKeyId
  type: string
- container: ''
  name: tags
  type: reference
- container: set
  name: items
  type: string
- container: ''
  name: nextToken
  type: string
property_count: 10
provider_name: Amazon Monitron
provider_slug: amazon-monitron
slug: amazon-monitron-monitron-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Tag\": \"pan:Tag\",\n    \"Project\": \"pan:Project\",\n    \"CreateProjectRequest\": \"pan:CreateProjectRequest\",\n    \"ListProjectsResponse\": \"pan:ListProjectsResponse\",\n    \"key\": {\n      \"@id\": \"pan:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"projectArn\": {\n      \"@id\": \"pan:project_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectName\": {\n      \"@id\": \"pan:project_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": \"schema:dateModified\",\n    \"clientToken\"\
  : {\n      \"@id\": \"pan:client_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"pan:kms_key_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@type\": \"@id\"\n    },\n    \"items\": {\n      \"@id\": \"pan:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:next_token\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-monitron/refs/heads/main/json-ld/amazon-monitron-monitron-api-context.jsonld
tags:
- AWS
- Broadcasting
- Media Processing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---

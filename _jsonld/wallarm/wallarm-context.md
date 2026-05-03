---
api_specs:
- filename: wallarm-openapi.yml
  format: yaml
  label: Wallarm API
  slug: wallarm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wallarm/refs/heads/main/openapi/wallarm-openapi.yml
class_count: 9
classes:
- Attack
- Vulnerability
- SecurityRule
- IpRule
- FilterNode
- Integration
- Trigger
- id
- type
context_file: json-ld/wallarm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wallarm/refs/heads/main/json-ld/wallarm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wallarm from Wallarm.
layout: jsonld
name: Wallarm Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: wallarm
  uri: https://docs.wallarm.com/api/#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: attackType
  type: string
- container: ''
  name: detectedAt
  type: dateTime
- container: ''
  name: domain
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: method
  type: string
- container: ''
  name: status
  type: integer
- container: ''
  name: severity
  type: string
- container: ''
  name: blocked
  type: boolean
- container: ''
  name: ruleType
  type: string
- container: ''
  name: ipList
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: version
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: integrationProvider
  type: string
property_count: 14
provider_name: Wallarm
provider_slug: wallarm
slug: wallarm-context
source_filename: wallarm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"wallarm\": \"https://docs.wallarm.com/api/#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Attack\": \"wallarm:Attack\",\n    \"Vulnerability\": \"wallarm:Vulnerability\",\n    \"SecurityRule\": \"wallarm:SecurityRule\",\n    \"IpRule\": \"wallarm:IpRule\",\n    \"FilterNode\": \"wallarm:FilterNode\",\n    \"Integration\": \"wallarm:Integration\",\n    \"Trigger\": \"wallarm:Trigger\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"attackType\": {\n      \"@id\": \"wallarm:attackType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectedAt\": {\n      \"@id\": \"wallarm:detectedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"domain\": {\n      \"@id\": \"schema:domainIncludes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"wallarm:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"method\": {\n      \"@id\"\
  : \"wallarm:httpMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"wallarm:httpStatus\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severity\": {\n      \"@id\": \"wallarm:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blocked\": {\n      \"@id\": \"wallarm:blocked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ruleType\": {\n      \"@id\": \"wallarm:ruleType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipList\": {\n      \"@id\": \"wallarm:ipList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"wallarm:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"schema:hostName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integrationProvider\": {\n      \"@id\": \"wallarm:integrationProvider\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wallarm/refs/heads/main/json-ld/wallarm-context.jsonld
tags:
- API Security
- Security Testing
- WAF
- Cybersecurity
- JSON-LD
- Linked Data
- Semantic Web
---

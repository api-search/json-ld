---
api_specs:
- filename: alchemy-gas-manager-api-openapi.yml
  format: yaml
  label: Alchemy Gas Manager API
  slug: alchemy-gas-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/openapi/alchemy-gas-manager-api-openapi.yml
- filename: alchemy-token-api-openapi.yml
  format: yaml
  label: Alchemy Token API
  slug: alchemy-token-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/openapi/alchemy-token-api-openapi.yml
- filename: alchemy-transfers-api-openapi.yml
  format: yaml
  label: Alchemy Transfers API
  slug: alchemy-transfers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/openapi/alchemy-transfers-api-openapi.yml
class_count: 7
classes:
- Sponsor User Operation Response
- Sponsor User Operation Result
- Policy List Response
- Sponsor User Operation Request
- Gas Manager Policy
- Create Policy Request
- name
context_file: json-ld/alchemy-gas-manager-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/json-ld/alchemy-gas-manager-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alchemy Gas Manager Api from Alchemy.
layout: jsonld
name: Alchemy Gas Manager Api Context
namespaces:
- prefix: alchemy
  uri: https://alchemy.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: callGasLimit
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: jsonrpc
  type: string
- container: ''
  name: maxSpendPerUser
  type: decimal
- container: ''
  name: maxSpendTotal
  type: decimal
- container: ''
  name: method
  type: string
- container: ''
  name: network
  type: string
- container: set
  name: params
  type: string
- container: ''
  name: paymasterAndData
  type: string
- container: set
  name: policies
  type: reference
- container: ''
  name: policyId
  type: string
- container: ''
  name: preVerificationGas
  type: string
- container: ''
  name: result
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: verificationGasLimit
  type: string
property_count: 15
provider_name: Alchemy
provider_slug: alchemy
slug: alchemy-gas-manager-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alchemy\": \"https://alchemy.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Sponsor User Operation Response\": \"alchemy:Sponsor User Operation Response\",\n    \"Sponsor User Operation Result\": \"alchemy:Sponsor User Operation Result\",\n    \"Policy List Response\": \"alchemy:Policy List Response\",\n    \"Sponsor User Operation Request\": \"alchemy:Sponsor User Operation Request\",\n    \"Gas Manager Policy\": \"alchemy:Gas Manager Policy\",\n    \"Create Policy Request\": \"alchemy:Create Policy Request\",\n    \"callGasLimit\": {\n      \"@id\": \"alchemy:callGasLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"alchemy:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jsonrpc\": {\n      \"@id\": \"alchemy:jsonrpc\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"maxSpendPerUser\": {\n      \"@id\": \"alchemy:maxSpendPerUser\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"maxSpendTotal\": {\n      \"@id\": \"alchemy:maxSpendTotal\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"method\": {\n      \"@id\": \"alchemy:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"network\": {\n      \"@id\": \"alchemy:network\",\n      \"@type\": \"xsd:string\"\n    },\n    \"params\": {\n      \"@id\": \"alchemy:params\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymasterAndData\": {\n      \"@id\": \"alchemy:paymasterAndData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policies\": {\n      \"@id\": \"alchemy:policies\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"policyId\": {\n      \"@id\": \"alchemy:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preVerificationGas\": {\n      \"@id\": \"alchemy:preVerificationGas\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"alchemy:result\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"alchemy:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationGasLimit\": {\n      \"@id\": \"alchemy:verificationGasLimit\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/json-ld/alchemy-gas-manager-api-context.jsonld
tags:
- Blockchain
- Cryptocurrency
- Web3
- Account Abstraction
- Ethereum
- JSON-LD
- Linked Data
- Semantic Web
---

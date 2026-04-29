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
class_count: 6
classes:
- Token Balance
- Token Balances Result
- Token Metadata Response
- Token Balances Response
- Token Metadata
- name
context_file: json-ld/alchemy-token-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/json-ld/alchemy-token-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alchemy Token Api from Alchemy.
layout: jsonld
name: Alchemy Token Api Context
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
  name: address
  type: string
- container: ''
  name: contractAddress
  type: string
- container: ''
  name: decimals
  type: integer
- container: ''
  name: error
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: jsonrpc
  type: string
- container: ''
  name: logo
  type: reference
- container: ''
  name: pageKey
  type: string
- container: ''
  name: result
  type: reference
- container: ''
  name: symbol
  type: string
- container: ''
  name: tokenBalance
  type: string
- container: set
  name: tokenBalances
  type: reference
property_count: 12
provider_name: Alchemy
provider_slug: alchemy
slug: alchemy-token-api-context
source_filename: alchemy-token-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alchemy\": \"https://alchemy.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Token Balance\": \"alchemy:Token Balance\",\n    \"Token Balances Result\": \"alchemy:Token Balances Result\",\n    \"Token Metadata Response\": \"alchemy:Token Metadata Response\",\n    \"Token Balances Response\": \"alchemy:Token Balances Response\",\n    \"Token Metadata\": \"alchemy:Token Metadata\",\n    \"address\": {\n      \"@id\": \"alchemy:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contractAddress\": {\n      \"@id\": \"alchemy:contractAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"decimals\": {\n      \"@id\": \"alchemy:decimals\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error\": {\n      \"@id\": \"alchemy:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\"\
  : \"alchemy:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jsonrpc\": {\n      \"@id\": \"alchemy:jsonrpc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logo\": {\n      \"@id\": \"alchemy:logo\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"pageKey\": {\n      \"@id\": \"alchemy:pageKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"alchemy:result\",\n      \"@type\": \"@id\"\n    },\n    \"symbol\": {\n      \"@id\": \"alchemy:symbol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenBalance\": {\n      \"@id\": \"alchemy:tokenBalance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenBalances\": {\n      \"@id\": \"alchemy:tokenBalances\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/json-ld/alchemy-token-api-context.jsonld
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

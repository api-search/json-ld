---
class_count: 4
classes:
- Asset Transfer
- Asset Transfers Response
- Asset Transfers Result
- Transfer Metadata
context_file: json-ld/alchemy-transfers-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/json-ld/alchemy-transfers-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alchemy Transfers Api from Alchemy.
layout: jsonld
name: Alchemy Transfers Api Context
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
  name: asset
  type: string
- container: ''
  name: blockNum
  type: string
- container: ''
  name: blockTimestamp
  type: dateTime
- container: ''
  name: category
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: hash
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: jsonrpc
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: pageKey
  type: string
- container: ''
  name: result
  type: reference
- container: ''
  name: to
  type: string
- container: set
  name: transfers
  type: reference
- container: ''
  name: value
  type: decimal
property_count: 14
provider_name: Alchemy
provider_slug: alchemy
slug: alchemy-transfers-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alchemy\": \"https://alchemy.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Asset Transfer\": \"alchemy:Asset Transfer\",\n    \"Asset Transfers Response\": \"alchemy:Asset Transfers Response\",\n    \"Asset Transfers Result\": \"alchemy:Asset Transfers Result\",\n    \"Transfer Metadata\": \"alchemy:Transfer Metadata\",\n    \"asset\": {\n      \"@id\": \"alchemy:asset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockNum\": {\n      \"@id\": \"alchemy:blockNum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockTimestamp\": {\n      \"@id\": \"alchemy:blockTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"category\": {\n      \"@id\": \"alchemy:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"alchemy:from\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"hash\": {\n      \"@id\": \"alchemy:hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"alchemy:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jsonrpc\": {\n      \"@id\": \"alchemy:jsonrpc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"alchemy:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"pageKey\": {\n      \"@id\": \"alchemy:pageKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"alchemy:result\",\n      \"@type\": \"@id\"\n    },\n    \"to\": {\n      \"@id\": \"alchemy:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transfers\": {\n      \"@id\": \"alchemy:transfers\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"alchemy:value\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alchemy/refs/heads/main/json-ld/alchemy-transfers-api-context.jsonld
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

---
api_specs:
- filename: uniblock-unified-api-openapi.yml
  format: yaml
  label: Uniblock Unified API
  slug: unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/openapi/uniblock-unified-api-openapi.yml
- filename: uniblock-direct-api-openapi.yml
  format: yaml
  label: Uniblock Direct API
  slug: direct-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/openapi/uniblock-direct-api-openapi.yml
- filename: uniblock-json-rpc-api-openapi.yml
  format: yaml
  label: Uniblock JSON-RPC API
  slug: json-rpc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/openapi/uniblock-json-rpc-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/uniblock-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/json-ld/uniblock-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uniblock from Uniblock.
layout: jsonld
name: Uniblock Context
namespaces:
- prefix: uniblock
  uri: https://uniblock.dev/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Token
  type: ''
- container: ''
  name: NFT
  type: ''
- container: ''
  name: NftCollection
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: TokenTransfer
  type: ''
- container: ''
  name: MarketData
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 7
provider_name: Uniblock
provider_slug: uniblock
slug: uniblock-context
source_filename: uniblock-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uniblock\": \"https://uniblock.dev/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Token\": {\n      \"@id\": \"uniblock:Token\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"symbol\": \"uniblock:symbol\",\n        \"decimals\": {\n          \"@id\": \"uniblock:decimals\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"contractAddress\": \"uniblock:contractAddress\",\n        \"chain\": \"uniblock:chain\",\n        \"logo\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"totalSupply\": {\n          \"@id\": \"uniblock:totalSupply\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"NFT\": {\n      \"@id\": \"uniblock:NFT\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\"\
  : \"schema:description\",\n        \"contractAddress\": \"uniblock:contractAddress\",\n        \"tokenId\": \"uniblock:tokenId\",\n        \"tokenType\": \"uniblock:tokenType\",\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"animationUrl\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"collectionName\": \"uniblock:collectionName\",\n        \"attributes\": {\n          \"@id\": \"uniblock:attributes\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"NftCollection\": {\n      \"@id\": \"uniblock:NftCollection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"contractAddress\": \"uniblock:contractAddress\",\n        \"symbol\": \"uniblock:symbol\",\n        \"totalSupply\": {\n          \"@id\": \"uniblock:totalSupply\",\n          \"@type\": \"xsd:integer\"\n        },\n\
  \        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"floorPrice\": {\n          \"@id\": \"uniblock:floorPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"chain\": \"uniblock:chain\"\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"uniblock:Transaction\",\n      \"@context\": {\n        \"transactionHash\": \"uniblock:transactionHash\",\n        \"from\": \"uniblock:fromAddress\",\n        \"to\": \"uniblock:toAddress\",\n        \"value\": \"uniblock:value\",\n        \"blockNumber\": {\n          \"@id\": \"uniblock:blockNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"blockTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": \"uniblock:status\",\n        \"gasUsed\": \"uniblock:gasUsed\",\n        \"gasPrice\": \"uniblock:gasPrice\",\n        \"nonce\": {\n          \"@id\": \"uniblock:nonce\"\
  ,\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"TokenTransfer\": {\n      \"@id\": \"uniblock:TokenTransfer\",\n      \"@context\": {\n        \"transactionHash\": \"uniblock:transactionHash\",\n        \"from\": \"uniblock:fromAddress\",\n        \"to\": \"uniblock:toAddress\",\n        \"value\": \"uniblock:value\",\n        \"contractAddress\": \"uniblock:contractAddress\",\n        \"tokenName\": \"schema:name\",\n        \"tokenSymbol\": \"uniblock:symbol\",\n        \"blockNumber\": {\n          \"@id\": \"uniblock:blockNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"blockTimestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MarketData\": {\n      \"@id\": \"uniblock:MarketData\",\n      \"@context\": {\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"marketCap\": {\n          \"@id\"\
  : \"uniblock:marketCap\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"volume24h\": {\n          \"@id\": \"uniblock:volume24h\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"contractAddress\": \"uniblock:contractAddress\",\n        \"chain\": \"uniblock:chain\"\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"uniblock:WebhookEvent\",\n      \"@context\": {\n        \"webhookId\": \"uniblock:webhookId\",\n        \"eventType\": \"uniblock:eventType\",\n        \"chain\": \"uniblock:chain\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/json-ld/uniblock-context.jsonld
tags:
- Blockchain
- Web3
- JSON-LD
- Linked Data
- Semantic Web
---

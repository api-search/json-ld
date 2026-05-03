---
api_specs:
- filename: uniswap-trading-openapi.yaml
  format: yaml
  label: Uniswap Trading API
  slug: uniswap-trading-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/openapi/uniswap-trading-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/uniswap-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-ld/uniswap-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uniswap from Uniswap.
layout: jsonld
name: Uniswap Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: uniswap
  uri: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-ld/uniswap-context.jsonld#
properties:
- container: ''
  name: Token
  type: schema:Thing
- container: ''
  name: Pool
  type: schema:Thing
- container: ''
  name: SwapOrder
  type: schema:Order
- container: ''
  name: LimitOrder
  type: schema:Order
- container: ''
  name: LPPosition
  type: schema:Thing
- container: ''
  name: ExecutionPlan
  type: schema:Thing
- container: ''
  name: tokenAddress
  type: string
- container: ''
  name: tokenSymbol
  type: string
- container: ''
  name: tokenAmount
  type: string
- container: ''
  name: chainId
  type: integer
- container: ''
  name: walletAddress
  type: string
- container: ''
  name: inputToken
  type: uniswap:Token
- container: ''
  name: outputToken
  type: uniswap:Token
- container: ''
  name: slippageTolerance
  type: string
- container: ''
  name: swapStatus
  type: string
- container: ''
  name: gasEstimate
  type: string
- container: ''
  name: priceImpact
  type: decimal
- container: ''
  name: protocols
  type: string
- container: ''
  name: feeAmount
  type: integer
- container: ''
  name: tickLower
  type: integer
- container: ''
  name: tickUpper
  type: integer
- container: ''
  name: liquidity
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: orderId
  type: string
- container: ''
  name: deadline
  type: integer
property_count: 25
provider_name: Uniswap
provider_slug: uniswap
slug: uniswap-context
source_filename: uniswap-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"uniswap\": \"https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-ld/uniswap-context.jsonld#\",\n\n    \"Token\": {\n      \"@id\": \"uniswap:Token\",\n      \"@type\": \"schema:Thing\"\n    },\n    \"Pool\": {\n      \"@id\": \"uniswap:Pool\",\n      \"@type\": \"schema:Thing\"\n    },\n    \"SwapOrder\": {\n      \"@id\": \"uniswap:SwapOrder\",\n      \"@type\": \"schema:Order\"\n    },\n    \"LimitOrder\": {\n      \"@id\": \"uniswap:LimitOrder\",\n      \"@type\": \"schema:Order\"\n    },\n    \"LPPosition\": {\n      \"@id\": \"uniswap:LPPosition\",\n      \"@type\": \"schema:Thing\"\n    },\n    \"ExecutionPlan\": {\n      \"@id\": \"uniswap:ExecutionPlan\",\n      \"@type\": \"schema:Thing\"\n    },\n\n    \"tokenAddress\": {\n      \"@id\": \"uniswap:tokenAddress\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"tokenSymbol\": {\n      \"@id\": \"uniswap:tokenSymbol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenAmount\": {\n      \"@id\": \"uniswap:tokenAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chainId\": {\n      \"@id\": \"uniswap:chainId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"walletAddress\": {\n      \"@id\": \"uniswap:walletAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputToken\": {\n      \"@id\": \"uniswap:inputToken\",\n      \"@type\": \"uniswap:Token\"\n    },\n    \"outputToken\": {\n      \"@id\": \"uniswap:outputToken\",\n      \"@type\": \"uniswap:Token\"\n    },\n    \"slippageTolerance\": {\n      \"@id\": \"uniswap:slippageTolerance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"swapStatus\": {\n      \"@id\": \"uniswap:swapStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gasEstimate\": {\n      \"@id\": \"uniswap:gasEstimate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceImpact\": {\n\
  \      \"@id\": \"uniswap:priceImpact\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"protocols\": {\n      \"@id\": \"uniswap:protocols\",\n      \"@type\": \"xsd:string\"\n    },\n    \"feeAmount\": {\n      \"@id\": \"uniswap:feeAmount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tickLower\": {\n      \"@id\": \"uniswap:tickLower\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tickUpper\": {\n      \"@id\": \"uniswap:tickUpper\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"liquidity\": {\n      \"@id\": \"uniswap:liquidity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deadline\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uniswap/refs/heads/main/json-ld/uniswap-context.jsonld
tags:
- Blockchain
- Cryptocurrency
- DeFi
- Decentralized Exchange
- Liquidity
- Swaps
- JSON-LD
- Linked Data
- Semantic Web
---

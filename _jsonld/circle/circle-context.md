---
class_count: 0
classes: []
context_file: json-ld/circle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/circle/refs/heads/main/json-ld/circle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Circle from Circle.
layout: jsonld
name: Circle Context
namespaces:
- prefix: circle
  uri: https://developers.circle.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Wallet
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Token
  type: ''
- container: ''
  name: Contract
  type: ''
- container: ''
  name: Attestation
  type: ''
- container: ''
  name: Payment
  type: ''
property_count: 6
provider_name: Circle
provider_slug: circle
slug: circle-context
source_filename: circle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"circle\": \"https://developers.circle.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Wallet\": {\n      \"@id\": \"circle:Wallet\",\n      \"@context\": {\n        \"id\": \"circle:id\",\n        \"address\": \"circle:address\",\n        \"blockchain\": \"circle:blockchain\",\n        \"accountType\": \"circle:account_type\",\n        \"custodyType\": \"circle:custody_type\",\n        \"state\": \"circle:state\",\n        \"walletSetId\": \"circle:wallet_set_id\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"circle:Transaction\",\n      \"@context\": {\n  \
  \      \"id\": \"circle:id\",\n        \"blockchain\": \"circle:blockchain\",\n        \"tokenId\": \"circle:token_id\",\n        \"walletId\": \"circle:wallet_id\",\n        \"sourceAddress\": \"circle:source_address\",\n        \"destinationAddress\": \"circle:destination_address\",\n        \"transactionType\": \"circle:transaction_type\",\n        \"state\": \"circle:state\",\n        \"amounts\": \"circle:amounts\",\n        \"txHash\": \"circle:tx_hash\",\n        \"blockHash\": \"circle:block_hash\",\n        \"blockHeight\": \"circle:block_height\",\n        \"networkFee\": \"circle:network_fee\",\n        \"estimatedFee\": \"circle:estimated_fee\",\n        \"createDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Token\": {\n      \"@id\": \"circle:Token\",\n      \"@context\": {\n\
  \        \"id\": \"circle:id\",\n        \"blockchain\": \"circle:blockchain\",\n        \"name\": \"schema:name\",\n        \"symbol\": \"schema:tickerSymbol\",\n        \"decimals\": \"circle:decimals\",\n        \"isNative\": \"circle:is_native\",\n        \"tokenAddress\": \"circle:token_address\"\n      }\n    },\n\n    \"Contract\": {\n      \"@id\": \"circle:Contract\",\n      \"@context\": {\n        \"id\": \"circle:id\",\n        \"blockchain\": \"circle:blockchain\",\n        \"contractAddress\": \"circle:contract_address\",\n        \"contractInputType\": \"circle:contract_input_type\",\n        \"name\": \"schema:name\",\n        \"abiJson\": \"circle:abi_json\",\n        \"deploymentTransactionHash\": \"circle:deployment_transaction_hash\"\n      }\n    },\n\n    \"Attestation\": {\n      \"@id\": \"circle:Attestation\",\n      \"@context\": {\n        \"messageHash\": \"circle:message_hash\",\n        \"message\": \"circle:message\",\n        \"attestation\": \"circle:attestation\"\
  ,\n        \"status\": \"circle:status\"\n      }\n    },\n\n    \"Payment\": {\n      \"@id\": \"circle:Payment\",\n      \"@context\": {\n        \"id\": \"circle:id\",\n        \"amount\": \"circle:amount\",\n        \"currency\": \"circle:currency\",\n        \"source\": \"circle:source\",\n        \"destination\": \"circle:destination\",\n        \"status\": \"circle:status\",\n        \"settlementDate\": {\n          \"@id\": \"circle:settlement_date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/circle/refs/heads/main/json-ld/circle-context.jsonld
tags:
- Blockchain
- Compliance
- Cross-Chain
- Currency
- Money
- Payments
- Stablecoin
- Transfers
- USDC
- Wallets
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: ethereum-json-rpc-openapi.yml
  format: yaml
  label: Ethereum JSON-RPC API
  slug: ethereum-json-rpc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ethereum/refs/heads/main/openapi/ethereum-json-rpc-openapi.yml
class_count: 0
classes: []
context_file: json-ld/ethereum-json-rpc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ethereum/refs/heads/main/json-ld/ethereum-json-rpc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ethereum Json Rpc from Ethereum.
layout: jsonld
name: Ethereum Json Rpc Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: eth
  uri: https://ethereum.org/ns/
- prefix: ethon
  uri: http://ethon.consensys.net/
- prefix: blondie
  uri: http://w3id.org/sioc/ns#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
properties:
- container: ''
  name: Block
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: TransactionReceipt
  type: ''
- container: ''
  name: Log
  type: ''
- container: ''
  name: Withdrawal
  type: ''
- container: ''
  name: AccessListEntry
  type: ''
- container: ''
  name: EthereumNode
  type: ''
- container: ''
  name: Account
  type: ''
property_count: 8
provider_name: Ethereum
provider_slug: ethereum
slug: ethereum-json-rpc-context
source_filename: ethereum-json-rpc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"eth\": \"https://ethereum.org/ns/\",\n    \"ethon\": \"http://ethon.consensys.net/\",\n    \"blondie\": \"http://w3id.org/sioc/ns#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n\n    \"Block\": {\n      \"@id\": \"ethon:Block\",\n      \"@context\": {\n        \"number\": {\n          \"@id\": \"ethon:blockNumber\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"hash\": {\n          \"@id\": \"ethon:blockHash\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"parentHash\": {\n          \"@id\": \"ethon:parentBlockHash\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"miner\": {\n          \"@id\":\
  \ \"ethon:hasBeneficiary\",\n          \"@type\": \"@id\"\n        },\n        \"gasLimit\": {\n          \"@id\": \"ethon:blockGasLimit\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"gasUsed\": {\n          \"@id\": \"ethon:blockGasUsed\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"difficulty\": {\n          \"@id\": \"ethon:blockDifficulty\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"totalDifficulty\": {\n          \"@id\": \"ethon:totalBlockDifficulty\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"size\": {\n          \"@id\": \"ethon:blockSize\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"stateRoot\": {\n          \"@id\": \"ethon:stateRoot\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"transactionsRoot\": {\n          \"@id\": \"ethon:transactionsRoot\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"receiptsRoot\": {\n          \"@id\": \"ethon:receiptsRoot\"\
  ,\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"logsBloom\": {\n          \"@id\": \"ethon:logsBloom\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"extraData\": {\n          \"@id\": \"ethon:extraData\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"baseFeePerGas\": {\n          \"@id\": \"ethon:baseFeePerGas\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"transactions\": {\n          \"@id\": \"ethon:containsTransaction\",\n          \"@container\": \"@list\"\n        },\n        \"uncles\": {\n          \"@id\": \"ethon:hasUncle\",\n          \"@container\": \"@set\"\n        },\n        \"withdrawals\": {\n          \"@id\": \"eth:hasWithdrawal\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"ethon:Tx\",\n      \"@context\": {\n        \"hash\": {\n          \"@id\": \"ethon:txHash\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"from\"\
  : {\n          \"@id\": \"ethon:from\",\n          \"@type\": \"@id\"\n        },\n        \"to\": {\n          \"@id\": \"ethon:to\",\n          \"@type\": \"@id\"\n        },\n        \"value\": {\n          \"@id\": \"ethon:value\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"gas\": {\n          \"@id\": \"ethon:txGasLimit\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"gasPrice\": {\n          \"@id\": \"ethon:txGasPrice\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"maxFeePerGas\": {\n          \"@id\": \"ethon:maxFeePerGas\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"maxPriorityFeePerGas\": {\n          \"@id\": \"ethon:maxPriorityFeePerGas\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"nonce\": {\n          \"@id\": \"ethon:txNonce\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"input\": {\n          \"@id\": \"ethon:txInputData\",\n          \"@type\": \"xsd:hexBinary\"\
  \n        },\n        \"blockHash\": {\n          \"@id\": \"ethon:blockHash\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"blockNumber\": {\n          \"@id\": \"ethon:blockNumber\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"transactionIndex\": {\n          \"@id\": \"ethon:txIndex\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"type\": {\n          \"@id\": \"ethon:txType\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"chainId\": {\n          \"@id\": \"ethon:chainId\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"accessList\": {\n          \"@id\": \"ethon:hasAccessList\",\n          \"@container\": \"@list\"\n        },\n        \"v\": {\n          \"@id\": \"ethon:v\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"r\": {\n          \"@id\": \"ethon:r\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"s\": {\n          \"@id\": \"ethon:s\",\n          \"@type\"\
  : \"xsd:hexBinary\"\n        }\n      }\n    },\n\n    \"TransactionReceipt\": {\n      \"@id\": \"ethon:TxReceipt\",\n      \"@context\": {\n        \"transactionHash\": {\n          \"@id\": \"ethon:txHash\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"blockHash\": {\n          \"@id\": \"ethon:blockHash\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"blockNumber\": {\n          \"@id\": \"ethon:blockNumber\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"from\": {\n          \"@id\": \"ethon:from\",\n          \"@type\": \"@id\"\n        },\n        \"to\": {\n          \"@id\": \"ethon:to\",\n          \"@type\": \"@id\"\n        },\n        \"gasUsed\": {\n          \"@id\": \"ethon:txGasUsed\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"cumulativeGasUsed\": {\n          \"@id\": \"ethon:cumulativeGasUsed\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"effectiveGasPrice\": {\n          \"@id\"\
  : \"ethon:effectiveGasPrice\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"contractAddress\": {\n          \"@id\": \"ethon:createdContract\",\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"ethon:txStatus\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"logs\": {\n          \"@id\": \"ethon:hasLog\",\n          \"@container\": \"@list\"\n        },\n        \"logsBloom\": {\n          \"@id\": \"ethon:logsBloom\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"type\": {\n          \"@id\": \"ethon:txType\",\n          \"@type\": \"xsd:hexBinary\"\n        }\n      }\n    },\n\n    \"Log\": {\n      \"@id\": \"ethon:LogEntry\",\n      \"@context\": {\n        \"address\": {\n          \"@id\": \"ethon:logEmitter\",\n          \"@type\": \"@id\"\n        },\n        \"data\": {\n          \"@id\": \"ethon:logData\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"topics\": {\n     \
  \     \"@id\": \"ethon:hasTopic\",\n          \"@container\": \"@list\"\n        },\n        \"logIndex\": {\n          \"@id\": \"ethon:logIndex\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"transactionHash\": {\n          \"@id\": \"ethon:txHash\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"transactionIndex\": {\n          \"@id\": \"ethon:txIndex\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"blockHash\": {\n          \"@id\": \"ethon:blockHash\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"blockNumber\": {\n          \"@id\": \"ethon:blockNumber\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"removed\": {\n          \"@id\": \"ethon:isRemoved\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Withdrawal\": {\n      \"@id\": \"eth:Withdrawal\",\n      \"@context\": {\n        \"index\": {\n          \"@id\": \"eth:withdrawalIndex\",\n          \"@type\": \"xsd:hexBinary\"\
  \n        },\n        \"validatorIndex\": {\n          \"@id\": \"eth:validatorIndex\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"address\": {\n          \"@id\": \"eth:withdrawalRecipient\",\n          \"@type\": \"@id\"\n        },\n        \"amount\": {\n          \"@id\": \"eth:withdrawalAmount\",\n          \"@type\": \"xsd:hexBinary\"\n        }\n      }\n    },\n\n    \"AccessListEntry\": {\n      \"@id\": \"ethon:AccessListEntry\",\n      \"@context\": {\n        \"address\": {\n          \"@id\": \"ethon:accessedAddress\",\n          \"@type\": \"@id\"\n        },\n        \"storageKeys\": {\n          \"@id\": \"ethon:accessedStorageKey\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"EthereumNode\": {\n      \"@id\": \"eth:Node\",\n      \"@context\": {\n        \"clientVersion\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"networkId\": {\n          \"@id\": \"eth:networkId\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"chainId\": {\n          \"@id\": \"ethon:chainId\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"isListening\": {\n          \"@id\": \"eth:isListening\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"peerCount\": {\n          \"@id\": \"eth:peerCount\",\n          \"@type\": \"xsd:hexBinary\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"ethon:Account\",\n      \"@context\": {\n        \"address\": {\n          \"@id\": \"ethon:address\",\n          \"@type\": \"@id\"\n        },\n        \"balance\": {\n          \"@id\": \"ethon:accountBalance\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"nonce\": {\n          \"@id\": \"ethon:accountNonce\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"code\": {\n          \"@id\": \"ethon:accountCode\",\n          \"@type\": \"xsd:hexBinary\"\n        },\n        \"storageRoot\": {\n          \"\
  @id\": \"ethon:accountStorageRoot\",\n          \"@type\": \"xsd:hexBinary\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ethereum/refs/heads/main/json-ld/ethereum-json-rpc-context.jsonld
tags:
- Blockchain
- DeFi
- Ethereum
- JSON-RPC
- Smart Contracts
- Web3
- JSON-LD
- Linked Data
- Semantic Web
---

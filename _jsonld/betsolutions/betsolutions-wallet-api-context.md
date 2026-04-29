---
api_specs:
- filename: betsolutions-wallet-api.yaml
  format: yaml
  label: BetSolutions Wallet API
  slug: wallet-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/betsolutions/refs/heads/main/openapi/betsolutions-wallet-api.yaml
class_count: 14
classes:
- DepositRequest
- PlayerInfoRequest
- WalletTransactionResponse
- PlayerInfoResponse
- GameListRequest
- ErrorResponse
- BalanceRequest
- GameListResponse
- WithdrawRequest
- AuthResponse
- BalanceResponse
- Game
- email
- name
context_file: json-ld/betsolutions-wallet-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/betsolutions/refs/heads/main/json-ld/betsolutions-wallet-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Betsolutions Wallet Api from BetSolutions.
layout: jsonld
name: Betsolutions Wallet Api Context
namespaces:
- prefix: bs
  uri: https://betsolutions.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: merchantId
  type: string
- container: ''
  name: playerId
  type: string
- container: ''
  name: amount
  type: double
- container: ''
  name: currency
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: hash
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: balance
  type: double
- container: ''
  name: userId
  type: string
- container: ''
  name: userName
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: errorCode
  type: integer
- container: ''
  name: errorMessage
  type: string
- container: set
  name: products
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: gameId
  type: string
- container: ''
  name: productId
  type: integer
- container: ''
  name: hasFreePay
  type: boolean
- container: ''
  name: launchUrl
  type: string
- container: ''
  name: rtp
  type: double
- container: ''
  name: rakePercent
  type: double
property_count: 23
provider_name: BetSolutions
provider_slug: betsolutions
slug: betsolutions-wallet-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bs\": \"https://betsolutions.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DepositRequest\": \"bs:DepositRequest\",\n    \"PlayerInfoRequest\": \"bs:PlayerInfoRequest\",\n    \"WalletTransactionResponse\": \"bs:WalletTransactionResponse\",\n    \"PlayerInfoResponse\": \"bs:PlayerInfoResponse\",\n    \"GameListRequest\": \"bs:GameListRequest\",\n    \"ErrorResponse\": \"bs:ErrorResponse\",\n    \"BalanceRequest\": \"bs:BalanceRequest\",\n    \"GameListResponse\": \"bs:GameListResponse\",\n    \"WithdrawRequest\": \"bs:WithdrawRequest\",\n    \"AuthResponse\": \"bs:AuthResponse\",\n    \"BalanceResponse\": \"bs:BalanceResponse\",\n    \"Game\": \"bs:Game\",\n    \"merchantId\": {\n      \"@id\": \"bs:merchantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playerId\": {\n      \"@id\": \"bs:playerId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"bs:amount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"currency\": {\n      \"@id\": \"bs:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"bs:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hash\": {\n      \"@id\": \"bs:hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n      \"@id\": \"bs:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"balance\": {\n      \"@id\": \"bs:balance\",\n      \"@type\": \"xsd:double\"\n    },\n    \"userId\": {\n      \"@id\": \"bs:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userName\": {\n      \"@id\": \"bs:userName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"bs:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"bs:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\"\
  : \"schema:email\",\n    \"countryCode\": {\n      \"@id\": \"bs:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"bs:errorCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"bs:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"products\": {\n      \"@id\": \"bs:products\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"bs:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gameId\": {\n      \"@id\": \"bs:gameId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productId\": {\n      \"@id\": \"bs:productId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"hasFreePay\": {\n      \"@id\": \"bs:hasFreePay\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"launchUrl\": {\n      \"@id\": \"bs:launchUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rtp\": {\n      \"@id\": \"bs:rtp\"\
  ,\n      \"@type\": \"xsd:double\"\n    },\n    \"rakePercent\": {\n      \"@id\": \"bs:rakePercent\",\n      \"@type\": \"xsd:double\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/betsolutions/refs/heads/main/json-ld/betsolutions-wallet-api-context.jsonld
tags:
- Betting
- Casinos
- Gaming
- Gambling
- Slots
- Sports Betting
- JSON-LD
- Linked Data
- Semantic Web
---

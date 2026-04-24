---
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

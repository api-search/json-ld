---
api_specs:
- filename: nomba-authentication-openapi.yml
  format: yaml
  label: Nomba Authentication API
  slug: authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-authentication-openapi.yml
- filename: nomba-accounts-openapi.yml
  format: yaml
  label: Nomba Accounts API
  slug: accounts
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-accounts-openapi.yml
- filename: nomba-virtual-accounts-openapi.yml
  format: yaml
  label: Nomba Virtual Accounts API
  slug: virtual-accounts
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-virtual-accounts-openapi.yml
- filename: nomba-transfers-openapi.yml
  format: yaml
  label: Nomba Transfers API
  slug: transfers
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-transfers-openapi.yml
- filename: nomba-online-checkout-openapi.yml
  format: yaml
  label: Nomba Online Checkout API
  slug: online-checkout
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-online-checkout-openapi.yml
- filename: nomba-charge-openapi.yml
  format: yaml
  label: Nomba Charge API
  slug: charge
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-charge-openapi.yml
- filename: nomba-transactions-openapi.yml
  format: yaml
  label: Nomba Transactions API
  slug: transactions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-transactions-openapi.yml
- filename: nomba-global-payout-openapi.yml
  format: yaml
  label: Nomba Global Payout API
  slug: global-payout
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-global-payout-openapi.yml
class_count: 0
classes: []
context_file: json-ld/nomba-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/json-ld/nomba-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nomba from Nomba.
layout: jsonld
name: Nomba Context
namespaces:
- prefix: nomba
  uri: https://developer.nomba.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FBC/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: VirtualAccount
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: CheckoutOrder
  type: ''
- container: ''
  name: Transfer
  type: ''
- container: ''
  name: Terminal
  type: ''
- container: ''
  name: Bank
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
- container: ''
  name: GlobalPayout
  type: ''
property_count: 9
provider_name: Nomba
provider_slug: nomba
slug: nomba-context
source_filename: nomba-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nomba\": \"https://developer.nomba.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FBC/\",\n\n    \"Account\": {\n      \"@id\": \"nomba:Account\",\n      \"@context\": {\n        \"accountId\": \"nomba:accountId\",\n        \"accountName\": \"schema:name\",\n        \"accountType\": \"nomba:accountType\",\n        \"status\": \"nomba:status\",\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"balance\": {\n          \"@id\": \"nomba:balance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VirtualAccount\": {\n      \"@id\": \"nomba:VirtualAccount\"\
  ,\n      \"@context\": {\n        \"accountRef\": \"nomba:accountRef\",\n        \"accountName\": \"schema:name\",\n        \"accountNumber\": \"nomba:accountNumber\",\n        \"bankName\": \"schema:bankName\",\n        \"bankCode\": \"nomba:bankCode\",\n        \"status\": \"nomba:status\",\n        \"expiryDate\": {\n          \"@id\": \"nomba:expiryDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"nomba:Transaction\",\n      \"@context\": {\n        \"transactionId\": \"nomba:transactionId\",\n        \"transactionRef\": \"nomba:transactionRef\",\n        \"merchantTxRef\": \"nomba:merchantTxRef\",\n        \"amount\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"fee\": {\n          \"@id\": \"nomba:fee\",\n          \"@type\": \"xsd:decimal\"\
  \n        },\n        \"currency\": {\n          \"@id\": \"schema:currency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": \"nomba:transactionType\",\n        \"source\": \"nomba:transactionSource\",\n        \"status\": \"nomba:status\",\n        \"terminalId\": \"nomba:terminalId\",\n        \"narration\": \"schema:description\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CheckoutOrder\": {\n      \"@id\": \"nomba:CheckoutOrder\",\n      \"@context\": {\n        \"orderReference\": \"nomba:orderReference\",\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  customerEmail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"callbackUrl\": {\n          \"@id\": \"nomba:callbackUrl\",\n          \"@type\": \"@id\"\n        },\n        \"checkoutLink\": {\n          \"@id\": \"nomba:checkoutLink\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"nomba:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Transfer\": {\n      \"@id\": \"nomba:Transfer\",\n      \"@context\": {\n        \"transactionId\": \"nomba:transactionId\",\n        \"amount\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"accountNumber\": \"nomba:accountNumber\",\n        \"accountName\": \"schema:name\",\n        \"bankCode\": \"nomba:bankCode\",\n        \"merchantTxRef\": \"nomba:merchantTxRef\",\n        \"narration\": \"schema:description\",\n    \
  \    \"status\": \"nomba:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Terminal\": {\n      \"@id\": \"nomba:Terminal\",\n      \"@context\": {\n        \"terminalId\": \"nomba:terminalId\",\n        \"serialNumber\": \"nomba:serialNumber\",\n        \"status\": \"nomba:status\",\n        \"assignedAt\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Bank\": {\n      \"@id\": \"nomba:Bank\",\n      \"@context\": {\n        \"bankCode\": \"nomba:bankCode\",\n        \"bankName\": \"schema:name\"\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"nomba:WebhookEvent\",\n      \"@context\": {\n        \"event_type\": \"nomba:eventType\",\n        \"requestId\": {\n          \"@id\": \"nomba:requestId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"data\": \"nomba:eventData\"\n      }\n    },\n\
  \n    \"GlobalPayout\": {\n      \"@id\": \"nomba:GlobalPayout\",\n      \"@context\": {\n        \"transactionId\": \"nomba:transactionId\",\n        \"sourceCurrency\": \"nomba:sourceCurrency\",\n        \"destinationCurrency\": \"nomba:destinationCurrency\",\n        \"sourceAmount\": {\n          \"@id\": \"nomba:sourceAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"destinationAmount\": {\n          \"@id\": \"nomba:destinationAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"rate\": {\n          \"@id\": \"nomba:exchangeRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"paymentMethod\": \"nomba:paymentMethod\",\n        \"status\": \"nomba:status\",\n        \"settledAt\": {\n          \"@id\": \"nomba:settledAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/json-ld/nomba-context.jsonld
tags:
- Payments
- Fintech
- Banking
- Transfers
- Virtual Accounts
- Checkout
- Cross-Border Payments
- Cards
- JSON-LD
- Linked Data
- Semantic Web
---

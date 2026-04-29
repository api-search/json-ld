---
api_specs:
- filename: affirm-direct-api-openapi.yml
  format: yaml
  label: Affirm Direct API
  slug: direct-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-direct-api-openapi.yml
- filename: affirm-checkout-openapi.yml
  format: yaml
  label: Affirm Checkout API
  slug: checkout-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-checkout-openapi.yml
- filename: affirm-transactions-openapi.yml
  format: yaml
  label: Affirm Transactions API
  slug: transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-transactions-openapi.yml
- filename: affirm-promos-openapi.yml
  format: yaml
  label: Affirm Promos API
  slug: promos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-promos-openapi.yml
- filename: affirm-disputes-openapi.yml
  format: yaml
  label: Affirm Disputes API
  slug: disputes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-disputes-openapi.yml
class_count: 4
classes:
- SettlementEvent
- TransactionEvent
- SettlementEventSummary
- Transaction
context_file: json-ld/affirm-transactions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-transactions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Affirm Transactions from affirm.
layout: jsonld
name: Affirm Transactions Context
namespaces:
- prefix: affirm
  uri: https://affirm.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: transactionEventId
  type: string
- container: ''
  name: amount
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: type
  type: string
- container: ''
  name: fee
  type: integer
- container: ''
  name: referenceId
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: totalAmount
  type: integer
- container: ''
  name: eventCount
  type: integer
- container: ''
  name: disbursedAt
  type: dateTime
- container: ''
  name: checkoutId
  type: string
- container: ''
  name: orderId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: amountRefunded
  type: integer
- container: ''
  name: authorizationExpiration
  type: dateTime
- container: ''
  name: providerId
  type: integer
- container: ''
  name: removeTax
  type: boolean
- container: set
  name: events
  type: string
- container: ''
  name: token
  type: string
property_count: 22
provider_name: affirm
provider_slug: affirm
slug: affirm-transactions-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"affirm\": \"https://affirm.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SettlementEvent\": \"affirm:SettlementEvent\",\n    \"id\": {\n      \"@id\": \"affirm:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionId\": {\n      \"@id\": \"affirm:transaction_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionEventId\": {\n      \"@id\": \"affirm:transaction_event_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"affirm:amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currency\": {\n      \"@id\": \"affirm:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"affirm:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"type\": {\n      \"@id\": \"affirm:type\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"TransactionEvent\": \"affirm:TransactionEvent\",\n    \"fee\": {\n      \"@id\": \"affirm:fee\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"referenceId\": {\n      \"@id\": \"affirm:reference_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"affirm:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"SettlementEventSummary\": \"affirm:SettlementEventSummary\",\n    \"totalAmount\": {\n      \"@id\": \"affirm:total_amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"eventCount\": {\n      \"@id\": \"affirm:event_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"disbursedAt\": {\n      \"@id\": \"affirm:disbursed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Transaction\": \"affirm:Transaction\",\n    \"checkoutId\": {\n      \"@id\": \"affirm:checkout_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderId\": {\n      \"@id\": \"affirm:order_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\"\
  : {\n      \"@id\": \"affirm:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amountRefunded\": {\n      \"@id\": \"affirm:amount_refunded\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"authorizationExpiration\": {\n      \"@id\": \"affirm:authorization_expiration\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"providerId\": {\n      \"@id\": \"affirm:provider_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"removeTax\": {\n      \"@id\": \"affirm:remove_tax\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"events\": {\n      \"@id\": \"affirm:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"affirm:token\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-transactions-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---

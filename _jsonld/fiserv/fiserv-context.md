---
api_specs:
- filename: fiserv-commercehub-openapi.yml
  format: yaml
  label: Fiserv CommerceHub API
  slug: commercehub
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/openapi/fiserv-commercehub-openapi.yml
- filename: fiserv-cardpointe-gateway-openapi.yml
  format: yaml
  label: Fiserv CardPointe Gateway API
  slug: cardpointe-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/openapi/fiserv-cardpointe-gateway-openapi.yml
- filename: fiserv-bankinghub-openapi.yml
  format: yaml
  label: Fiserv BankingHub API
  slug: bankinghub
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/openapi/fiserv-bankinghub-openapi.yml
- filename: fiserv-carddeveloper-openapi.yml
  format: yaml
  label: Fiserv CardDeveloper API
  slug: carddeveloper
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/openapi/fiserv-carddeveloper-openapi.yml
- filename: fiserv-payment-events-asyncapi.yml
  format: yaml
  label: Fiserv Payment Events
  slug: payment-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/asyncapi/fiserv-payment-events-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/fiserv-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/json-ld/fiserv-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fiserv from Fiserv.
layout: jsonld
name: Fiserv Context
namespaces:
- prefix: fiserv
  uri: https://developer.fiserv.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: pay
  uri: https://www.w3.org/ns/payment#
properties:
- container: ''
  name: PaymentTransaction
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Card
  type: ''
- container: ''
  name: Party
  type: ''
- container: ''
  name: Merchant
  type: ''
- container: ''
  name: Dispute
  type: ''
- container: ''
  name: Transfer
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 8
provider_name: Fiserv
provider_slug: fiserv
slug: fiserv-context
source_filename: fiserv-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fiserv\": \"https://developer.fiserv.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"pay\": \"https://www.w3.org/ns/payment#\",\n\n    \"PaymentTransaction\": {\n      \"@id\": \"fiserv:PaymentTransaction\",\n      \"@context\": {\n        \"transactionId\": \"fiserv:transactionId\",\n        \"orderId\": \"fiserv:orderId\",\n        \"merchantId\": \"fiserv:merchantId\",\n        \"transactionType\": \"fiserv:transactionType\",\n        \"transactionState\": \"fiserv:transactionState\",\n        \"amount\": \"schema:price\",\n        \"currency\": \"schema:priceCurrency\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"settlementDate\": {\n          \"@id\": \"fiserv:settlementDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"paymentSource\": \"fiserv:paymentSource\",\n        \"processorResponse\": \"fiserv:processorResponse\"\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"fiserv:Account\",\n      \"@context\": {\n        \"accountId\": \"fiserv:accountId\",\n        \"accountNumber\": \"fiserv:accountNumber\",\n        \"accountType\": \"fiserv:accountType\",\n        \"status\": \"fiserv:accountStatus\",\n        \"currency\": \"schema:priceCurrency\",\n        \"openDate\": {\n          \"@id\": \"fiserv:openDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"closeDate\": {\n          \"@id\": \"fiserv:closeDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"branchId\": \"fiserv:branchId\",\n        \"balances\": \"fiserv:balances\",\n        \"limits\": \"fiserv:limits\",\n        \"owner\": {\n          \"@id\": \"fiserv:owner\",\n\
  \          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Card\": {\n      \"@id\": \"fiserv:Card\",\n      \"@context\": {\n        \"cardNumber\": \"fiserv:cardNumber\",\n        \"cardType\": \"fiserv:cardType\",\n        \"cardBrand\": \"fiserv:cardBrand\",\n        \"status\": \"fiserv:cardStatus\",\n        \"expirationDate\": {\n          \"@id\": \"fiserv:expirationDate\",\n          \"@type\": \"xsd:gYearMonth\"\n        },\n        \"nameOnCard\": \"schema:name\",\n        \"account\": {\n          \"@id\": \"fiserv:account\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Party\": {\n      \"@id\": \"fiserv:Party\",\n      \"@context\": {\n        \"partyId\": \"fiserv:partyId\",\n        \"partyType\": \"fiserv:partyType\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"organizationName\": \"schema:legalName\",\n        \"email\": \"schema:email\",\n        \"phone\": \"schema:telephone\",\n\
  \        \"dateOfBirth\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"address\": \"schema:address\"\n      }\n    },\n\n    \"Merchant\": {\n      \"@id\": \"fiserv:Merchant\",\n      \"@context\": {\n        \"merchantId\": \"fiserv:merchantId\",\n        \"merchantName\": \"schema:name\",\n        \"merchantCategoryCode\": \"fiserv:merchantCategoryCode\",\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Dispute\": {\n      \"@id\": \"fiserv:Dispute\",\n      \"@context\": {\n        \"disputeId\": \"fiserv:disputeId\",\n        \"disputeStatus\": \"fiserv:disputeStatus\",\n        \"reason\": \"fiserv:disputeReason\",\n        \"reasonCode\": \"fiserv:disputeReasonCode\",\n        \"disputeAmount\": \"schema:price\",\n        \"transaction\": {\n          \"@id\": \"fiserv:transaction\",\n          \"@type\": \"@id\"\n        },\n        \"responseDeadline\"\
  : {\n          \"@id\": \"fiserv:responseDeadline\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Transfer\": {\n      \"@id\": \"fiserv:Transfer\",\n      \"@context\": {\n        \"transferId\": \"fiserv:transferId\",\n        \"transferType\": \"fiserv:transferType\",\n        \"amount\": \"schema:price\",\n        \"currency\": \"schema:priceCurrency\",\n        \"fromAccount\": {\n          \"@id\": \"fiserv:fromAccount\",\n          \"@type\": \"@id\"\n        },\n        \"toAccount\": {\n          \"@id\": \"fiserv:toAccount\",\n          \"@type\": \"@id\"\n        },\n        \"scheduledDate\": {\n          \"@id\": \"fiserv:scheduledDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"fiserv:transferStatus\"\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"fiserv:WebhookEvent\",\n      \"@context\": {\n        \"eventId\": \"fiserv:eventId\",\n        \"eventType\": \"fiserv:eventType\",\n        \"timestamp\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/json-ld/fiserv-context.jsonld
tags:
- Banking
- Financial
- Payments
- Wealth Management
- JSON-LD
- Linked Data
- Semantic Web
---

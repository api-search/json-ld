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
class_count: 0
classes: []
context_file: json-ld/affirm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Affirm from affirm.
layout: jsonld
name: Affirm Context
namespaces:
- prefix: affirm
  uri: https://affirm.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: payments
  uri: https://schema.org/
properties:
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: TransactionEvent
  type: ''
- container: ''
  name: Checkout
  type: ''
- container: ''
  name: CheckoutItem
  type: ''
- container: ''
  name: Dispute
  type: ''
- container: ''
  name: PromoOffer
  type: ''
- container: ''
  name: FinancingTerm
  type: ''
- container: ''
  name: VirtualCard
  type: ''
- container: ''
  name: Merchant
  type: ''
property_count: 9
provider_name: affirm
provider_slug: affirm
slug: affirm-context
source_filename: affirm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"affirm\": \"https://affirm.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"payments\": \"https://schema.org/\",\n\n    \"Transaction\": {\n      \"@id\": \"affirm:Transaction\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"checkout_id\": {\n          \"@id\": \"affirm:checkoutId\"\n        },\n        \"order_id\": {\n          \"@id\": \"schema:orderNumber\"\n        },\n        \"status\": {\n          \"@id\": \"affirm:transactionStatus\"\n        },\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"amount_refunded\": {\n          \"@id\": \"affirm:amountRefunded\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\"\n        },\n        \"created\": {\n\
  \          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"authorization_expiration\": {\n          \"@id\": \"affirm:authorizationExpiration\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"provider_id\": {\n          \"@id\": \"affirm:providerId\"\n        },\n        \"events\": {\n          \"@id\": \"affirm:transactionEvents\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"TransactionEvent\": {\n      \"@id\": \"affirm:TransactionEvent\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"type\": {\n          \"@id\": \"affirm:eventType\"\n        },\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\"\n        },\n        \"fee\": {\n          \"@id\": \"affirm:transactionFee\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created\": {\n      \
  \    \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"reference_id\": {\n          \"@id\": \"dcterms:identifier\"\n        },\n        \"metadata\": {\n          \"@id\": \"affirm:metadata\"\n        }\n      }\n    },\n\n    \"Checkout\": {\n      \"@id\": \"affirm:Checkout\",\n      \"@context\": {\n        \"checkout_id\": \"@id\",\n        \"checkout_status\": {\n          \"@id\": \"schema:orderStatus\"\n        },\n        \"order_id\": {\n          \"@id\": \"schema:orderNumber\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\"\n        },\n        \"total\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"shipping_amount\": {\n          \"@id\": \"schema:shippingRate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tax_amount\": {\n          \"@id\": \"schema:taxValue\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"\
  created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"checkout_expiration\": {\n          \"@id\": \"affirm:checkoutExpiration\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"items\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        },\n        \"merchant\": {\n          \"@id\": \"affirm:merchant\"\n        },\n        \"shipping\": {\n          \"@id\": \"schema:shippingDetails\"\n        },\n        \"billing\": {\n          \"@id\": \"schema:billingAddress\"\n        },\n        \"financing_program\": {\n          \"@id\": \"affirm:financingProgram\"\n        },\n        \"metadata\": {\n          \"@id\": \"affirm:metadata\"\n        }\n      }\n    },\n\n    \"CheckoutItem\": {\n      \"@id\": \"affirm:CheckoutItem\",\n      \"@context\": {\n        \"display_name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"sku\": {\n          \"@id\": \"schema:sku\"\
  \n        },\n        \"unit_price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"qty\": {\n          \"@id\": \"schema:orderQuantity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"item_image_url\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"item_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Dispute\": {\n      \"@id\": \"affirm:Dispute\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"transaction_id\": {\n          \"@id\": \"affirm:transactionId\"\n        },\n        \"status\": {\n          \"@id\": \"affirm:disputeStatus\"\n        },\n        \"reason_code\": {\n          \"@id\": \"affirm:reasonCode\"\n        },\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\"\
  \n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"evidence_due_by\": {\n          \"@id\": \"affirm:evidenceDueBy\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closed_at\": {\n          \"@id\": \"affirm:closedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"outcome\": {\n          \"@id\": \"affirm:disputeOutcome\"\n        },\n        \"evidence\": {\n          \"@id\": \"affirm:evidence\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PromoOffer\": {\n      \"@id\": \"affirm:PromoOffer\",\n      \"@context\": {\n        \"ala\": {\n          \"@id\": \"affirm:asLowAs\"\n        },\n        \"html_ala\": {\n          \"@id\": \"affirm:htmlAsLowAs\"\n        },\n        \"headline\": {\n          \"@id\": \"schema:headline\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"minimum_loan_amount\"\
  : {\n          \"@id\": \"affirm:minimumLoanAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"maximum_loan_amount\": {\n          \"@id\": \"affirm:maximumLoanAmount\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"FinancingTerm\": {\n      \"@id\": \"affirm:FinancingTerm\",\n      \"@context\": {\n        \"loan_type\": {\n          \"@id\": \"affirm:loanType\"\n        },\n        \"apr\": {\n          \"@id\": \"schema:annualPercentageRate\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"installment_amount\": {\n          \"@id\": \"affirm:installmentAmount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"installment_count\": {\n          \"@id\": \"affirm:installmentCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"interest_amount\": {\n          \"@id\": \"affirm:interestAmount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_amount\": {\n          \"@id\": \"affirm:totalAmount\"\
  ,\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"VirtualCard\": {\n      \"@id\": \"affirm:VirtualCard\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"checkout_id\": {\n          \"@id\": \"affirm:checkoutId\"\n        },\n        \"status\": {\n          \"@id\": \"affirm:cardStatus\"\n        },\n        \"amount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Merchant\": {\n      \"@id\": \"affirm:Merchant\",\n      \"@context\": {\n        \"user_confirmation_url\": {\n          \"@id\": \"affirm:userConfirmationUrl\",\n          \"@type\": \"@id\"\n        },\n        \"user_cancel_url\": {\n          \"@id\": \"affirm:userCancelUrl\",\n          \"@type\": \"@id\"\n        },\n\
  \        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"public_api_key\": {\n          \"@id\": \"affirm:publicApiKey\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---

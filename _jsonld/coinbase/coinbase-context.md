---
api_specs:
- filename: coinbase-advanced-trade-openapi.yml
  format: yaml
  label: Coinbase Advanced Trade API
  slug: advanced-trade-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-advanced-trade-openapi.yml
- filename: coinbase-exchange-openapi.yml
  format: yaml
  label: Coinbase Exchange API
  slug: exchange-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-exchange-openapi.yml
- filename: coinbase-prime-openapi.yml
  format: yaml
  label: Coinbase Prime API
  slug: prime-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-prime-openapi.yml
- filename: coinbase-onramp-openapi.yml
  format: yaml
  label: Coinbase Onramp API
  slug: onramp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-onramp-openapi.yml
- filename: coinbase-commerce-openapi.yml
  format: yaml
  label: Coinbase Commerce API
  slug: commerce-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/openapi/coinbase-commerce-openapi.yml
class_count: 0
classes: []
context_file: json-ld/coinbase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/json-ld/coinbase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Coinbase from Coinbase.
layout: jsonld
name: Coinbase Context
namespaces:
- prefix: coinbase
  uri: https://api.coinbase.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: fibo-fnd
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: Trade
  type: ''
- container: ''
  name: Portfolio
  type: ''
- container: ''
  name: Charge
  type: ''
- container: ''
  name: Wallet
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Currency
  type: ''
property_count: 9
provider_name: Coinbase
provider_slug: coinbase
slug: coinbase-context
source_filename: coinbase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"coinbase\": \"https://api.coinbase.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"fibo-fnd\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n\n    \"Account\": {\n      \"@id\": \"coinbase:Account\",\n      \"@context\": {\n        \"uuid\": \"coinbase:uuid\",\n        \"name\": \"schema:name\",\n        \"currency\": \"coinbase:currency\",\n        \"available_balance\": \"coinbase:availableBalance\",\n        \"hold\": \"coinbase:hold\",\n        \"active\": \"coinbase:active\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"coinbase:Order\",\n      \"@context\"\
  : {\n        \"order_id\": \"coinbase:orderId\",\n        \"client_order_id\": \"coinbase:clientOrderId\",\n        \"product_id\": \"coinbase:productId\",\n        \"side\": \"coinbase:side\",\n        \"order_type\": \"coinbase:orderType\",\n        \"status\": \"coinbase:status\",\n        \"price\": \"schema:price\",\n        \"size\": \"coinbase:size\",\n        \"filled_size\": \"coinbase:filledSize\",\n        \"average_filled_price\": \"coinbase:averageFilledPrice\",\n        \"total_fees\": \"coinbase:totalFees\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completed_at\": {\n          \"@id\": \"coinbase:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"coinbase:Product\",\n      \"@context\": {\n        \"product_id\": \"coinbase:productId\",\n        \"base_currency\": \"coinbase:baseCurrency\",\n        \"quote_currency\"\
  : \"coinbase:quoteCurrency\",\n        \"display_name\": \"schema:name\",\n        \"status\": \"coinbase:status\",\n        \"price\": \"schema:price\",\n        \"volume_24h\": \"coinbase:volume24h\",\n        \"base_min_size\": \"coinbase:baseMinSize\",\n        \"base_max_size\": \"coinbase:baseMaxSize\",\n        \"quote_increment\": \"coinbase:quoteIncrement\"\n      }\n    },\n\n    \"Trade\": {\n      \"@id\": \"coinbase:Trade\",\n      \"@context\": {\n        \"trade_id\": \"coinbase:tradeId\",\n        \"product_id\": \"coinbase:productId\",\n        \"price\": \"schema:price\",\n        \"size\": \"coinbase:size\",\n        \"side\": \"coinbase:side\",\n        \"time\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Portfolio\": {\n      \"@id\": \"coinbase:Portfolio\",\n      \"@context\": {\n        \"uuid\": \"coinbase:uuid\",\n        \"name\": \"schema:name\",\n        \"type\": \"coinbase:portfolioType\"\
  ,\n        \"entity_id\": \"coinbase:entityId\",\n        \"organization_id\": \"coinbase:organizationId\"\n      }\n    },\n\n    \"Charge\": {\n      \"@id\": \"coinbase:Charge\",\n      \"@context\": {\n        \"code\": \"coinbase:chargeCode\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"pricing_type\": \"coinbase:pricingType\",\n        \"hosted_url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"redirect_url\": {\n          \"@id\": \"coinbase:redirectUrl\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"confirmed_at\": {\n          \"@id\": \"coinbase:confirmedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expires_at\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"payments\": {\n\
  \          \"@id\": \"coinbase:payments\",\n          \"@container\": \"@set\"\n        },\n        \"metadata\": \"coinbase:metadata\"\n      }\n    },\n\n    \"Wallet\": {\n      \"@id\": \"coinbase:Wallet\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"symbol\": \"coinbase:symbol\",\n        \"type\": \"coinbase:walletType\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"coinbase:Transaction\",\n      \"@context\": {\n        \"type\": \"coinbase:transactionType\",\n        \"status\": \"coinbase:status\",\n        \"symbol\": \"coinbase:symbol\",\n        \"amount\": \"schema:amount\",\n        \"fee\": \"coinbase:fee\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completed_at\": {\n          \"@id\": \"coinbase:completedAt\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Currency\": {\n      \"@id\": \"coinbase:Currency\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"symbol\": \"coinbase:symbol\",\n        \"min_size\": \"coinbase:minSize\",\n        \"status\": \"coinbase:status\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/json-ld/coinbase-context.jsonld
tags:
- Blockchain
- Cryptocurrency
- Custody
- Exchange
- Onramp
- Payments
- Trading
- Wallet
- Web3
- JSON-LD
- Linked Data
- Semantic Web
---

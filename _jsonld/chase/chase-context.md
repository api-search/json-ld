---
api_specs:
- filename: chase-account-and-customer-information-api-openapi.yml
  format: yaml
  label: Chase Account and Customer Information API
  slug: account-and-customer-information-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-account-and-customer-information-api-openapi.yml
- filename: chase-account-aggregation-user-consent-api-openapi.yml
  format: yaml
  label: Chase Account Aggregation User Consent API
  slug: account-aggregation-user-consent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-account-aggregation-user-consent-api-openapi.yml
- filename: chase-rewards-balance-api-openapi.yml
  format: yaml
  label: Chase Rewards Balance API
  slug: rewards-balance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-rewards-balance-api-openapi.yml
- filename: chase-loyalty-pay-with-points-order-service-api-openapi.yml
  format: yaml
  label: Chase Loyalty Pay with Points Order Service API
  slug: loyalty-pay-with-points-order-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-loyalty-pay-with-points-order-service-api-openapi.yml
- filename: chase-loyalty-pay-with-points-enrollment-service-api-openapi.yml
  format: yaml
  label: Chase Loyalty Pay with Points Enrollment Service API
  slug: loyalty-pay-with-points-enrollment-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-loyalty-pay-with-points-enrollment-service-api-openapi.yml
- filename: chase-loyalty-pci-merchant-relationship-manager-api-openapi.yml
  format: yaml
  label: Chase Loyalty PCI Merchant Relationship Manager API
  slug: loyalty-pci-merchant-relationship-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-loyalty-pci-merchant-relationship-manager-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/chase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/json-ld/chase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chase from Chase.
layout: jsonld
name: Chase Context
namespaces:
- prefix: chase
  uri: https://developer.chase.com/schemas/
- prefix: fdx
  uri: https://api.fdx.org/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Consent
  type: ''
- container: ''
  name: RewardsBalance
  type: ''
- container: ''
  name: PayWithPointsOrder
  type: ''
property_count: 5
provider_name: Chase
provider_slug: chase
slug: chase-context
source_filename: chase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"chase\": \"https://developer.chase.com/schemas/\",\n    \"fdx\": \"https://api.fdx.org/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Account\": {\n      \"@id\": \"fdx:Account\",\n      \"@context\": {\n        \"accountId\": \"fdx:accountId\",\n        \"accountType\": \"fdx:accountType\",\n        \"accountCategory\": \"fdx:accountCategory\",\n        \"displayName\": \"schema:name\",\n        \"currency\": \"schema:currency\",\n        \"currentBalance\": {\n          \"@id\": \"fdx:currentBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"availableBalance\": {\n          \"@id\": \"fdx:availableBalance\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"fdx:Transaction\",\n      \"@context\": {\n        \"transactionId\"\
  : \"fdx:transactionId\",\n        \"amount\": {\n          \"@id\": \"fdx:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"description\": \"schema:description\",\n        \"postedTimestamp\": {\n          \"@id\": \"fdx:postedTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"transactionTimestamp\": {\n          \"@id\": \"fdx:transactionTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Consent\": {\n      \"@id\": \"fdx:Consent\",\n      \"@context\": {\n        \"consentId\": \"fdx:consentId\",\n        \"permissions\": \"fdx:permissions\",\n        \"status\": \"fdx:consentStatus\",\n        \"expirationTime\": {\n          \"@id\": \"fdx:expirationTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RewardsBalance\": {\n      \"@id\": \"chase:RewardsBalance\",\n      \"@context\": {\n        \"cardToken\": \"chase:cardToken\",\n        \"pointsBalance\": {\n         \
  \ \"@id\": \"chase:pointsBalance\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"cashValue\": {\n          \"@id\": \"chase:cashValue\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"PayWithPointsOrder\": {\n      \"@id\": \"chase:PayWithPointsOrder\",\n      \"@context\": {\n        \"orderId\": \"chase:orderId\",\n        \"merchantId\": \"chase:merchantId\",\n        \"amount\": {\n          \"@id\": \"chase:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"pointsToRedeem\": {\n          \"@id\": \"chase:pointsToRedeem\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": \"chase:orderStatus\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/json-ld/chase-context.jsonld
tags:
- Account Aggregation
- Banking
- Consent
- Credit Cards
- FDX
- Financial Services
- Loyalty
- Open Banking
- Pay with Points
- Rewards
- JSON-LD
- Linked Data
- Semantic Web
---

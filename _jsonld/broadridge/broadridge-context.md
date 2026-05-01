---
api_specs:
- filename: broadridge-wealth-openapi.yml
  format: yaml
  label: Broadridge Wealth Management API
  slug: broadridge-wealth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/openapi/broadridge-wealth-openapi.yml
class_count: 0
classes: []
context_file: json-ld/broadridge-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/json-ld/broadridge-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Broadridge from broadridge.
layout: jsonld
name: Broadridge Context
namespaces:
- prefix: br
  uri: https://api.broadridge.example.com/wealth/
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Position
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: AccountHolder
  type: ''
property_count: 4
provider_name: broadridge
provider_slug: broadridge
slug: broadridge-context
source_filename: broadridge-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"br\": \"https://api.broadridge.example.com/wealth/\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Account\": {\n      \"@id\": \"fibo:FinancialAccount\",\n      \"@context\": {\n        \"accountNumber\": {\"@id\": \"schema:identifier\"},\n        \"accountName\": {\"@id\": \"schema:name\"},\n        \"accountType\": {\"@id\": \"br:accountType\"},\n        \"status\": {\"@id\": \"br:accountStatus\"},\n        \"repId\": {\"@id\": \"br:representativeId\"},\n        \"openDate\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n        \"closeDate\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:date\"},\n        \"primaryHolder\": {\"@id\": \"schema:accountablePerson\"},\n        \"currentValue\": {\"@id\": \"schema:value\", \"@type\": \"xsd:decimal\"},\n        \"currency\": {\"@id\": \"schema:currency\"\
  }\n      }\n    },\n\n    \"Position\": {\n      \"@id\": \"fibo:SecurityPosition\",\n      \"@context\": {\n        \"positionId\": {\"@id\": \"schema:identifier\"},\n        \"accountNumber\": {\"@id\": \"br:accountNumber\"},\n        \"cusip\": {\"@id\": \"fibo:CUSIP\"},\n        \"symbol\": {\"@id\": \"schema:tickerSymbol\"},\n        \"securityDescription\": {\"@id\": \"schema:name\"},\n        \"assetClass\": {\"@id\": \"fibo:assetClass\"},\n        \"quantity\": {\"@id\": \"fibo:numberOfUnits\", \"@type\": \"xsd:decimal\"},\n        \"price\": {\"@id\": \"schema:price\", \"@type\": \"xsd:decimal\"},\n        \"marketValue\": {\"@id\": \"fibo:marketValue\", \"@type\": \"xsd:decimal\"},\n        \"costBasis\": {\"@id\": \"fibo:costBasis\", \"@type\": \"xsd:decimal\"},\n        \"unrealizedGainLoss\": {\"@id\": \"fibo:unrealizedGainLoss\", \"@type\": \"xsd:decimal\"},\n        \"currency\": {\"@id\": \"schema:currency\"},\n        \"asOfDate\": {\"@id\": \"br:asOfDate\", \"@type\"\
  : \"xsd:date\"}\n      }\n    },\n\n    \"Transaction\": {\n      \"@id\": \"schema:MoneyTransfer\",\n      \"@context\": {\n        \"transactionId\": {\"@id\": \"schema:identifier\"},\n        \"accountNumber\": {\"@id\": \"br:accountNumber\"},\n        \"tradeDate\": {\"@id\": \"schema:bookingTime\", \"@type\": \"xsd:date\"},\n        \"settleDate\": {\"@id\": \"br:settleDate\", \"@type\": \"xsd:date\"},\n        \"transactionType\": {\"@id\": \"schema:transactionType\"},\n        \"cusip\": {\"@id\": \"fibo:CUSIP\"},\n        \"symbol\": {\"@id\": \"schema:tickerSymbol\"},\n        \"quantity\": {\"@id\": \"fibo:numberOfUnits\", \"@type\": \"xsd:decimal\"},\n        \"price\": {\"@id\": \"schema:price\", \"@type\": \"xsd:decimal\"},\n        \"netAmount\": {\"@id\": \"br:netAmount\", \"@type\": \"xsd:decimal\"},\n        \"grossAmount\": {\"@id\": \"br:grossAmount\", \"@type\": \"xsd:decimal\"},\n        \"commission\": {\"@id\": \"br:commission\", \"@type\": \"xsd:decimal\"},\n  \
  \      \"currency\": {\"@id\": \"schema:currency\"}\n      }\n    },\n\n    \"AccountHolder\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"firstName\": {\"@id\": \"schema:givenName\"},\n        \"lastName\": {\"@id\": \"schema:familyName\"},\n        \"dateOfBirth\": {\"@id\": \"schema:birthDate\", \"@type\": \"xsd:date\"},\n        \"address\": {\"@id\": \"schema:address\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/json-ld/broadridge-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---

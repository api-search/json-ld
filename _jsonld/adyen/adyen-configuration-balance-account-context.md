---
class_count: 5
classes:
- BalanceAccountBase
- BalanceAccountInfo
- BalanceAccount
- BalanceAccountUpdateRequest
- description
context_file: json-ld/adyen-configuration-balance-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-balance-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Balance Account from Adyen.
layout: jsonld
name: Adyen Configuration Balance Account Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountHolderId
  type: string
- container: ''
  name: defaultCurrencyCode
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: migratedAccountCode
  type: string
- container: ''
  name: platformPaymentConfiguration
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: timeZone
  type: string
- container: set
  name: balances
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-balance-account-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BalanceAccountBase\": \"adyen:BalanceAccountBase\",\n    \"BalanceAccountInfo\": \"adyen:BalanceAccountInfo\",\n    \"BalanceAccount\": \"adyen:BalanceAccount\",\n    \"BalanceAccountUpdateRequest\": \"adyen:BalanceAccountUpdateRequest\",\n    \"accountHolderId\": {\n      \"@id\": \"adyen:accountHolderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultCurrencyCode\": {\n      \"@id\": \"adyen:defaultCurrencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"adyen:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"migratedAccountCode\": {\n      \"@id\"\
  : \"adyen:migratedAccountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformPaymentConfiguration\": {\n      \"@id\": \"adyen:platformPaymentConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"adyen:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balances\": {\n      \"@id\": \"adyen:balances\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-balance-account-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

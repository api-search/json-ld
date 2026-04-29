---
class_count: 1
classes:
- TransactionConditions
context_file: json-ld/adyen-terminal-transaction-conditions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-transaction-conditions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Transaction Conditions from Adyen.
layout: jsonld
name: Adyen Terminal Transaction Conditions Context
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
- container: set
  name: AllowedPaymentBrand
  type: string
- container: set
  name: AcquirerID
  type: integer
- container: ''
  name: DebitPreferredFlag
  type: boolean
- container: set
  name: AllowedLoyaltyBrand
  type: string
- container: ''
  name: LoyaltyHandling
  type: string
- container: ''
  name: CustomerLanguage
  type: string
- container: ''
  name: ForceOnlineFlag
  type: boolean
- container: ''
  name: ForceEntryMode
  type: string
- container: ''
  name: MerchantCategoryCode
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-transaction-conditions-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TransactionConditions\": \"adyen:TransactionConditions\",\n    \"AllowedPaymentBrand\": {\n      \"@id\": \"adyen:AllowedPaymentBrand\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AcquirerID\": {\n      \"@id\": \"adyen:AcquirerID\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DebitPreferredFlag\": {\n      \"@id\": \"adyen:DebitPreferredFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"AllowedLoyaltyBrand\": {\n      \"@id\": \"adyen:AllowedLoyaltyBrand\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyHandling\": {\n      \"@id\": \"adyen:LoyaltyHandling\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerLanguage\"\
  : {\n      \"@id\": \"adyen:CustomerLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForceOnlineFlag\": {\n      \"@id\": \"adyen:ForceOnlineFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ForceEntryMode\": {\n      \"@id\": \"adyen:ForceEntryMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MerchantCategoryCode\": {\n      \"@id\": \"adyen:MerchantCategoryCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-transaction-conditions-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

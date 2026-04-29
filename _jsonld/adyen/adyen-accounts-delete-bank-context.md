---
class_count: 1
classes:
- DeleteBankAccountRequest
context_file: json-ld/adyen-accounts-delete-bank-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-delete-bank-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Delete Bank from Adyen.
layout: jsonld
name: Adyen Accounts Delete Bank Context
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
  name: accountHolderCode
  type: string
- container: set
  name: bankAccountUUIDs
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-delete-bank-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeleteBankAccountRequest\": \"adyen:DeleteBankAccountRequest\",\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountUUIDs\": {\n      \"@id\": \"adyen:bankAccountUUIDs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-delete-bank-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

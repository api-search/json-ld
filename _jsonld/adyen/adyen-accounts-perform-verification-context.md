---
class_count: 1
classes:
- PerformVerificationRequest
context_file: json-ld/adyen-accounts-perform-verification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-perform-verification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Perform Verification from Adyen.
layout: jsonld
name: Adyen Accounts Perform Verification Context
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
- container: ''
  name: accountStateType
  type: string
- container: ''
  name: tier
  type: integer
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-perform-verification-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PerformVerificationRequest\": \"adyen:PerformVerificationRequest\",\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountStateType\": {\n      \"@id\": \"adyen:accountStateType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tier\": {\n      \"@id\": \"adyen:tier\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-perform-verification-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

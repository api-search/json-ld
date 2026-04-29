---
class_count: 1
classes:
- KYCShareholderCheckResult
context_file: json-ld/adyen-accounts-kyc-shareholder-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-shareholder-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Kyc Shareholder from Adyen.
layout: jsonld
name: Adyen Accounts Kyc Shareholder Context
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
  name: checks
  type: string
- container: ''
  name: legalArrangementCode
  type: string
- container: ''
  name: legalArrangementEntityCode
  type: string
- container: ''
  name: shareholderCode
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-kyc-shareholder-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"KYCShareholderCheckResult\": \"adyen:KYCShareholderCheckResult\",\n    \"checks\": {\n      \"@id\": \"adyen:checks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementCode\": {\n      \"@id\": \"adyen:legalArrangementCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntityCode\": {\n      \"@id\": \"adyen:legalArrangementEntityCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholderCode\": {\n      \"@id\": \"adyen:shareholderCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-shareholder-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 2
classes:
- KYCLegalArrangementCheckResult
- KYCLegalArrangementEntityCheckResult
context_file: json-ld/adyen-accounts-kyc-legal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-legal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Kyc Legal from Adyen.
layout: jsonld
name: Adyen Accounts Kyc Legal Context
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
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-kyc-legal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"KYCLegalArrangementCheckResult\": \"adyen:KYCLegalArrangementCheckResult\",\n    \"KYCLegalArrangementEntityCheckResult\": \"adyen:KYCLegalArrangementEntityCheckResult\",\n    \"checks\": {\n      \"@id\": \"adyen:checks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementCode\": {\n      \"@id\": \"adyen:legalArrangementCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntityCode\": {\n      \"@id\": \"adyen:legalArrangementEntityCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-legal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

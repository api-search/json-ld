---
class_count: 1
classes:
- KYCPayoutMethodCheckResult
context_file: json-ld/adyen-accounts-kyc-payout-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-payout-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Kyc Payout from Adyen.
layout: jsonld
name: Adyen Accounts Kyc Payout Context
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
  name: payoutMethodCode
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-kyc-payout-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"KYCPayoutMethodCheckResult\": \"adyen:KYCPayoutMethodCheckResult\",\n    \"checks\": {\n      \"@id\": \"adyen:checks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutMethodCode\": {\n      \"@id\": \"adyen:payoutMethodCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-payout-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

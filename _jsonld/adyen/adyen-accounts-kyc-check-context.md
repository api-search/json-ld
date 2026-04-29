---
class_count: 3
classes:
- KYCCheckResult
- KYCCheckStatusData
- KYCCheckSummary
context_file: json-ld/adyen-accounts-kyc-check-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-check-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Kyc Check from Adyen.
layout: jsonld
name: Adyen Accounts Kyc Check Context
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
- container: set
  name: requiredFields
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: kycCheckCode
  type: integer
- container: ''
  name: kycCheckDescription
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-kyc-check-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"KYCCheckResult\": \"adyen:KYCCheckResult\",\n    \"KYCCheckStatusData\": \"adyen:KYCCheckStatusData\",\n    \"KYCCheckSummary\": \"adyen:KYCCheckSummary\",\n    \"checks\": {\n      \"@id\": \"adyen:checks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiredFields\": {\n      \"@id\": \"adyen:requiredFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"adyen:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kycCheckCode\": {\n      \"\
  @id\": \"adyen:kycCheckCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"kycCheckDescription\": {\n      \"@id\": \"adyen:kycCheckDescription\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-check-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

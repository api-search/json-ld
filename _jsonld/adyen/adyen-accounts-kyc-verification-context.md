---
class_count: 1
classes:
- KYCVerificationResult
context_file: json-ld/adyen-accounts-kyc-verification-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-verification-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Kyc Verification from Adyen.
layout: jsonld
name: Adyen Accounts Kyc Verification Context
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
  name: accountHolder
  type: string
- container: set
  name: legalArrangements
  type: string
- container: set
  name: legalArrangementsEntities
  type: string
- container: set
  name: payoutMethods
  type: string
- container: set
  name: shareholders
  type: string
- container: set
  name: signatories
  type: string
- container: set
  name: ultimateParentCompany
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-kyc-verification-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"KYCVerificationResult\": \"adyen:KYCVerificationResult\",\n    \"accountHolder\": {\n      \"@id\": \"adyen:accountHolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangements\": {\n      \"@id\": \"adyen:legalArrangements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementsEntities\": {\n      \"@id\": \"adyen:legalArrangementsEntities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutMethods\": {\n      \"@id\": \"adyen:payoutMethods\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholders\": {\n      \"@id\": \"adyen:shareholders\",\n      \"@container\": \"@set\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"signatories\": {\n      \"@id\": \"adyen:signatories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ultimateParentCompany\": {\n      \"@id\": \"adyen:ultimateParentCompany\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-kyc-verification-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

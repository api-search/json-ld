---
class_count: 2
classes:
- SetupBeneficiaryRequest
- SetupBeneficiaryResponse
context_file: json-ld/adyen-funds-setup-beneficiary-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-setup-beneficiary-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Funds Setup Beneficiary from Adyen.
layout: jsonld
name: Adyen Funds Setup Beneficiary Context
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
  name: destinationAccountCode
  type: string
- container: ''
  name: merchantReference
  type: string
- container: ''
  name: sourceAccountCode
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-funds-setup-beneficiary-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SetupBeneficiaryRequest\": \"adyen:SetupBeneficiaryRequest\",\n    \"SetupBeneficiaryResponse\": \"adyen:SetupBeneficiaryResponse\",\n    \"destinationAccountCode\": {\n      \"@id\": \"adyen:destinationAccountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantReference\": {\n      \"@id\": \"adyen:merchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceAccountCode\": {\n      \"@id\": \"adyen:sourceAccountCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-funds-setup-beneficiary-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

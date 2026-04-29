---
class_count: 2
classes:
- CreatePermitRequest
- CreatePermitResult
context_file: json-ld/adyen-recurring-create-permit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-create-permit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Create Permit from Adyen.
layout: jsonld
name: Adyen Recurring Create Permit Context
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
  name: merchantAccount
  type: string
- container: set
  name: permits
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: shopperReference
  type: string
- container: set
  name: permitResultList
  type: string
- container: ''
  name: pspReference
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-create-permit-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreatePermitRequest\": \"adyen:CreatePermitRequest\",\n    \"CreatePermitResult\": \"adyen:CreatePermitResult\",\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permits\": {\n      \"@id\": \"adyen:permits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permitResultList\": {\n      \"@id\": \"adyen:permitResultList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-create-permit-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

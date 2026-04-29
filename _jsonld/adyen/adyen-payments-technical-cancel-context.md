---
class_count: 1
classes:
- TechnicalCancelRequest
context_file: json-ld/adyen-payments-technical-cancel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-technical-cancel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Technical Cancel from Adyen.
layout: jsonld
name: Adyen Payments Technical Cancel Context
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
  name: additionalData
  type: reference
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: modificationAmount
  type: string
- container: ''
  name: mpiData
  type: string
- container: ''
  name: originalMerchantReference
  type: string
- container: ''
  name: platformChargebackLogic
  type: string
- container: ''
  name: reference
  type: string
- container: set
  name: splits
  type: string
- container: ''
  name: tenderReference
  type: string
- container: ''
  name: uniqueTerminalId
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-technical-cancel-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TechnicalCancelRequest\": \"adyen:TechnicalCancelRequest\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modificationAmount\": {\n      \"@id\": \"adyen:modificationAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mpiData\": {\n      \"@id\": \"adyen:mpiData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalMerchantReference\": {\n      \"@id\": \"adyen:originalMerchantReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformChargebackLogic\": {\n      \"@id\": \"adyen:platformChargebackLogic\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"splits\": {\n      \"@id\": \"adyen:splits\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenderReference\": {\n      \"@id\": \"adyen:tenderReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uniqueTerminalId\": {\n      \"@id\": \"adyen:uniqueTerminalId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-technical-cancel-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

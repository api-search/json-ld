---
class_count: 3
classes:
- Merchant
- description
- name
context_file: json-ld/adyen-management-merchant-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-merchant-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Merchant from Adyen.
layout: jsonld
name: Adyen Management Merchant Context
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
  name: Links
  type: string
- container: ''
  name: captureDelay
  type: string
- container: ''
  name: companyId
  type: string
- container: set
  name: dataCenters
  type: string
- container: ''
  name: defaultShopperInteraction
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: merchantCity
  type: string
- container: ''
  name: pricingPlan
  type: string
- container: ''
  name: primarySettlementCurrency
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: shopWebAddress
  type: string
- container: ''
  name: status
  type: string
property_count: 12
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-merchant-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Merchant\": \"adyen:Merchant\",\n    \"Links\": {\n      \"@id\": \"adyen:_links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"captureDelay\": {\n      \"@id\": \"adyen:captureDelay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"companyId\": {\n      \"@id\": \"adyen:companyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataCenters\": {\n      \"@id\": \"adyen:dataCenters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultShopperInteraction\": {\n      \"@id\": \"adyen:defaultShopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  merchantCity\": {\n      \"@id\": \"adyen:merchantCity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"pricingPlan\": {\n      \"@id\": \"adyen:pricingPlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primarySettlementCurrency\": {\n      \"@id\": \"adyen:primarySettlementCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopWebAddress\": {\n      \"@id\": \"adyen:shopWebAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-merchant-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 1
classes:
- CartesBancairesInfo
context_file: json-ld/adyen-management-cartes-bancaires-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-cartes-bancaires-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Cartes Bancaires from Adyen.
layout: jsonld
name: Adyen Management Cartes Bancaires Context
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
  name: siret
  type: string
- container: ''
  name: transactionDescription
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-cartes-bancaires-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CartesBancairesInfo\": \"adyen:CartesBancairesInfo\",\n    \"siret\": {\n      \"@id\": \"adyen:siret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transactionDescription\": {\n      \"@id\": \"adyen:transactionDescription\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-cartes-bancaires-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 1
classes:
- AdditionalCommission
context_file: json-ld/adyen-management-additional-commission-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-additional-commission-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Additional Commission from Adyen.
layout: jsonld
name: Adyen Management Additional Commission Context
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
  name: balanceAccountId
  type: string
- container: ''
  name: fixedAmount
  type: integer
- container: ''
  name: variablePercentage
  type: integer
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-additional-commission-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdditionalCommission\": \"adyen:AdditionalCommission\",\n    \"balanceAccountId\": {\n      \"@id\": \"adyen:balanceAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fixedAmount\": {\n      \"@id\": \"adyen:fixedAmount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"variablePercentage\": {\n      \"@id\": \"adyen:variablePercentage\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-additional-commission-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

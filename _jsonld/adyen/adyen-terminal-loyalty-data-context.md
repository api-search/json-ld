---
class_count: 1
classes:
- LoyaltyData
context_file: json-ld/adyen-terminal-loyalty-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Loyalty Data from Adyen.
layout: jsonld
name: Adyen Terminal Loyalty Data Context
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
  name: CardAcquisitionReference
  type: string
- container: ''
  name: LoyaltyAccountID
  type: string
- container: ''
  name: LoyaltyAmount
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-loyalty-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoyaltyData\": \"adyen:LoyaltyData\",\n    \"CardAcquisitionReference\": {\n      \"@id\": \"adyen:CardAcquisitionReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyAccountID\": {\n      \"@id\": \"adyen:LoyaltyAccountID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyAmount\": {\n      \"@id\": \"adyen:LoyaltyAmount\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 1
classes:
- GrantOffers
context_file: json-ld/adyen-configuration-grant-offers-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-grant-offers-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Grant Offers from Adyen.
layout: jsonld
name: Adyen Configuration Grant Offers Context
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
  name: grantOffers
  type: string
property_count: 1
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-grant-offers-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GrantOffers\": \"adyen:GrantOffers\",\n    \"grantOffers\": {\n      \"@id\": \"adyen:grantOffers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-grant-offers-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

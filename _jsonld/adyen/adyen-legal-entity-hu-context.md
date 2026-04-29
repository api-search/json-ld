---
class_count: 1
classes:
- HULocalAccountIdentification
context_file: json-ld/adyen-legal-entity-hu-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-hu-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Hu from Adyen.
layout: jsonld
name: Adyen Legal Entity Hu Context
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
  name: accountNumber
  type: string
- container: ''
  name: type
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-hu-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"HULocalAccountIdentification\": \"adyen:HULocalAccountIdentification\",\n    \"accountNumber\": {\n      \"@id\": \"adyen:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-hu-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

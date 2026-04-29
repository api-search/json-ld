---
class_count: 1
classes:
- AdminRequest
context_file: json-ld/adyen-terminal-admin-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-admin-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Admin Request from Adyen.
layout: jsonld
name: Adyen Terminal Admin Request Context
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
  name: ServiceIdentification
  type: string
property_count: 1
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-admin-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdminRequest\": \"adyen:AdminRequest\",\n    \"ServiceIdentification\": {\n      \"@id\": \"adyen:ServiceIdentification\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-admin-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

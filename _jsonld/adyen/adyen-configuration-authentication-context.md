---
class_count: 2
classes:
- Authentication
- email
context_file: json-ld/adyen-configuration-authentication-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-authentication-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Authentication from Adyen.
layout: jsonld
name: Adyen Configuration Authentication Context
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
  name: password
  type: string
- container: ''
  name: phone
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-authentication-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Authentication\": \"adyen:Authentication\",\n    \"email\": \"schema:email\",\n    \"password\": {\n      \"@id\": \"adyen:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"adyen:phone\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-authentication-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

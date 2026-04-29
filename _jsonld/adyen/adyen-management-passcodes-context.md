---
class_count: 1
classes:
- Passcodes
context_file: json-ld/adyen-management-passcodes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-passcodes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Passcodes from Adyen.
layout: jsonld
name: Adyen Management Passcodes Context
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
  name: adminMenuPin
  type: string
- container: ''
  name: refundPin
  type: string
- container: ''
  name: screenLockPin
  type: string
- container: ''
  name: txMenuPin
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-passcodes-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Passcodes\": \"adyen:Passcodes\",\n    \"adminMenuPin\": {\n      \"@id\": \"adyen:adminMenuPin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundPin\": {\n      \"@id\": \"adyen:refundPin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"screenLockPin\": {\n      \"@id\": \"adyen:screenLockPin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"txMenuPin\": {\n      \"@id\": \"adyen:txMenuPin\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-passcodes-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

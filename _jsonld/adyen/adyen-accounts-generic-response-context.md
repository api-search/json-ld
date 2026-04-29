---
class_count: 1
classes:
- GenericResponse
context_file: json-ld/adyen-accounts-generic-response-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-generic-response-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Generic Response from Adyen.
layout: jsonld
name: Adyen Accounts Generic Response Context
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
  name: invalidFields
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-generic-response-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GenericResponse\": \"adyen:GenericResponse\",\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-generic-response-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

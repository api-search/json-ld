---
class_count: 2
classes:
- SubjectErasureByPspReferenceRequest
- SubjectErasureResponse
context_file: json-ld/adyen-data-protection-subject-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-data-protection-subject-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Data Protection Subject from Adyen.
layout: jsonld
name: Adyen Data Protection Subject Context
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
  name: forceErasure
  type: boolean
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: result
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-data-protection-subject-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SubjectErasureByPspReferenceRequest\": \"adyen:SubjectErasureByPspReferenceRequest\",\n    \"SubjectErasureResponse\": \"adyen:SubjectErasureResponse\",\n    \"forceErasure\": {\n      \"@id\": \"adyen:forceErasure\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result\": {\n      \"@id\": \"adyen:result\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-data-protection-subject-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

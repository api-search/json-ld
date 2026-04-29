---
class_count: 2
classes:
- GeneratePciDescriptionRequest
- GeneratePciDescriptionResponse
context_file: json-ld/adyen-legal-entity-generate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-generate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Generate from Adyen.
layout: jsonld
name: Adyen Legal Entity Generate Context
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
  name: additionalSalesChannels
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: content
  type: string
- container: set
  name: pciTemplateReferences
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-generate-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GeneratePciDescriptionRequest\": \"adyen:GeneratePciDescriptionRequest\",\n    \"GeneratePciDescriptionResponse\": \"adyen:GeneratePciDescriptionResponse\",\n    \"additionalSalesChannels\": {\n      \"@id\": \"adyen:additionalSalesChannels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"adyen:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"adyen:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pciTemplateReferences\": {\n      \"@id\": \"adyen:pciTemplateReferences\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-generate-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

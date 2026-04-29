---
class_count: 2
classes:
- GetPciQuestionnaireInfosResponse
- GetPciQuestionnaireResponse
context_file: json-ld/adyen-legal-entity-get-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-get-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Get from Adyen.
layout: jsonld
name: Adyen Legal Entity Get Context
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
  name: data
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: validUntil
  type: dateTime
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-get-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetPciQuestionnaireInfosResponse\": \"adyen:GetPciQuestionnaireInfosResponse\",\n    \"GetPciQuestionnaireResponse\": \"adyen:GetPciQuestionnaireResponse\",\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"adyen:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"adyen:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validUntil\": {\n      \"@id\": \"adyen:validUntil\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-get-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

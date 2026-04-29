---
class_count: 1
classes:
- TermsOfServiceAcceptanceInfo
context_file: json-ld/adyen-legal-entity-terms-of-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-terms-of-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Terms Of Service from Adyen.
layout: jsonld
name: Adyen Legal Entity Terms Of Service Context
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
  name: acceptedBy
  type: string
- container: ''
  name: acceptedFor
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-terms-of-service-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TermsOfServiceAcceptanceInfo\": \"adyen:TermsOfServiceAcceptanceInfo\",\n    \"acceptedBy\": {\n      \"@id\": \"adyen:acceptedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"acceptedFor\": {\n      \"@id\": \"adyen:acceptedFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"adyen:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-terms-of-service-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

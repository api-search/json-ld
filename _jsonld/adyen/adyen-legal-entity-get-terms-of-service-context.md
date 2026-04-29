---
class_count: 3
classes:
- GetTermsOfServiceAcceptanceInfosResponse
- GetTermsOfServiceDocumentRequest
- GetTermsOfServiceDocumentResponse
context_file: json-ld/adyen-legal-entity-get-terms-of-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-get-terms-of-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Get Terms Of Service from Adyen.
layout: jsonld
name: Adyen Legal Entity Get Terms Of Service Context
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
  name: language
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: document
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: termsOfServiceDocumentId
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-get-terms-of-service-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetTermsOfServiceAcceptanceInfosResponse\": \"adyen:GetTermsOfServiceAcceptanceInfosResponse\",\n    \"GetTermsOfServiceDocumentRequest\": \"adyen:GetTermsOfServiceDocumentRequest\",\n    \"GetTermsOfServiceDocumentResponse\": \"adyen:GetTermsOfServiceDocumentResponse\",\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"adyen:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"document\": {\n      \"@id\": \"adyen:document\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"termsOfServiceDocumentId\": {\n      \"@id\": \"adyen:termsOfServiceDocumentId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-get-terms-of-service-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

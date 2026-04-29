---
class_count: 2
classes:
- EnableServiceRequest
- EnableServiceResponse
context_file: json-ld/adyen-terminal-enable-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-enable-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Enable Service from Adyen.
layout: jsonld
name: Adyen Terminal Enable Service Context
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
  name: TransactionAction
  type: string
- container: ''
  name: ServicesEnabled
  type: string
- container: ''
  name: DisplayOutput
  type: string
- container: ''
  name: Response
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-enable-service-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EnableServiceRequest\": \"adyen:EnableServiceRequest\",\n    \"EnableServiceResponse\": \"adyen:EnableServiceResponse\",\n    \"TransactionAction\": {\n      \"@id\": \"adyen:TransactionAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServicesEnabled\": {\n      \"@id\": \"adyen:ServicesEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayOutput\": {\n      \"@id\": \"adyen:DisplayOutput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Response\": {\n      \"@id\": \"adyen:Response\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-enable-service-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

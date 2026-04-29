---
class_count: 1
classes:
- ListTerminalsResponse
context_file: json-ld/adyen-management-list-terminals-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-list-terminals-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management List Terminals from Adyen.
layout: jsonld
name: Adyen Management List Terminals Context
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
  name: Links
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: itemsTotal
  type: integer
- container: ''
  name: pagesTotal
  type: integer
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-list-terminals-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ListTerminalsResponse\": \"adyen:ListTerminalsResponse\",\n    \"Links\": {\n      \"@id\": \"adyen:_links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemsTotal\": {\n      \"@id\": \"adyen:itemsTotal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pagesTotal\": {\n      \"@id\": \"adyen:pagesTotal\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-list-terminals-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

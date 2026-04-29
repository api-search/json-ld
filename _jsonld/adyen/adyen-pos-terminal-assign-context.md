---
class_count: 2
classes:
- AssignTerminalsRequest
- AssignTerminalsResponse
context_file: json-ld/adyen-pos-terminal-assign-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-pos-terminal-assign-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Pos Terminal Assign from Adyen.
layout: jsonld
name: Adyen Pos Terminal Assign Context
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
  name: companyAccount
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: merchantInventory
  type: boolean
- container: ''
  name: store
  type: string
- container: set
  name: terminals
  type: string
- container: ''
  name: results
  type: reference
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-pos-terminal-assign-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssignTerminalsRequest\": \"adyen:AssignTerminalsRequest\",\n    \"AssignTerminalsResponse\": \"adyen:AssignTerminalsResponse\",\n    \"companyAccount\": {\n      \"@id\": \"adyen:companyAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantInventory\": {\n      \"@id\": \"adyen:merchantInventory\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"store\": {\n      \"@id\": \"adyen:store\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminals\": {\n      \"@id\": \"adyen:terminals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"adyen:results\"\
  ,\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-pos-terminal-assign-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 1
classes:
- LoginResponse
context_file: json-ld/adyen-terminal-login-response-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-login-response-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Login Response from Adyen.
layout: jsonld
name: Adyen Terminal Login Response Context
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
  name: Response
  type: string
- container: ''
  name: POISystemData
  type: string
- container: ''
  name: TokenRequestStatus
  type: boolean
- container: ''
  name: CustomerOrderStatus
  type: boolean
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-login-response-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoginResponse\": \"adyen:LoginResponse\",\n    \"Response\": {\n      \"@id\": \"adyen:Response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POISystemData\": {\n      \"@id\": \"adyen:POISystemData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TokenRequestStatus\": {\n      \"@id\": \"adyen:TokenRequestStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CustomerOrderStatus\": {\n      \"@id\": \"adyen:CustomerOrderStatus\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-login-response-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 1
classes:
- Card
context_file: json-ld/adyen-payouts-card-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-card-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payouts Card from Adyen.
layout: jsonld
name: Adyen Payouts Card Context
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
  name: cvc
  type: string
- container: ''
  name: expiryMonth
  type: string
- container: ''
  name: expiryYear
  type: string
- container: ''
  name: holderName
  type: string
- container: ''
  name: issueNumber
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: startMonth
  type: string
- container: ''
  name: startYear
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-payouts-card-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Card\": \"adyen:Card\",\n    \"cvc\": {\n      \"@id\": \"adyen:cvc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryMonth\": {\n      \"@id\": \"adyen:expiryMonth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryYear\": {\n      \"@id\": \"adyen:expiryYear\",\n      \"@type\": \"xsd:string\"\n    },\n    \"holderName\": {\n      \"@id\": \"adyen:holderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issueNumber\": {\n      \"@id\": \"adyen:issueNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"adyen:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startMonth\": {\n      \"@id\": \"adyen:startMonth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startYear\":\
  \ {\n      \"@id\": \"adyen:startYear\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-card-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

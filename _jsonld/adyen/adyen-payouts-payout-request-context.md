---
class_count: 1
classes:
- PayoutRequest
context_file: json-ld/adyen-payouts-payout-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-payout-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payouts Payout Request from Adyen.
layout: jsonld
name: Adyen Payouts Payout Request Context
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
  name: amount
  type: string
- container: ''
  name: billingAddress
  type: string
- container: ''
  name: card
  type: string
- container: ''
  name: fraudOffset
  type: integer
- container: ''
  name: fundSource
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: recurring
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: selectedRecurringDetailReference
  type: string
- container: ''
  name: shopperEmail
  type: string
- container: ''
  name: shopperInteraction
  type: string
- container: ''
  name: shopperName
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: telephoneNumber
  type: string
property_count: 14
provider_name: Adyen
provider_slug: adyen
slug: adyen-payouts-payout-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PayoutRequest\": \"adyen:PayoutRequest\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"card\": {\n      \"@id\": \"adyen:card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fraudOffset\": {\n      \"@id\": \"adyen:fraudOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fundSource\": {\n      \"@id\": \"adyen:fundSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurring\": {\n      \"@id\": \"adyen:recurring\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedRecurringDetailReference\": {\n      \"@id\": \"adyen:selectedRecurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"telephoneNumber\": {\n      \"@id\": \"adyen:telephoneNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-payout-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

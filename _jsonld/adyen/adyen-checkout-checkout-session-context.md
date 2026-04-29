---
class_count: 1
classes:
- CheckoutSessionInstallmentOption
context_file: json-ld/adyen-checkout-checkout-session-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-checkout-session-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Checkout Session from Adyen.
layout: jsonld
name: Adyen Checkout Checkout Session Context
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
  name: plans
  type: string
- container: ''
  name: preselectedValue
  type: integer
- container: set
  name: values
  type: integer
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-checkout-session-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CheckoutSessionInstallmentOption\": \"adyen:CheckoutSessionInstallmentOption\",\n    \"plans\": {\n      \"@id\": \"adyen:plans\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preselectedValue\": {\n      \"@id\": \"adyen:preselectedValue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"values\": {\n      \"@id\": \"adyen:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-checkout-session-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

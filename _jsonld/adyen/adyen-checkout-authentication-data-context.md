---
class_count: 1
classes:
- AuthenticationData
context_file: json-ld/adyen-checkout-authentication-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-authentication-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Authentication Data from Adyen.
layout: jsonld
name: Adyen Checkout Authentication Data Context
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
  name: attemptAuthentication
  type: string
- container: ''
  name: authenticationOnly
  type: boolean
- container: ''
  name: threeDSRequestData
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-authentication-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuthenticationData\": \"adyen:AuthenticationData\",\n    \"attemptAuthentication\": {\n      \"@id\": \"adyen:attemptAuthentication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authenticationOnly\": {\n      \"@id\": \"adyen:authenticationOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"threeDSRequestData\": {\n      \"@id\": \"adyen:threeDSRequestData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-authentication-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 1
classes:
- TestOutput
context_file: json-ld/adyen-management-test-output-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-test-output-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Test Output from Adyen.
layout: jsonld
name: Adyen Management Test Output Context
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
  name: merchantId
  type: string
- container: ''
  name: output
  type: string
- container: ''
  name: requestSent
  type: string
- container: ''
  name: responseCode
  type: string
- container: ''
  name: responseTime
  type: string
- container: ''
  name: status
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-test-output-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TestOutput\": \"adyen:TestOutput\",\n    \"merchantId\": {\n      \"@id\": \"adyen:merchantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"output\": {\n      \"@id\": \"adyen:output\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestSent\": {\n      \"@id\": \"adyen:requestSent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseCode\": {\n      \"@id\": \"adyen:responseCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseTime\": {\n      \"@id\": \"adyen:responseTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-test-output-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

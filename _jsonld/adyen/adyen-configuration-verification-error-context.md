---
class_count: 2
classes:
- VerificationError-recursive
- VerificationError
context_file: json-ld/adyen-configuration-verification-error-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-verification-error-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Verification Error from Adyen.
layout: jsonld
name: Adyen Configuration Verification Error Context
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
  name: capabilities
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: remediatingActions
  type: string
- container: set
  name: subErrors
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-verification-error-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"VerificationError-recursive\": \"adyen:VerificationError-recursive\",\n    \"VerificationError\": \"adyen:VerificationError\",\n    \"capabilities\": {\n      \"@id\": \"adyen:capabilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"adyen:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"adyen:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediatingActions\": {\n      \"@id\": \"adyen:remediatingActions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subErrors\": {\n      \"@id\": \"adyen:subErrors\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-verification-error-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

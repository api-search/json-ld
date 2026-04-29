---
class_count: 1
classes:
- IssuedCard
context_file: json-ld/adyen-transfers-issued-card-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-issued-card-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Issued Card from Adyen.
layout: jsonld
name: Adyen Transfers Issued Card Context
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
  name: authorisationType
  type: string
- container: ''
  name: panEntryMode
  type: string
- container: ''
  name: processingType
  type: string
- container: ''
  name: relayedAuthorisationData
  type: string
- container: ''
  name: schemeTraceId
  type: string
- container: ''
  name: schemeUniqueTransactionId
  type: string
- container: ''
  name: type
  type: string
- container: set
  name: validationFacts
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-issued-card-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"IssuedCard\": \"adyen:IssuedCard\",\n    \"authorisationType\": {\n      \"@id\": \"adyen:authorisationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"panEntryMode\": {\n      \"@id\": \"adyen:panEntryMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingType\": {\n      \"@id\": \"adyen:processingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relayedAuthorisationData\": {\n      \"@id\": \"adyen:relayedAuthorisationData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemeTraceId\": {\n      \"@id\": \"adyen:schemeTraceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemeUniqueTransactionId\": {\n      \"@id\": \"adyen:schemeUniqueTransactionId\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validationFacts\": {\n      \"@id\": \"adyen:validationFacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-issued-card-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

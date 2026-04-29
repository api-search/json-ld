---
class_count: 2
classes:
- SweepConfigurationV2
- description
context_file: json-ld/adyen-configuration-sweep-configuration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-sweep-configuration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Sweep Configuration from Adyen.
layout: jsonld
name: Adyen Configuration Sweep Configuration Context
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
  name: category
  type: string
- container: ''
  name: counterparty
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: priorities
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: schedule
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: sweepAmount
  type: string
- container: ''
  name: targetAmount
  type: string
- container: ''
  name: triggerAmount
  type: string
- container: ''
  name: type
  type: string
property_count: 12
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-sweep-configuration-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SweepConfigurationV2\": \"adyen:SweepConfigurationV2\",\n    \"category\": {\n      \"@id\": \"adyen:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterparty\": {\n      \"@id\": \"adyen:counterparty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priorities\": {\n      \"@id\": \"adyen:priorities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"adyen:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n\
  \      \"@id\": \"adyen:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sweepAmount\": {\n      \"@id\": \"adyen:sweepAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetAmount\": {\n      \"@id\": \"adyen:targetAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerAmount\": {\n      \"@id\": \"adyen:triggerAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-sweep-configuration-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

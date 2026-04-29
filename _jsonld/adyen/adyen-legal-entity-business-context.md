---
class_count: 4
classes:
- BusinessLineInfo
- BusinessLineInfoUpdate
- BusinessLine
- BusinessLines
context_file: json-ld/adyen-legal-entity-business-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-business-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Business from Adyen.
layout: jsonld
name: Adyen Legal Entity Business Context
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
  name: capability
  type: string
- container: ''
  name: industryCode
  type: string
- container: ''
  name: legalEntityId
  type: string
- container: set
  name: salesChannels
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: sourceOfFunds
  type: string
- container: set
  name: webData
  type: string
- container: ''
  name: webDataExemption
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: problems
  type: string
- container: set
  name: businessLines
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-business-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BusinessLineInfo\": \"adyen:BusinessLineInfo\",\n    \"BusinessLineInfoUpdate\": \"adyen:BusinessLineInfoUpdate\",\n    \"BusinessLine\": \"adyen:BusinessLine\",\n    \"BusinessLines\": \"adyen:BusinessLines\",\n    \"capability\": {\n      \"@id\": \"adyen:capability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"industryCode\": {\n      \"@id\": \"adyen:industryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalEntityId\": {\n      \"@id\": \"adyen:legalEntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salesChannels\": {\n      \"@id\": \"adyen:salesChannels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"adyen:service\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"sourceOfFunds\": {\n      \"@id\": \"adyen:sourceOfFunds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webData\": {\n      \"@id\": \"adyen:webData\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webDataExemption\": {\n      \"@id\": \"adyen:webDataExemption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"problems\": {\n      \"@id\": \"adyen:problems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessLines\": {\n      \"@id\": \"adyen:businessLines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-business-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

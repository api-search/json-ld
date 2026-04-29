---
class_count: 4
classes:
- CapabilityProblemEntity-recursive
- CapabilityProblemEntity
- CapabilityProblem
- CapabilitySettings
context_file: json-ld/adyen-legal-entity-capability-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-capability-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Capability from Adyen.
layout: jsonld
name: Adyen Legal Entity Capability Context
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
  name: documents
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: entity
  type: string
- container: set
  name: verificationErrors
  type: string
- container: ''
  name: amountPerIndustry
  type: reference
- container: ''
  name: authorizedCardUsers
  type: boolean
- container: set
  name: fundingSource
  type: string
- container: ''
  name: interval
  type: string
- container: ''
  name: maxAmount
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-capability-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CapabilityProblemEntity-recursive\": \"adyen:CapabilityProblemEntity-recursive\",\n    \"CapabilityProblemEntity\": \"adyen:CapabilityProblemEntity\",\n    \"CapabilityProblem\": \"adyen:CapabilityProblem\",\n    \"CapabilitySettings\": \"adyen:CapabilitySettings\",\n    \"documents\": {\n      \"@id\": \"adyen:documents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"adyen:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entity\": {\n      \"@id\": \"adyen:entity\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"verificationErrors\": {\n      \"@id\": \"adyen:verificationErrors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amountPerIndustry\": {\n      \"@id\": \"adyen:amountPerIndustry\",\n      \"@type\": \"@id\"\n    },\n    \"authorizedCardUsers\": {\n      \"@id\": \"adyen:authorizedCardUsers\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interval\": {\n      \"@id\": \"adyen:interval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAmount\": {\n      \"@id\": \"adyen:maxAmount\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-capability-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

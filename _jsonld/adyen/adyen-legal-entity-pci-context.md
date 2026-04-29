---
class_count: 3
classes:
- PciDocumentInfo
- PciSigningRequest
- PciSigningResponse
context_file: json-ld/adyen-legal-entity-pci-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-pci-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Pci from Adyen.
layout: jsonld
name: Adyen Legal Entity Pci Context
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
  name: createdAt
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: validUntil
  type: dateTime
- container: set
  name: pciTemplateReferences
  type: string
- container: ''
  name: signedBy
  type: string
- container: set
  name: pciQuestionnaireIds
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-pci-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PciDocumentInfo\": \"adyen:PciDocumentInfo\",\n    \"PciSigningRequest\": \"adyen:PciSigningRequest\",\n    \"PciSigningResponse\": \"adyen:PciSigningResponse\",\n    \"createdAt\": {\n      \"@id\": \"adyen:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validUntil\": {\n      \"@id\": \"adyen:validUntil\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"pciTemplateReferences\": {\n      \"@id\": \"adyen:pciTemplateReferences\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedBy\": {\n      \"@id\": \"adyen:signedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pciQuestionnaireIds\": {\n\
  \      \"@id\": \"adyen:pciQuestionnaireIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-pci-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

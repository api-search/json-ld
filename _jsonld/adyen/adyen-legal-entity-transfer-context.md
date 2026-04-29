---
class_count: 3
classes:
- TransferInstrumentInfo
- TransferInstrumentReference
- TransferInstrument
context_file: json-ld/adyen-legal-entity-transfer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-transfer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Transfer from Adyen.
layout: jsonld
name: Adyen Legal Entity Transfer Context
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
  name: bankAccount
  type: string
- container: ''
  name: legalEntityId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: accountIdentifier
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: realLastFour
  type: string
- container: ''
  name: trustedSource
  type: boolean
- container: ''
  name: capabilities
  type: reference
- container: set
  name: documentDetails
  type: string
- container: set
  name: problems
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-transfer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TransferInstrumentInfo\": \"adyen:TransferInstrumentInfo\",\n    \"TransferInstrumentReference\": \"adyen:TransferInstrumentReference\",\n    \"TransferInstrument\": \"adyen:TransferInstrument\",\n    \"bankAccount\": {\n      \"@id\": \"adyen:bankAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalEntityId\": {\n      \"@id\": \"adyen:legalEntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountIdentifier\": {\n      \"@id\": \"adyen:accountIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realLastFour\": {\n      \"@id\"\
  : \"adyen:realLastFour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trustedSource\": {\n      \"@id\": \"adyen:trustedSource\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"capabilities\": {\n      \"@id\": \"adyen:capabilities\",\n      \"@type\": \"@id\"\n    },\n    \"documentDetails\": {\n      \"@id\": \"adyen:documentDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"problems\": {\n      \"@id\": \"adyen:problems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-transfer-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

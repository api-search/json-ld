---
class_count: 1
classes:
- SaleData
context_file: json-ld/adyen-terminal-sale-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-sale-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Sale Data from Adyen.
layout: jsonld
name: Adyen Terminal Sale Data Context
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
  name: OperatorID
  type: string
- container: ''
  name: OperatorLanguage
  type: string
- container: ''
  name: ShiftNumber
  type: string
- container: ''
  name: SaleTransactionID
  type: string
- container: ''
  name: SaleReferenceID
  type: string
- container: ''
  name: SaleTerminalData
  type: string
- container: ''
  name: TokenRequestedType
  type: string
- container: ''
  name: CustomerOrderID
  type: string
- container: ''
  name: CustomerOrderReq
  type: string
- container: ''
  name: SaleToPOIData
  type: string
- container: ''
  name: SaleToAcquirerData
  type: string
- container: ''
  name: SaleToIssuerData
  type: string
property_count: 12
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-sale-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SaleData\": \"adyen:SaleData\",\n    \"OperatorID\": {\n      \"@id\": \"adyen:OperatorID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OperatorLanguage\": {\n      \"@id\": \"adyen:OperatorLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShiftNumber\": {\n      \"@id\": \"adyen:ShiftNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleTransactionID\": {\n      \"@id\": \"adyen:SaleTransactionID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleReferenceID\": {\n      \"@id\": \"adyen:SaleReferenceID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleTerminalData\": {\n      \"@id\": \"adyen:SaleTerminalData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TokenRequestedType\": {\n      \"@id\"\
  : \"adyen:TokenRequestedType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerOrderID\": {\n      \"@id\": \"adyen:CustomerOrderID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerOrderReq\": {\n      \"@id\": \"adyen:CustomerOrderReq\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleToPOIData\": {\n      \"@id\": \"adyen:SaleToPOIData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleToAcquirerData\": {\n      \"@id\": \"adyen:SaleToAcquirerData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleToIssuerData\": {\n      \"@id\": \"adyen:SaleToIssuerData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-sale-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

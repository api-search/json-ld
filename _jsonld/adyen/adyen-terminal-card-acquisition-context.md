---
class_count: 3
classes:
- CardAcquisitionRequest
- CardAcquisitionResponse
- CardAcquisitionTransaction
context_file: json-ld/adyen-terminal-card-acquisition-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-card-acquisition-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Card Acquisition from Adyen.
layout: jsonld
name: Adyen Terminal Card Acquisition Context
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
  name: SaleData
  type: string
- container: ''
  name: Response
  type: string
- container: ''
  name: POIData
  type: string
- container: ''
  name: CustomerLanguage
  type: string
- container: set
  name: PaymentBrand
  type: string
- container: ''
  name: PaymentInstrumentData
  type: string
- container: set
  name: LoyaltyAccount
  type: string
- container: set
  name: AllowedPaymentBrand
  type: string
- container: set
  name: AllowedLoyaltyBrand
  type: string
- container: ''
  name: LoyaltyHandling
  type: string
- container: ''
  name: ForceEntryMode
  type: string
- container: ''
  name: ForceCustomerSelectionFlag
  type: boolean
- container: ''
  name: TotalAmount
  type: decimal
- container: ''
  name: PaymentType
  type: string
- container: ''
  name: CashBackFlag
  type: boolean
property_count: 15
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-card-acquisition-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CardAcquisitionRequest\": \"adyen:CardAcquisitionRequest\",\n    \"CardAcquisitionResponse\": \"adyen:CardAcquisitionResponse\",\n    \"CardAcquisitionTransaction\": \"adyen:CardAcquisitionTransaction\",\n    \"SaleData\": {\n      \"@id\": \"adyen:SaleData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Response\": {\n      \"@id\": \"adyen:Response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POIData\": {\n      \"@id\": \"adyen:POIData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerLanguage\": {\n      \"@id\": \"adyen:CustomerLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentBrand\": {\n      \"@id\": \"adyen:PaymentBrand\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"PaymentInstrumentData\": {\n      \"@id\": \"adyen:PaymentInstrumentData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyAccount\": {\n      \"@id\": \"adyen:LoyaltyAccount\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowedPaymentBrand\": {\n      \"@id\": \"adyen:AllowedPaymentBrand\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowedLoyaltyBrand\": {\n      \"@id\": \"adyen:AllowedLoyaltyBrand\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyHandling\": {\n      \"@id\": \"adyen:LoyaltyHandling\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForceEntryMode\": {\n      \"@id\": \"adyen:ForceEntryMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForceCustomerSelectionFlag\": {\n      \"@id\": \"adyen:ForceCustomerSelectionFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"TotalAmount\": {\n      \"@id\": \"adyen:TotalAmount\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"PaymentType\": {\n      \"@id\": \"adyen:PaymentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CashBackFlag\": {\n      \"@id\": \"adyen:CashBackFlag\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-card-acquisition-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

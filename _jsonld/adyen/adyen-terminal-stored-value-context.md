---
class_count: 8
classes:
- StoredValueAccountID
- StoredValueAccountStatus
- StoredValueAccountType
- StoredValueData
- StoredValueRequest
- StoredValueResponse
- StoredValueResult
- StoredValueTransactionType
context_file: json-ld/adyen-terminal-stored-value-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-stored-value-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Stored Value from Adyen.
layout: jsonld
name: Adyen Terminal Stored Value Context
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
  name: StoredValueProvider
  type: string
- container: ''
  name: OwnerName
  type: string
- container: ''
  name: ExpiryDate
  type: integer
- container: ''
  name: EntryMode
  type: string
- container: ''
  name: IdentificationType
  type: string
- container: ''
  name: StoredValueID
  type: string
- container: ''
  name: CurrentBalance
  type: decimal
- container: ''
  name: OriginalPOITransaction
  type: string
- container: ''
  name: ProductCode
  type: integer
- container: ''
  name: EanUpc
  type: integer
- container: ''
  name: ItemAmount
  type: decimal
- container: ''
  name: Currency
  type: string
- container: ''
  name: SaleData
  type: string
- container: ''
  name: CustomerLanguage
  type: string
- container: ''
  name: Response
  type: string
- container: ''
  name: POIData
  type: string
- container: set
  name: PaymentReceipt
  type: string
- container: ''
  name: HostTransactionID
  type: string
property_count: 18
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-stored-value-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StoredValueAccountID\": \"adyen:StoredValueAccountID\",\n    \"StoredValueAccountStatus\": \"adyen:StoredValueAccountStatus\",\n    \"StoredValueAccountType\": \"adyen:StoredValueAccountType\",\n    \"StoredValueData\": \"adyen:StoredValueData\",\n    \"StoredValueRequest\": \"adyen:StoredValueRequest\",\n    \"StoredValueResponse\": \"adyen:StoredValueResponse\",\n    \"StoredValueResult\": \"adyen:StoredValueResult\",\n    \"StoredValueTransactionType\": \"adyen:StoredValueTransactionType\",\n    \"StoredValueProvider\": {\n      \"@id\": \"adyen:StoredValueProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerName\": {\n      \"@id\": \"adyen:OwnerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpiryDate\":\
  \ {\n      \"@id\": \"adyen:ExpiryDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"EntryMode\": {\n      \"@id\": \"adyen:EntryMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentificationType\": {\n      \"@id\": \"adyen:IdentificationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StoredValueID\": {\n      \"@id\": \"adyen:StoredValueID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentBalance\": {\n      \"@id\": \"adyen:CurrentBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"OriginalPOITransaction\": {\n      \"@id\": \"adyen:OriginalPOITransaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductCode\": {\n      \"@id\": \"adyen:ProductCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"EanUpc\": {\n      \"@id\": \"adyen:EanUpc\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ItemAmount\": {\n      \"@id\": \"adyen:ItemAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Currency\": {\n      \"@id\": \"adyen:Currency\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleData\": {\n      \"@id\": \"adyen:SaleData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerLanguage\": {\n      \"@id\": \"adyen:CustomerLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Response\": {\n      \"@id\": \"adyen:Response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POIData\": {\n      \"@id\": \"adyen:POIData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentReceipt\": {\n      \"@id\": \"adyen:PaymentReceipt\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HostTransactionID\": {\n      \"@id\": \"adyen:HostTransactionID\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-stored-value-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

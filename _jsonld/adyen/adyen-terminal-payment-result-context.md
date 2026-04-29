---
class_count: 1
classes:
- PaymentResult
context_file: json-ld/adyen-terminal-payment-result-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-payment-result-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Payment Result from Adyen.
layout: jsonld
name: Adyen Terminal Payment Result Context
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
  name: PaymentType
  type: string
- container: ''
  name: PaymentInstrumentData
  type: string
- container: ''
  name: AmountsResp
  type: string
- container: ''
  name: Instalment
  type: string
- container: set
  name: CurrencyConversion
  type: string
- container: ''
  name: MerchantOverrideFlag
  type: boolean
- container: ''
  name: CapturedSignature
  type: string
- container: ''
  name: ProtectedSignature
  type: string
- container: ''
  name: CustomerLanguage
  type: string
- container: ''
  name: OnlineFlag
  type: boolean
- container: ''
  name: AuthenticationMethod
  type: string
- container: ''
  name: ValidityDate
  type: date
- container: ''
  name: PaymentAcquirerData
  type: string
property_count: 13
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-payment-result-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentResult\": \"adyen:PaymentResult\",\n    \"PaymentType\": {\n      \"@id\": \"adyen:PaymentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentInstrumentData\": {\n      \"@id\": \"adyen:PaymentInstrumentData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AmountsResp\": {\n      \"@id\": \"adyen:AmountsResp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Instalment\": {\n      \"@id\": \"adyen:Instalment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrencyConversion\": {\n      \"@id\": \"adyen:CurrencyConversion\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MerchantOverrideFlag\": {\n      \"@id\": \"adyen:MerchantOverrideFlag\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"CapturedSignature\": {\n      \"@id\": \"adyen:CapturedSignature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProtectedSignature\": {\n      \"@id\": \"adyen:ProtectedSignature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerLanguage\": {\n      \"@id\": \"adyen:CustomerLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OnlineFlag\": {\n      \"@id\": \"adyen:OnlineFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"AuthenticationMethod\": {\n      \"@id\": \"adyen:AuthenticationMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidityDate\": {\n      \"@id\": \"adyen:ValidityDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"PaymentAcquirerData\": {\n      \"@id\": \"adyen:PaymentAcquirerData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-payment-result-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

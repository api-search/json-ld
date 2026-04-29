---
class_count: 1
classes:
- AcctInfo
context_file: json-ld/adyen-checkout-acct-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-acct-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Acct Info from Adyen.
layout: jsonld
name: Adyen Checkout Acct Info Context
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
  name: chAccAgeInd
  type: string
- container: ''
  name: chAccChange
  type: string
- container: ''
  name: chAccChangeInd
  type: string
- container: ''
  name: chAccPwChange
  type: string
- container: ''
  name: chAccPwChangeInd
  type: string
- container: ''
  name: chAccString
  type: string
- container: ''
  name: nbPurchaseAccount
  type: string
- container: ''
  name: paymentAccAge
  type: string
- container: ''
  name: paymentAccInd
  type: string
- container: ''
  name: provisionAttemptsDay
  type: string
- container: ''
  name: shipAddressUsage
  type: string
- container: ''
  name: shipAddressUsageInd
  type: string
- container: ''
  name: shipNameIndicator
  type: string
- container: ''
  name: suspiciousAccActivity
  type: string
- container: ''
  name: txnActivityDay
  type: string
- container: ''
  name: txnActivityYear
  type: string
property_count: 16
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-acct-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AcctInfo\": \"adyen:AcctInfo\",\n    \"chAccAgeInd\": {\n      \"@id\": \"adyen:chAccAgeInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chAccChange\": {\n      \"@id\": \"adyen:chAccChange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chAccChangeInd\": {\n      \"@id\": \"adyen:chAccChangeInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chAccPwChange\": {\n      \"@id\": \"adyen:chAccPwChange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chAccPwChangeInd\": {\n      \"@id\": \"adyen:chAccPwChangeInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chAccString\": {\n      \"@id\": \"adyen:chAccString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nbPurchaseAccount\": {\n      \"@id\": \"adyen:nbPurchaseAccount\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentAccAge\": {\n      \"@id\": \"adyen:paymentAccAge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentAccInd\": {\n      \"@id\": \"adyen:paymentAccInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisionAttemptsDay\": {\n      \"@id\": \"adyen:provisionAttemptsDay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipAddressUsage\": {\n      \"@id\": \"adyen:shipAddressUsage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipAddressUsageInd\": {\n      \"@id\": \"adyen:shipAddressUsageInd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipNameIndicator\": {\n      \"@id\": \"adyen:shipNameIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suspiciousAccActivity\": {\n      \"@id\": \"adyen:suspiciousAccActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"txnActivityDay\": {\n      \"@id\": \"adyen:txnActivityDay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"txnActivityYear\": {\n     \
  \ \"@id\": \"adyen:txnActivityYear\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-acct-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

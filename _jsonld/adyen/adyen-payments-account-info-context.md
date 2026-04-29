---
class_count: 1
classes:
- AccountInfo
context_file: json-ld/adyen-payments-account-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-account-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Account Info from Adyen.
layout: jsonld
name: Adyen Payments Account Info Context
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
  name: accountAgeIndicator
  type: string
- container: ''
  name: accountChangeDate
  type: dateTime
- container: ''
  name: accountChangeIndicator
  type: string
- container: ''
  name: accountCreationDate
  type: dateTime
- container: ''
  name: accountType
  type: string
- container: ''
  name: addCardAttemptsDay
  type: integer
- container: ''
  name: deliveryAddressUsageDate
  type: dateTime
- container: ''
  name: deliveryAddressUsageIndicator
  type: string
- container: ''
  name: homePhone
  type: string
- container: ''
  name: mobilePhone
  type: string
- container: ''
  name: passwordChangeDate
  type: dateTime
- container: ''
  name: passwordChangeIndicator
  type: string
- container: ''
  name: pastTransactionsDay
  type: integer
- container: ''
  name: pastTransactionsYear
  type: integer
- container: ''
  name: paymentAccountAge
  type: dateTime
- container: ''
  name: paymentAccountIndicator
  type: string
- container: ''
  name: purchasesLast6Months
  type: integer
- container: ''
  name: suspiciousActivity
  type: boolean
- container: ''
  name: workPhone
  type: string
property_count: 19
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-account-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountInfo\": \"adyen:AccountInfo\",\n    \"accountAgeIndicator\": {\n      \"@id\": \"adyen:accountAgeIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountChangeDate\": {\n      \"@id\": \"adyen:accountChangeDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"accountChangeIndicator\": {\n      \"@id\": \"adyen:accountChangeIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountCreationDate\": {\n      \"@id\": \"adyen:accountCreationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"accountType\": {\n      \"@id\": \"adyen:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addCardAttemptsDay\": {\n      \"@id\": \"adyen:addCardAttemptsDay\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"deliveryAddressUsageDate\": {\n      \"@id\": \"adyen:deliveryAddressUsageDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveryAddressUsageIndicator\": {\n      \"@id\": \"adyen:deliveryAddressUsageIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"homePhone\": {\n      \"@id\": \"adyen:homePhone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mobilePhone\": {\n      \"@id\": \"adyen:mobilePhone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passwordChangeDate\": {\n      \"@id\": \"adyen:passwordChangeDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"passwordChangeIndicator\": {\n      \"@id\": \"adyen:passwordChangeIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pastTransactionsDay\": {\n      \"@id\": \"adyen:pastTransactionsDay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pastTransactionsYear\": {\n      \"@id\": \"adyen:pastTransactionsYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"paymentAccountAge\"\
  : {\n      \"@id\": \"adyen:paymentAccountAge\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"paymentAccountIndicator\": {\n      \"@id\": \"adyen:paymentAccountIndicator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchasesLast6Months\": {\n      \"@id\": \"adyen:purchasesLast6Months\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"suspiciousActivity\": {\n      \"@id\": \"adyen:suspiciousActivity\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"workPhone\": {\n      \"@id\": \"adyen:workPhone\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-account-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

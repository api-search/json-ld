---
class_count: 3
classes:
- RecurringDetail
- RecurringDetailWrapper
- name
context_file: json-ld/adyen-recurring-recurring-detail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-recurring-detail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Recurring Detail from Adyen.
layout: jsonld
name: Adyen Recurring Recurring Detail Context
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
  name: additionalData
  type: reference
- container: ''
  name: alias
  type: string
- container: ''
  name: aliasType
  type: string
- container: ''
  name: bank
  type: string
- container: ''
  name: billingAddress
  type: string
- container: ''
  name: card
  type: string
- container: set
  name: contractTypes
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: firstPspReference
  type: string
- container: ''
  name: networkTxReference
  type: string
- container: ''
  name: paymentMethodVariant
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: shopperName
  type: string
- container: ''
  name: socialSecurityNumber
  type: string
- container: ''
  name: tokenDetails
  type: string
- container: ''
  name: variant
  type: string
property_count: 16
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-recurring-detail-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RecurringDetail\": \"adyen:RecurringDetail\",\n    \"RecurringDetailWrapper\": \"adyen:RecurringDetailWrapper\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"alias\": {\n      \"@id\": \"adyen:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aliasType\": {\n      \"@id\": \"adyen:aliasType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bank\": {\n      \"@id\": \"adyen:bank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"card\": {\n      \"@id\": \"adyen:card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contractTypes\": {\n      \"@id\":\
  \ \"adyen:contractTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"firstPspReference\": {\n      \"@id\": \"adyen:firstPspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"networkTxReference\": {\n      \"@id\": \"adyen:networkTxReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethodVariant\": {\n      \"@id\": \"adyen:paymentMethodVariant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"socialSecurityNumber\": {\n      \"@id\": \"adyen:socialSecurityNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenDetails\": {\n      \"@id\": \"adyen:tokenDetails\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"variant\": {\n      \"@id\": \"adyen:variant\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-recurring-detail-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

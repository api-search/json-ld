---
class_count: 1
classes:
- TerminalSettings
context_file: json-ld/adyen-management-terminal-settings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-settings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Terminal Settings from Adyen.
layout: jsonld
name: Adyen Management Terminal Settings Context
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
  name: cardholderReceipt
  type: string
- container: ''
  name: connectivity
  type: string
- container: set
  name: gratuities
  type: string
- container: ''
  name: hardware
  type: string
- container: ''
  name: localization
  type: string
- container: ''
  name: nexo
  type: string
- container: ''
  name: offlineProcessing
  type: string
- container: ''
  name: opi
  type: string
- container: ''
  name: passcodes
  type: string
- container: ''
  name: payAtTable
  type: string
- container: ''
  name: payment
  type: string
- container: ''
  name: receiptOptions
  type: string
- container: ''
  name: receiptPrinting
  type: string
- container: ''
  name: refunds
  type: string
- container: ''
  name: signature
  type: string
- container: ''
  name: standalone
  type: string
- container: ''
  name: surcharge
  type: string
- container: ''
  name: tapToPay
  type: string
- container: ''
  name: timeouts
  type: string
- container: ''
  name: wifiProfiles
  type: string
property_count: 20
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-terminal-settings-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TerminalSettings\": \"adyen:TerminalSettings\",\n    \"cardholderReceipt\": {\n      \"@id\": \"adyen:cardholderReceipt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectivity\": {\n      \"@id\": \"adyen:connectivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gratuities\": {\n      \"@id\": \"adyen:gratuities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hardware\": {\n      \"@id\": \"adyen:hardware\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localization\": {\n      \"@id\": \"adyen:localization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nexo\": {\n      \"@id\": \"adyen:nexo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offlineProcessing\": {\n      \"@id\"\
  : \"adyen:offlineProcessing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"opi\": {\n      \"@id\": \"adyen:opi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passcodes\": {\n      \"@id\": \"adyen:passcodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payAtTable\": {\n      \"@id\": \"adyen:payAtTable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payment\": {\n      \"@id\": \"adyen:payment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"receiptOptions\": {\n      \"@id\": \"adyen:receiptOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"receiptPrinting\": {\n      \"@id\": \"adyen:receiptPrinting\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refunds\": {\n      \"@id\": \"adyen:refunds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signature\": {\n      \"@id\": \"adyen:signature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standalone\": {\n      \"@id\": \"adyen:standalone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surcharge\": {\n\
  \      \"@id\": \"adyen:surcharge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tapToPay\": {\n      \"@id\": \"adyen:tapToPay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeouts\": {\n      \"@id\": \"adyen:timeouts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wifiProfiles\": {\n      \"@id\": \"adyen:wifiProfiles\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-settings-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 1
classes:
- UpdatePaymentMethodInfo
context_file: json-ld/adyen-management-update-payment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-update-payment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Update Payment from Adyen.
layout: jsonld
name: Adyen Management Update Payment Context
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
  name: bcmc
  type: string
- container: ''
  name: cartesBancaires
  type: string
- container: set
  name: countries
  type: string
- container: ''
  name: cup
  type: string
- container: set
  name: currencies
  type: string
- container: set
  name: customRoutingFlags
  type: string
- container: ''
  name: diners
  type: string
- container: ''
  name: discover
  type: string
- container: ''
  name: eftposAustralia
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: girocard
  type: string
- container: ''
  name: ideal
  type: string
- container: ''
  name: interacCard
  type: string
- container: ''
  name: jcb
  type: string
- container: ''
  name: maestro
  type: string
- container: ''
  name: mc
  type: string
- container: set
  name: storeIds
  type: string
- container: ''
  name: visa
  type: string
property_count: 18
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-update-payment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdatePaymentMethodInfo\": \"adyen:UpdatePaymentMethodInfo\",\n    \"bcmc\": {\n      \"@id\": \"adyen:bcmc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cartesBancaires\": {\n      \"@id\": \"adyen:cartesBancaires\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countries\": {\n      \"@id\": \"adyen:countries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cup\": {\n      \"@id\": \"adyen:cup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencies\": {\n      \"@id\": \"adyen:currencies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customRoutingFlags\": {\n      \"@id\": \"adyen:customRoutingFlags\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"diners\": {\n      \"@id\": \"adyen:diners\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discover\": {\n      \"@id\": \"adyen:discover\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eftposAustralia\": {\n      \"@id\": \"adyen:eftpos_australia\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"adyen:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"girocard\": {\n      \"@id\": \"adyen:girocard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ideal\": {\n      \"@id\": \"adyen:ideal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interacCard\": {\n      \"@id\": \"adyen:interac_card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jcb\": {\n      \"@id\": \"adyen:jcb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maestro\": {\n      \"@id\": \"adyen:maestro\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mc\": {\n      \"@id\": \"adyen:mc\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"storeIds\": {\n      \"@id\": \"adyen:storeIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visa\": {\n      \"@id\": \"adyen:visa\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-update-payment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

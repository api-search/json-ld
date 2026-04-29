---
class_count: 2
classes:
- ThreeDSAvailabilityRequest
- ThreeDSAvailabilityResponse
context_file: json-ld/adyen-binlookup-three-ds-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-three-ds-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Binlookup Three Ds from Adyen.
layout: jsonld
name: Adyen Binlookup Three Ds Context
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
- container: set
  name: brands
  type: string
- container: ''
  name: cardNumber
  type: string
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: binDetails
  type: string
- container: set
  name: dsPublicKeys
  type: string
- container: ''
  name: threeDS1Supported
  type: boolean
- container: set
  name: threeDS2CardRangeDetails
  type: string
- container: ''
  name: threeDS2supported
  type: boolean
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-binlookup-three-ds-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ThreeDSAvailabilityRequest\": \"adyen:ThreeDSAvailabilityRequest\",\n    \"ThreeDSAvailabilityResponse\": \"adyen:ThreeDSAvailabilityResponse\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"brands\": {\n      \"@id\": \"adyen:brands\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardNumber\": {\n      \"@id\": \"adyen:cardNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\"\
  : {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"binDetails\": {\n      \"@id\": \"adyen:binDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dsPublicKeys\": {\n      \"@id\": \"adyen:dsPublicKeys\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS1Supported\": {\n      \"@id\": \"adyen:threeDS1Supported\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"threeDS2CardRangeDetails\": {\n      \"@id\": \"adyen:threeDS2CardRangeDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS2supported\": {\n      \"@id\": \"adyen:threeDS2supported\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-three-ds-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

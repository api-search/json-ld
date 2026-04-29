---
class_count: 2
classes:
- ThreeDSRequestorAuthenticationInfo
- ThreeDSRequestorPriorAuthenticationInfo
context_file: json-ld/adyen-payments-three-ds-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-three-ds-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Three Ds from Adyen.
layout: jsonld
name: Adyen Payments Three Ds Context
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
  name: threeDSReqAuthData
  type: string
- container: ''
  name: threeDSReqAuthMethod
  type: string
- container: ''
  name: threeDSReqAuthTimestamp
  type: string
- container: ''
  name: threeDSReqPriorAuthData
  type: string
- container: ''
  name: threeDSReqPriorAuthMethod
  type: string
- container: ''
  name: threeDSReqPriorAuthTimestamp
  type: string
- container: ''
  name: threeDSReqPriorRef
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-three-ds-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ThreeDSRequestorAuthenticationInfo\": \"adyen:ThreeDSRequestorAuthenticationInfo\",\n    \"ThreeDSRequestorPriorAuthenticationInfo\": \"adyen:ThreeDSRequestorPriorAuthenticationInfo\",\n    \"threeDSReqAuthData\": {\n      \"@id\": \"adyen:threeDSReqAuthData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSReqAuthMethod\": {\n      \"@id\": \"adyen:threeDSReqAuthMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSReqAuthTimestamp\": {\n      \"@id\": \"adyen:threeDSReqAuthTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSReqPriorAuthData\": {\n      \"@id\": \"adyen:threeDSReqPriorAuthData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSReqPriorAuthMethod\": {\n      \"@id\": \"adyen:threeDSReqPriorAuthMethod\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSReqPriorAuthTimestamp\": {\n      \"@id\": \"adyen:threeDSReqPriorAuthTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSReqPriorRef\": {\n      \"@id\": \"adyen:threeDSReqPriorRef\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-three-ds-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

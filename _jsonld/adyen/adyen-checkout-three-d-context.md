---
class_count: 1
classes:
- ThreeDSecureData
context_file: json-ld/adyen-checkout-three-d-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-three-d-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Three D from Adyen.
layout: jsonld
name: Adyen Checkout Three D Context
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
  name: authenticationResponse
  type: string
- container: ''
  name: cavv
  type: string
- container: ''
  name: cavvAlgorithm
  type: string
- container: ''
  name: challengeCancel
  type: string
- container: ''
  name: directoryResponse
  type: string
- container: ''
  name: dsTransID
  type: string
- container: ''
  name: eci
  type: string
- container: ''
  name: riskScore
  type: string
- container: ''
  name: threeDSVersion
  type: string
- container: ''
  name: tokenAuthenticationVerificationValue
  type: string
- container: ''
  name: transStatusReason
  type: string
- container: ''
  name: xid
  type: string
property_count: 12
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-three-d-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ThreeDSecureData\": \"adyen:ThreeDSecureData\",\n    \"authenticationResponse\": {\n      \"@id\": \"adyen:authenticationResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cavv\": {\n      \"@id\": \"adyen:cavv\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cavvAlgorithm\": {\n      \"@id\": \"adyen:cavvAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"challengeCancel\": {\n      \"@id\": \"adyen:challengeCancel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directoryResponse\": {\n      \"@id\": \"adyen:directoryResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dsTransID\": {\n      \"@id\": \"adyen:dsTransID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eci\": {\n      \"@id\": \"adyen:eci\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"riskScore\": {\n      \"@id\": \"adyen:riskScore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSVersion\": {\n      \"@id\": \"adyen:threeDSVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenAuthenticationVerificationValue\": {\n      \"@id\": \"adyen:tokenAuthenticationVerificationValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transStatusReason\": {\n      \"@id\": \"adyen:transStatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xid\": {\n      \"@id\": \"adyen:xid\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-three-d-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

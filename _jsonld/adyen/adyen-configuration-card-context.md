---
class_count: 1
classes:
- Card
context_file: json-ld/adyen-configuration-card-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-card-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Card from Adyen.
layout: jsonld
name: Adyen Configuration Card Context
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
  name: authentication
  type: string
- container: ''
  name: bin
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: brandVariant
  type: string
- container: ''
  name: cardholderName
  type: string
- container: ''
  name: configuration
  type: string
- container: ''
  name: cvc
  type: string
- container: ''
  name: deliveryContact
  type: string
- container: ''
  name: expiration
  type: string
- container: ''
  name: formFactor
  type: string
- container: ''
  name: lastFour
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: threeDSecure
  type: string
property_count: 13
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-card-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Card\": \"adyen:Card\",\n    \"authentication\": {\n      \"@id\": \"adyen:authentication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bin\": {\n      \"@id\": \"adyen:bin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"adyen:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brandVariant\": {\n      \"@id\": \"adyen:brandVariant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardholderName\": {\n      \"@id\": \"adyen:cardholderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"adyen:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvc\": {\n      \"@id\": \"adyen:cvc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryContact\"\
  : {\n      \"@id\": \"adyen:deliveryContact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiration\": {\n      \"@id\": \"adyen:expiration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formFactor\": {\n      \"@id\": \"adyen:formFactor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastFour\": {\n      \"@id\": \"adyen:lastFour\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"adyen:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSecure\": {\n      \"@id\": \"adyen:threeDSecure\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-card-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

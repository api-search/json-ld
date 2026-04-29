---
class_count: 1
classes:
- GrantOffer
context_file: json-ld/adyen-configuration-grant-offer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-grant-offer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Grant Offer from Adyen.
layout: jsonld
name: Adyen Configuration Grant Offer Context
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
  name: accountHolderId
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: contractType
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: fee
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: repayment
  type: string
- container: ''
  name: startsAt
  type: dateTime
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-grant-offer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GrantOffer\": \"adyen:GrantOffer\",\n    \"accountHolderId\": {\n      \"@id\": \"adyen:accountHolderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contractType\": {\n      \"@id\": \"adyen:contractType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"adyen:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fee\": {\n      \"@id\": \"adyen:fee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repayment\": {\n      \"@id\": \"adyen:repayment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startsAt\"\
  : {\n      \"@id\": \"adyen:startsAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-grant-offer-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

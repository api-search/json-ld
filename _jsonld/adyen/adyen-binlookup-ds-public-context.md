---
class_count: 1
classes:
- DSPublicKeyDetail
context_file: json-ld/adyen-binlookup-ds-public-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-ds-public-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Binlookup Ds Public from Adyen.
layout: jsonld
name: Adyen Binlookup Ds Public Context
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
  name: brand
  type: string
- container: ''
  name: directoryServerId
  type: string
- container: ''
  name: fromSDKVersion
  type: string
- container: ''
  name: publicKey
  type: string
- container: ''
  name: rootCertificates
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-binlookup-ds-public-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DSPublicKeyDetail\": \"adyen:DSPublicKeyDetail\",\n    \"brand\": {\n      \"@id\": \"adyen:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directoryServerId\": {\n      \"@id\": \"adyen:directoryServerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fromSDKVersion\": {\n      \"@id\": \"adyen:fromSDKVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicKey\": {\n      \"@id\": \"adyen:publicKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rootCertificates\": {\n      \"@id\": \"adyen:rootCertificates\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-ds-public-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

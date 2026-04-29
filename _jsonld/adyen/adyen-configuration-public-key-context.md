---
class_count: 1
classes:
- PublicKeyResponse
context_file: json-ld/adyen-configuration-public-key-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-public-key-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Public Key from Adyen.
layout: jsonld
name: Adyen Configuration Public Key Context
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
  name: publicKey
  type: string
- container: ''
  name: publicKeyExpiryDate
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-public-key-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PublicKeyResponse\": \"adyen:PublicKeyResponse\",\n    \"publicKey\": {\n      \"@id\": \"adyen:publicKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicKeyExpiryDate\": {\n      \"@id\": \"adyen:publicKeyExpiryDate\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-public-key-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

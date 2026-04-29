---
class_count: 1
classes:
- MobileData
context_file: json-ld/adyen-terminal-mobile-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-mobile-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Mobile Data from Adyen.
layout: jsonld
name: Adyen Terminal Mobile Data Context
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
  name: MobileCountryCode
  type: integer
- container: ''
  name: MobileNetworkCode
  type: integer
- container: ''
  name: MaskedMSISDN
  type: integer
- container: ''
  name: Geolocation
  type: string
- container: ''
  name: ProtectedMobileData
  type: string
- container: ''
  name: SensitiveMobileData
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-mobile-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MobileData\": \"adyen:MobileData\",\n    \"MobileCountryCode\": {\n      \"@id\": \"adyen:MobileCountryCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MobileNetworkCode\": {\n      \"@id\": \"adyen:MobileNetworkCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MaskedMSISDN\": {\n      \"@id\": \"adyen:MaskedMSISDN\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Geolocation\": {\n      \"@id\": \"adyen:Geolocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProtectedMobileData\": {\n      \"@id\": \"adyen:ProtectedMobileData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SensitiveMobileData\": {\n      \"@id\": \"adyen:SensitiveMobileData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-mobile-data-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

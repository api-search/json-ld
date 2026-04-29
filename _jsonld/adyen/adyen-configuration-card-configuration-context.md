---
class_count: 1
classes:
- CardConfiguration
context_file: json-ld/adyen-configuration-card-configuration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-card-configuration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Card Configuration from Adyen.
layout: jsonld
name: Adyen Configuration Card Configuration Context
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
  name: activation
  type: string
- container: ''
  name: activationUrl
  type: string
- container: ''
  name: bulkAddress
  type: string
- container: ''
  name: cardImageId
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: carrierImageId
  type: string
- container: ''
  name: configurationProfileId
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: envelope
  type: string
- container: ''
  name: insert
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: logoImageId
  type: string
- container: ''
  name: pinMailer
  type: string
- container: ''
  name: shipmentMethod
  type: string
property_count: 14
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-card-configuration-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CardConfiguration\": \"adyen:CardConfiguration\",\n    \"activation\": {\n      \"@id\": \"adyen:activation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activationUrl\": {\n      \"@id\": \"adyen:activationUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bulkAddress\": {\n      \"@id\": \"adyen:bulkAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardImageId\": {\n      \"@id\": \"adyen:cardImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"adyen:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrierImageId\": {\n      \"@id\": \"adyen:carrierImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationProfileId\": {\n      \"@id\": \"adyen:configurationProfileId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"adyen:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"envelope\": {\n      \"@id\": \"adyen:envelope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insert\": {\n      \"@id\": \"adyen:insert\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"adyen:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logoImageId\": {\n      \"@id\": \"adyen:logoImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pinMailer\": {\n      \"@id\": \"adyen:pinMailer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipmentMethod\": {\n      \"@id\": \"adyen:shipmentMethod\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-card-configuration-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

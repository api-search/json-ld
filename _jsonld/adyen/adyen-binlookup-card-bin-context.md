---
class_count: 1
classes:
- CardBin
context_file: json-ld/adyen-binlookup-card-bin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-card-bin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Binlookup Card Bin from Adyen.
layout: jsonld
name: Adyen Binlookup Card Bin Context
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
  name: bin
  type: string
- container: ''
  name: commercial
  type: boolean
- container: ''
  name: fundingSource
  type: string
- container: ''
  name: fundsAvailability
  type: string
- container: ''
  name: issuerBin
  type: string
- container: ''
  name: issuingBank
  type: string
- container: ''
  name: issuingCountry
  type: string
- container: ''
  name: issuingCurrency
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: payoutEligible
  type: string
- container: ''
  name: summary
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-binlookup-card-bin-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CardBin\": \"adyen:CardBin\",\n    \"bin\": {\n      \"@id\": \"adyen:bin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commercial\": {\n      \"@id\": \"adyen:commercial\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundsAvailability\": {\n      \"@id\": \"adyen:fundsAvailability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerBin\": {\n      \"@id\": \"adyen:issuerBin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuingBank\": {\n      \"@id\": \"adyen:issuingBank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuingCountry\": {\n      \"@id\": \"adyen:issuingCountry\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"issuingCurrency\": {\n      \"@id\": \"adyen:issuingCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"adyen:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payoutEligible\": {\n      \"@id\": \"adyen:payoutEligible\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"adyen:summary\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-card-bin-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

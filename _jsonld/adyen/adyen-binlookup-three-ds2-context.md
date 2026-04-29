---
class_count: 1
classes:
- ThreeDS2CardRangeDetail
context_file: json-ld/adyen-binlookup-three-ds2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-three-ds2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Binlookup Three Ds2 from Adyen.
layout: jsonld
name: Adyen Binlookup Three Ds2 Context
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
- container: set
  name: acsInfoInd
  type: string
- container: ''
  name: brandCode
  type: string
- container: ''
  name: endRange
  type: string
- container: ''
  name: startRange
  type: string
- container: set
  name: threeDS2Versions
  type: string
- container: ''
  name: threeDSMethodURL
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-binlookup-three-ds2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ThreeDS2CardRangeDetail\": \"adyen:ThreeDS2CardRangeDetail\",\n    \"acsInfoInd\": {\n      \"@id\": \"adyen:acsInfoInd\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brandCode\": {\n      \"@id\": \"adyen:brandCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endRange\": {\n      \"@id\": \"adyen:endRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startRange\": {\n      \"@id\": \"adyen:startRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS2Versions\": {\n      \"@id\": \"adyen:threeDS2Versions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSMethodURL\": {\n      \"@id\": \"adyen:threeDSMethodURL\",\n      \"@type\": \"xsd:string\"\
  \n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-binlookup-three-ds2-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

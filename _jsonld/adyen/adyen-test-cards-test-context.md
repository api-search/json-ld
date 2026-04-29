---
class_count: 2
classes:
- TestCardRangeCreationResult
- TestCardRange
context_file: json-ld/adyen-test-cards-test-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-test-cards-test-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Test Cards Test from Adyen.
layout: jsonld
name: Adyen Test Cards Test Context
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
  name: cardNumberRangeEnd
  type: string
- container: ''
  name: cardNumberRangeStart
  type: string
- container: ''
  name: creationResultCode
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: cardHolderName
  type: string
- container: ''
  name: cvc
  type: string
- container: ''
  name: expiryMonth
  type: string
- container: ''
  name: expiryYear
  type: integer
- container: ''
  name: rangeEnd
  type: string
- container: ''
  name: rangeStart
  type: string
- container: ''
  name: threeDDirectoryServerResponse
  type: string
- container: ''
  name: threeDPassword
  type: string
- container: ''
  name: threeDUsername
  type: string
property_count: 14
provider_name: Adyen
provider_slug: adyen
slug: adyen-test-cards-test-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TestCardRangeCreationResult\": \"adyen:TestCardRangeCreationResult\",\n    \"TestCardRange\": \"adyen:TestCardRange\",\n    \"cardNumberRangeEnd\": {\n      \"@id\": \"adyen:cardNumberRangeEnd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardNumberRangeStart\": {\n      \"@id\": \"adyen:cardNumberRangeStart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationResultCode\": {\n      \"@id\": \"adyen:creationResultCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"adyen:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardHolderName\": {\n      \"@id\": \"adyen:cardHolderName\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"cvc\": {\n      \"@id\": \"adyen:cvc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryMonth\": {\n      \"@id\": \"adyen:expiryMonth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryYear\": {\n      \"@id\": \"adyen:expiryYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rangeEnd\": {\n      \"@id\": \"adyen:rangeEnd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rangeStart\": {\n      \"@id\": \"adyen:rangeStart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDDirectoryServerResponse\": {\n      \"@id\": \"adyen:threeDDirectoryServerResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDPassword\": {\n      \"@id\": \"adyen:threeDPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDUsername\": {\n      \"@id\": \"adyen:threeDUsername\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-test-cards-test-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

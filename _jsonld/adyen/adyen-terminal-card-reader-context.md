---
class_count: 2
classes:
- CardReaderAPDURequest
- CardReaderAPDUResponse
context_file: json-ld/adyen-terminal-card-reader-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-card-reader-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Card Reader from Adyen.
layout: jsonld
name: Adyen Terminal Card Reader Context
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
  name: APDUClass
  type: string
- container: ''
  name: APDUInstruction
  type: string
- container: ''
  name: APDUPar1
  type: string
- container: ''
  name: APDUPar2
  type: string
- container: ''
  name: APDUData
  type: string
- container: ''
  name: APDUExpectedLength
  type: string
- container: ''
  name: Response
  type: string
- container: ''
  name: CardStatusWords
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-card-reader-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CardReaderAPDURequest\": \"adyen:CardReaderAPDURequest\",\n    \"CardReaderAPDUResponse\": \"adyen:CardReaderAPDUResponse\",\n    \"APDUClass\": {\n      \"@id\": \"adyen:APDUClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APDUInstruction\": {\n      \"@id\": \"adyen:APDUInstruction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APDUPar1\": {\n      \"@id\": \"adyen:APDUPar1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APDUPar2\": {\n      \"@id\": \"adyen:APDUPar2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APDUData\": {\n      \"@id\": \"adyen:APDUData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"APDUExpectedLength\": {\n      \"@id\": \"adyen:APDUExpectedLength\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Response\": {\n      \"@id\": \"adyen:Response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardStatusWords\": {\n      \"@id\": \"adyen:CardStatusWords\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-card-reader-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

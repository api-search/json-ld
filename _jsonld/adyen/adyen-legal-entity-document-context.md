---
class_count: 4
classes:
- DocumentPage
- DocumentReference
- Document
- description
context_file: json-ld/adyen-legal-entity-document-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-document-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Document from Adyen.
layout: jsonld
name: Adyen Legal Entity Document Context
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
  name: pageName
  type: string
- container: ''
  name: pageNumber
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: fileName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: modificationDate
  type: dateTime
- container: set
  name: pages
  type: string
- container: ''
  name: attachment
  type: string
- container: set
  name: attachments
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: expiryDate
  type: string
- container: ''
  name: issuerCountry
  type: string
- container: ''
  name: issuerState
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: owner
  type: string
property_count: 16
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-document-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DocumentPage\": \"adyen:DocumentPage\",\n    \"DocumentReference\": \"adyen:DocumentReference\",\n    \"Document\": \"adyen:Document\",\n    \"pageName\": {\n      \"@id\": \"adyen:pageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageNumber\": {\n      \"@id\": \"adyen:pageNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"adyen:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"description\": \"schema:description\",\n    \"fileName\": {\n      \"@id\": \"adyen:fileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"modificationDate\": {\n      \"@id\": \"adyen:modificationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"pages\": {\n      \"@id\": \"adyen:pages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachment\": {\n      \"@id\": \"adyen:attachment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachments\": {\n      \"@id\": \"adyen:attachments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"adyen:expiryDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerCountry\": {\n      \"@id\": \"adyen:issuerCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerState\": {\n      \"@id\": \"adyen:issuerState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"adyen:number\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"owner\": {\n      \"@id\": \"adyen:owner\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-document-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

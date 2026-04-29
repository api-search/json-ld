---
class_count: 2
classes:
- DocumentDetail
- description
context_file: json-ld/adyen-accounts-document-detail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-document-detail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Document Detail from Adyen.
layout: jsonld
name: Adyen Accounts Document Detail Context
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
  name: accountHolderCode
  type: string
- container: ''
  name: bankAccountUUID
  type: string
- container: ''
  name: documentType
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: legalArrangementCode
  type: string
- container: ''
  name: legalArrangementEntityCode
  type: string
- container: ''
  name: shareholderCode
  type: string
- container: ''
  name: signatoryCode
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-document-detail-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DocumentDetail\": \"adyen:DocumentDetail\",\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountUUID\": {\n      \"@id\": \"adyen:bankAccountUUID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"documentType\": {\n      \"@id\": \"adyen:documentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\": {\n      \"@id\": \"adyen:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementCode\": {\n      \"@id\": \"adyen:legalArrangementCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"legalArrangementEntityCode\": {\n      \"@id\": \"adyen:legalArrangementEntityCode\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"shareholderCode\": {\n      \"@id\": \"adyen:shareholderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatoryCode\": {\n      \"@id\": \"adyen:signatoryCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-document-detail-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

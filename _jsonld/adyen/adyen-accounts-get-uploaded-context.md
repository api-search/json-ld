---
class_count: 2
classes:
- GetUploadedDocumentsRequest
- GetUploadedDocumentsResponse
context_file: json-ld/adyen-accounts-get-uploaded-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-get-uploaded-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Accounts Get Uploaded from Adyen.
layout: jsonld
name: Adyen Accounts Get Uploaded Context
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
  name: shareholderCode
  type: string
- container: set
  name: documentDetails
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: resultCode
  type: string
property_count: 7
provider_name: Adyen
provider_slug: adyen
slug: adyen-accounts-get-uploaded-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetUploadedDocumentsRequest\": \"adyen:GetUploadedDocumentsRequest\",\n    \"GetUploadedDocumentsResponse\": \"adyen:GetUploadedDocumentsResponse\",\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankAccountUUID\": {\n      \"@id\": \"adyen:bankAccountUUID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareholderCode\": {\n      \"@id\": \"adyen:shareholderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentDetails\": {\n      \"@id\": \"adyen:documentDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-accounts-get-uploaded-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

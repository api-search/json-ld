---
class_count: 1
classes:
- SubmitRequest
context_file: json-ld/adyen-payouts-submit-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-submit-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payouts Submit Request from Adyen.
layout: jsonld
name: Adyen Payouts Submit Request Context
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
  name: additionalData
  type: reference
- container: ''
  name: amount
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: entityType
  type: string
- container: ''
  name: fraudOffset
  type: integer
- container: ''
  name: merchantAccount
  type: string
- container: ''
  name: nationality
  type: string
- container: ''
  name: recurring
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: selectedRecurringDetailReference
  type: string
- container: ''
  name: shopperEmail
  type: string
- container: ''
  name: shopperName
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: shopperStatement
  type: string
- container: ''
  name: socialSecurityNumber
  type: string
property_count: 15
provider_name: Adyen
provider_slug: adyen
slug: adyen-payouts-submit-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SubmitRequest\": \"adyen:SubmitRequest\",\n    \"additionalData\": {\n      \"@id\": \"adyen:additionalData\",\n      \"@type\": \"@id\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"adyen:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"entityType\": {\n      \"@id\": \"adyen:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fraudOffset\": {\n      \"@id\": \"adyen:fraudOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nationality\": {\n      \"@id\": \"adyen:nationality\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"recurring\": {\n      \"@id\": \"adyen:recurring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedRecurringDetailReference\": {\n      \"@id\": \"adyen:selectedRecurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperEmail\": {\n      \"@id\": \"adyen:shopperEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperName\": {\n      \"@id\": \"adyen:shopperName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperStatement\": {\n      \"@id\": \"adyen:shopperStatement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"socialSecurityNumber\": {\n      \"@id\": \"adyen:socialSecurityNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payouts-submit-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

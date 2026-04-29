---
class_count: 2
classes:
- RecurringDetailsRequest
- RecurringDetailsResult
context_file: json-ld/adyen-recurring-recurring-details-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-recurring-details-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Recurring Recurring Details from Adyen.
layout: jsonld
name: Adyen Recurring Recurring Details Context
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
  name: merchantAccount
  type: string
- container: ''
  name: recurring
  type: string
- container: ''
  name: shopperReference
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: set
  name: details
  type: string
- container: ''
  name: lastKnownShopperEmail
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-recurring-recurring-details-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RecurringDetailsRequest\": \"adyen:RecurringDetailsRequest\",\n    \"RecurringDetailsResult\": \"adyen:RecurringDetailsResult\",\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurring\": {\n      \"@id\": \"adyen:recurring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperReference\": {\n      \"@id\": \"adyen:shopperReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"details\": {\n      \"@id\": \"adyen:details\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastKnownShopperEmail\": {\n      \"@id\"\
  : \"adyen:lastKnownShopperEmail\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-recurring-recurring-details-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

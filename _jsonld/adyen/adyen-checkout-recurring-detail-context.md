---
class_count: 2
classes:
- RecurringDetail
- name
context_file: json-ld/adyen-checkout-recurring-detail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-recurring-detail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Recurring Detail from Adyen.
layout: jsonld
name: Adyen Checkout Recurring Detail Context
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
  name: brand
  type: string
- container: set
  name: brands
  type: string
- container: ''
  name: configuration
  type: reference
- container: ''
  name: fundingSource
  type: string
- container: ''
  name: group
  type: string
- container: set
  name: inputDetails
  type: string
- container: set
  name: issuers
  type: string
- container: ''
  name: recurringDetailReference
  type: string
- container: ''
  name: storedDetails
  type: string
- container: ''
  name: type
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-recurring-detail-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RecurringDetail\": \"adyen:RecurringDetail\",\n    \"brand\": {\n      \"@id\": \"adyen:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brands\": {\n      \"@id\": \"adyen:brands\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"adyen:configuration\",\n      \"@type\": \"@id\"\n    },\n    \"fundingSource\": {\n      \"@id\": \"adyen:fundingSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"adyen:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputDetails\": {\n      \"@id\": \"adyen:inputDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuers\": {\n      \"@id\"\
  : \"adyen:issuers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"recurringDetailReference\": {\n      \"@id\": \"adyen:recurringDetailReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storedDetails\": {\n      \"@id\": \"adyen:storedDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-recurring-detail-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---

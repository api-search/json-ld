---
api_specs:
- filename: utilityapi-openapi.yml
  format: yaml
  label: UtilityAPI
  slug: utilityapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/openapi/utilityapi-openapi.yml
class_count: 18
classes:
- uid
- Meter
- Bill
- Interval
- Authorization
- utility
- service_address
- meter_number
- service_class
- statement_date
- due_date
- total_amount
- currency
- start
- end
- created
- modified
- status
context_file: json-ld/utilityapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/json-ld/utilityapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Utilityapi from UtilityAPI.
layout: jsonld
name: Utilityapi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: energy
  uri: https://www.w3.org/ns/sosa/
properties:
- container: ''
  name: total_kwh
  type: schema:QuantitativeValue
- container: ''
  name: kwh
  type: schema:QuantitativeValue
property_count: 2
provider_name: UtilityAPI
provider_slug: utilityapi
slug: utilityapi-context
source_filename: utilityapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://utilityapi.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"energy\": \"https://www.w3.org/ns/sosa/\",\n    \"uid\": \"@id\",\n    \"Meter\": \"schema:Utility\",\n    \"Bill\": \"schema:Invoice\",\n    \"Interval\": \"energy:Observation\",\n    \"Authorization\": \"schema:DigitalDocument\",\n    \"utility\": \"schema:serviceType\",\n    \"service_address\": \"schema:address\",\n    \"meter_number\": \"schema:identifier\",\n    \"service_class\": \"schema:additionalType\",\n    \"statement_date\": \"schema:dateIssued\",\n    \"due_date\": \"schema:paymentDueDate\",\n    \"total_kwh\": {\n      \"@id\": \"https://schema.org/energy\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"total_amount\": \"schema:totalPaymentDue\",\n    \"currency\": \"schema:priceCurrency\",\n    \"start\": \"schema:startDate\",\n    \"end\": \"schema:endDate\",\n    \"kwh\": {\n      \"@id\": \"https://schema.org/energy\",\n\
  \      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"created\": \"schema:dateCreated\",\n    \"modified\": \"schema:dateModified\",\n    \"status\": \"schema:status\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/json-ld/utilityapi-context.jsonld
tags:
- Energy
- Utilities
- Green Button
- Billing Data
- Meter Data
- Clean Energy
- JSON-LD
- Linked Data
- Semantic Web
---

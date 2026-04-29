---
class_count: 9
classes:
- activity_id
- name
- category
- sector
- source
- region
- data_version
- co2e_calculation_method
- constituent_gases
context_file: json-ld/climatiq-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/json-ld/climatiq-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Climatiq from Climatiq.
layout: jsonld
name: Climatiq Context
namespaces:
- prefix: climatiq
  uri: https://www.climatiq.io/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: EmissionFactor
  type: ''
- container: ''
  name: EmissionEstimate
  type: schema:QuantitativeValue
- container: ''
  name: Activity
  type: schema:Action
- container: ''
  name: year
  type: gYear
- container: ''
  name: co2e
  type: decimal
- container: ''
  name: co2e_unit
  type: ''
property_count: 6
provider_name: Climatiq
provider_slug: climatiq
slug: climatiq-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"climatiq\": \"https://www.climatiq.io/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"EmissionFactor\": {\n      \"@id\": \"climatiq:EmissionFactor\"\n    },\n    \"EmissionEstimate\": {\n      \"@id\": \"climatiq:EmissionEstimate\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"Activity\": {\n      \"@id\": \"climatiq:Activity\",\n      \"@type\": \"schema:Action\"\n    },\n\n    \"activity_id\": \"climatiq:activityId\",\n    \"name\": \"schema:name\",\n    \"category\": \"climatiq:category\",\n    \"sector\": \"climatiq:sector\",\n    \"source\": \"climatiq:source\",\n    \"year\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:gYear\"\n    },\n    \"region\": \"schema:areaServed\",\n    \"data_version\": \"climatiq:dataVersion\",\n\n    \"co2e\": {\n      \"@id\": \"climatiq:co2e\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"co2e_unit\": {\n      \"@id\": \"qudt:unit\"\n    },\n    \"co2e_calculation_method\": \"climatiq:method\",\n    \"constituent_gases\": \"climatiq:constituentGases\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/climatiq/refs/heads/main/json-ld/climatiq-context.jsonld
tags:
- Carbon Accounting
- Carbon Emissions
- Climate
- Energy
- Environment
- GHG Protocol
- Sustainability
- JSON-LD
- Linked Data
- Semantic Web
---

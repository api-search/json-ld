---
class_count: 0
classes: []
context_file: json-ld/data-commons-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/data-commons/refs/heads/main/json-ld/data-commons-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Data Commons from Data Commons.
layout: jsonld
name: Data Commons Context
namespaces:
- prefix: dc
  uri: https://datacommons.org/browser/
- prefix: DCID
  uri: https://schema.org/identifier
properties:
- container: ''
  name: StatisticalVariable
  type: ''
- container: ''
  name: Place
  type: ''
- container: ''
  name: Observation
  type: ''
- container: ''
  name: Provenance
  type: ''
property_count: 4
provider_name: Data Commons
provider_slug: data-commons
slug: data-commons-context
source_filename: data-commons-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dc\": \"https://datacommons.org/browser/\",\n    \"DCID\": \"https://schema.org/identifier\",\n    \"StatisticalVariable\": {\n      \"@id\": \"dc:StatisticalVariable\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"measuredProperty\": \"https://schema.org/propertyID\",\n        \"populationType\": \"https://schema.org/about\",\n        \"statType\": \"https://schema.org/additionalType\",\n        \"constraintProperties\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"Place\": {\n      \"@id\": \"https://schema.org/Place\",\n      \"@context\": {\n        \"dcid\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"containedInPlace\": \"https://schema.org/containedInPlace\",\n        \"typeOf\": \"https://schema.org/additionalType\"\n      }\n    },\n    \"Observation\": {\n      \"@id\": \"https://schema.org/Observation\"\
  ,\n      \"@context\": {\n        \"variable\": \"https://schema.org/variableMeasured\",\n        \"place\": \"https://schema.org/observationAbout\",\n        \"value\": \"https://schema.org/value\",\n        \"date\": \"https://schema.org/observationDate\",\n        \"unit\": \"https://schema.org/unitText\",\n        \"provenance\": \"https://schema.org/sourceOrganization\"\n      }\n    },\n    \"Provenance\": {\n      \"@id\": \"dc:Provenance\",\n      \"@context\": {\n        \"source\": \"https://schema.org/sourceOrganization\",\n        \"url\": \"https://schema.org/url\",\n        \"importDate\": \"https://schema.org/dateCreated\",\n        \"version\": \"https://schema.org/version\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/data-commons/refs/heads/main/json-ld/data-commons-context.jsonld
tags:
- Data Commons
- Knowledge Graph
- Open Data
- Public Data
- Statistics
- JSON-LD
- Linked Data
- Semantic Web
---

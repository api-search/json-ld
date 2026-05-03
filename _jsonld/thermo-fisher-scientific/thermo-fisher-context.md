---
api_specs:
- filename: thermo-fisher-samplemanager-openapi.yml
  format: yaml
  label: Thermo Fisher SampleManager LIMS REST API
  slug: samplemanager-lims
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/openapi/thermo-fisher-samplemanager-openapi.yml
- filename: thermo-fisher-nanodrop-openapi.yml
  format: yaml
  label: Thermo Fisher NanoDrop Ultra Web API
  slug: nanodrop-ultra
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/openapi/thermo-fisher-nanodrop-openapi.yml
class_count: 0
classes: []
context_file: json-ld/thermo-fisher-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/json-ld/thermo-fisher-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thermo Fisher from Thermo Fisher Scientific.
layout: jsonld
name: Thermo Fisher Context
namespaces:
- prefix: tfs
  uri: https://www.thermofisher.com/ontology/
- prefix: bio
  uri: http://purl.obolibrary.org/obo/
properties:
- container: ''
  name: Sample
  type: ''
- container: ''
  name: Result
  type: ''
- container: ''
  name: NanoDropMeasurement
  type: ''
property_count: 3
provider_name: Thermo Fisher Scientific
provider_slug: thermo-fisher-scientific
slug: thermo-fisher-context
source_filename: thermo-fisher-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tfs\": \"https://www.thermofisher.com/ontology/\",\n    \"bio\": \"http://purl.obolibrary.org/obo/\",\n    \"Sample\": {\n      \"@id\": \"tfs:LabSample\",\n      \"@context\": {\n        \"identity\": \"https://schema.org/identifier\",\n        \"description\": \"https://schema.org/description\",\n        \"status\": \"https://schema.org/status\",\n        \"sampled_date\": \"https://schema.org/dateCreated\",\n        \"customer\": {\n          \"@id\": \"https://schema.org/customer\",\n          \"@type\": \"@id\"\n        },\n        \"product\": {\n          \"@id\": \"https://schema.org/about\",\n          \"@type\": \"@id\"\n        },\n        \"analysis\": {\n          \"@id\": \"tfs:analysis\",\n          \"@type\": \"@id\"\n        },\n        \"due_date\": \"https://schema.org/expires\"\n      }\n    },\n    \"Result\": {\n      \"@id\": \"tfs:TestResult\",\n      \"@context\": {\n        \"sample_id\"\
  : {\n          \"@id\": \"tfs:fromSample\",\n          \"@type\": \"@id\"\n        },\n        \"test\": \"https://schema.org/name\",\n        \"component\": \"https://schema.org/additionalType\",\n        \"result_value\": \"https://schema.org/value\",\n        \"units\": \"https://schema.org/unitText\",\n        \"status\": \"https://schema.org/status\",\n        \"entered_on\": \"https://schema.org/dateCreated\",\n        \"entered_by\": \"https://schema.org/agent\"\n      }\n    },\n    \"NanoDropMeasurement\": {\n      \"@id\": \"tfs:SpectrophotometricMeasurement\",\n      \"@context\": {\n        \"measurement_id\": \"https://schema.org/identifier\",\n        \"sample_id\": {\n          \"@id\": \"tfs:fromSample\",\n          \"@type\": \"@id\"\n        },\n        \"method\": \"https://schema.org/measurementTechnique\",\n        \"timestamp\": \"https://schema.org/dateCreated\",\n        \"operator\": \"https://schema.org/agent\",\n        \"concentration\": {\n          \"@id\"\
  : \"tfs:concentration\",\n          \"@type\": \"https://schema.org/QuantitativeValue\"\n        },\n        \"a260\": {\n          \"@id\": \"tfs:absorbanceAt260nm\",\n          \"@type\": \"https://schema.org/QuantitativeValue\"\n        },\n        \"a280\": {\n          \"@id\": \"tfs:absorbanceAt280nm\",\n          \"@type\": \"https://schema.org/QuantitativeValue\"\n        },\n        \"a260_a280_ratio\": {\n          \"@id\": \"tfs:purityRatio260280\",\n          \"@type\": \"https://schema.org/QuantitativeValue\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/json-ld/thermo-fisher-context.jsonld
tags:
- Life Sciences
- Laboratory
- Scientific Instruments
- LIMS
- Diagnostics
- Biosciences
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---

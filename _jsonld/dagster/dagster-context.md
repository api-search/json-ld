---
api_specs:
- filename: dagster-external-assets-rest-api-openapi.yml
  format: yaml
  label: Dagster External Assets REST API
  slug: external-assets-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/openapi/dagster-external-assets-rest-api-openapi.yml
class_count: 3
classes:
- AssetMaterialization
- AssetCheck
- AssetObservation
context_file: json-ld/dagster-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/json-ld/dagster-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dagster from Dagster.
layout: jsonld
name: Dagster Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dagster
  uri: https://schema.dagster.io/
properties:
- container: ''
  name: asset_key
  type: schema:Text
- container: ''
  name: metadata
  type: '@json'
- container: ''
  name: data_version
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: ''
  name: partition
  type: schema:Text
- container: ''
  name: check_name
  type: schema:Text
- container: ''
  name: passed
  type: schema:Boolean
- container: ''
  name: severity
  type: schema:Text
property_count: 8
provider_name: Dagster
provider_slug: dagster
slug: dagster-context
source_filename: dagster-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.dagster.io/\",\n    \"schema\": \"https://schema.org/\",\n    \"dagster\": \"https://schema.dagster.io/\",\n    \"AssetMaterialization\": \"dagster:AssetMaterialization\",\n    \"AssetCheck\": \"dagster:AssetCheck\",\n    \"AssetObservation\": \"dagster:AssetObservation\",\n    \"asset_key\": {\n      \"@id\": \"dagster:assetKey\",\n      \"@type\": \"schema:Text\"\n    },\n    \"metadata\": {\n      \"@id\": \"dagster:metadata\",\n      \"@type\": \"@json\"\n    },\n    \"data_version\": {\n      \"@id\": \"dagster:dataVersion\",\n      \"@type\": \"schema:Text\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"schema:Text\"\n    },\n    \"partition\": {\n      \"@id\": \"dagster:partition\",\n      \"@type\": \"schema:Text\"\n    },\n    \"check_name\": {\n      \"@id\": \"dagster:checkName\",\n      \"@type\": \"schema:Text\"\n    },\n    \"passed\":\
  \ {\n      \"@id\": \"dagster:passed\",\n      \"@type\": \"schema:Boolean\"\n    },\n    \"severity\": {\n      \"@id\": \"dagster:severity\",\n      \"@type\": \"schema:Text\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/json-ld/dagster-context.jsonld
tags:
- Data Engineering
- Data Orchestration
- Data Pipelines
- ETL
- Workflows
- Assets
- GraphQL
- JSON-LD
- Linked Data
- Semantic Web
---

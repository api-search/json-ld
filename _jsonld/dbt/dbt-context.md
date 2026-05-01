---
api_specs:
- filename: dbt-cloud-administrative-api-openapi.yml
  format: yaml
  label: dbt Cloud Administrative API
  slug: dbt-cloud-administrative-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/openapi/dbt-cloud-administrative-api-openapi.yml
- filename: dbt-cloud-discovery-api-openapi.yml
  format: yaml
  label: dbt Cloud Discovery API
  slug: dbt-cloud-discovery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/openapi/dbt-cloud-discovery-api-openapi.yml
- filename: dbt-cloud-semantic-layer-api-openapi.yml
  format: yaml
  label: dbt Cloud Semantic Layer API
  slug: dbt-cloud-semantic-layer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/openapi/dbt-cloud-semantic-layer-api-openapi.yml
class_count: 6
classes:
- Project
- Job
- Run
- Environment
- Model
- Source
context_file: json-ld/dbt-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/json-ld/dbt-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dbt from dbt.
layout: jsonld
name: Dbt Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dbt
  uri: https://schema.getdbt.com/
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: started_at
  type: schema:DateTime
- container: ''
  name: finished_at
  type: schema:DateTime
- container: ''
  name: duration
  type: schema:Text
- container: ''
  name: git_branch
  type: schema:Text
- container: ''
  name: git_sha
  type: schema:Text
- container: ''
  name: execute_steps
  type: ''
property_count: 10
provider_name: dbt
provider_slug: dbt
slug: dbt-context
source_filename: dbt-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.getdbt.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"dbt\": \"https://schema.getdbt.com/\",\n    \"Project\": \"dbt:Project\",\n    \"Job\": \"dbt:Job\",\n    \"Run\": \"dbt:Run\",\n    \"Environment\": \"dbt:Environment\",\n    \"Model\": \"dbt:Model\",\n    \"Source\": \"dbt:Source\",\n    \"id\": {\"@id\": \"schema:identifier\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"schema:Text\"},\n    \"status\": {\"@id\": \"dbt:status\", \"@type\": \"schema:Text\"},\n    \"started_at\": {\"@id\": \"schema:startTime\", \"@type\": \"schema:DateTime\"},\n    \"finished_at\": {\"@id\": \"schema:endTime\", \"@type\": \"schema:DateTime\"},\n    \"duration\": {\"@id\": \"schema:duration\", \"@type\": \"schema:Text\"},\n    \"git_branch\": {\"@id\": \"dbt:gitBranch\", \"@type\": \"schema:Text\"},\n    \"\
  git_sha\": {\"@id\": \"dbt:gitSha\", \"@type\": \"schema:Text\"},\n    \"execute_steps\": {\"@id\": \"dbt:executeSteps\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dbt/refs/heads/main/json-ld/dbt-context.jsonld
tags:
- Analytics Engineering
- Data
- ELT
- Metrics
- Projects
- SQL
- Transformation
- JSON-LD
- Linked Data
- Semantic Web
---

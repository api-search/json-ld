---
api_specs:
- filename: grafana-dashboard-openapi.yml
  format: yaml
  label: Grafana HTTP API
  slug: grafana
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/openapi/grafana-dashboard-openapi.yml
class_count: 22
classes:
- Dashboard
- Panel
- Datasource
- Folder
- Annotation
- AlertRule
- Team
- title
- description
- tags
- uid
- created
- updated
- panels
- refresh
- folderId
- datasource
- query
- time
- annotations
- labels
- orgId
context_file: json-ld/tableaux-de-bord-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/json-ld/tableaux-de-bord-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tableaux De Bord from Tableaux De Bord.
layout: jsonld
name: Tableaux De Bord Context
namespaces:
- prefix: grafana
  uri: https://grafana.com/vocabulary/
properties: []
property_count: 0
provider_name: Tableaux De Bord
provider_slug: tableaux-de-bord
slug: tableaux-de-bord-context
source_filename: tableaux-de-bord-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"grafana\": \"https://grafana.com/vocabulary/\",\n    \"Dashboard\": \"schema:Dataset\",\n    \"Panel\": \"grafana:Panel\",\n    \"Datasource\": \"grafana:Datasource\",\n    \"Folder\": \"schema:Collection\",\n    \"Annotation\": \"schema:Comment\",\n    \"AlertRule\": \"grafana:AlertRule\",\n    \"Team\": \"schema:Organization\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"tags\": \"schema:keywords\",\n    \"uid\": \"schema:identifier\",\n    \"created\": \"schema:dateCreated\",\n    \"updated\": \"schema:dateModified\",\n    \"panels\": \"schema:hasPart\",\n    \"refresh\": \"grafana:refresh\",\n    \"folderId\": \"schema:isPartOf\",\n    \"datasource\": \"schema:provider\",\n    \"query\": \"grafana:query\",\n    \"time\": \"schema:temporalCoverage\",\n    \"annotations\": \"schema:comment\",\n    \"labels\": \"schema:keywords\",\n    \"orgId\": \"schema:memberOf\"\
  \n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/json-ld/tableaux-de-bord-context.jsonld
tags:
- Dashboards
- Business Intelligence
- Analytics
- Data Visualization
- Monitoring
- Grafana
- Metabase
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: cyclr-cyclr-openapi.yml
  format: yaml
  label: Cyclr API
  slug: api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/openapi/cyclr-cyclr-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cyclr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/json-ld/cyclr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cyclr from Cyclr.
layout: jsonld
name: Cyclr Context
namespaces:
- prefix: cyclr
  uri: https://cyclr.com/ns/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Connector
  type: ''
- container: ''
  name: InstalledConnector
  type: ''
- container: ''
  name: Template
  type: ''
- container: ''
  name: Cycle
  type: ''
- container: ''
  name: Step
  type: ''
property_count: 6
provider_name: Cyclr
provider_slug: cyclr
slug: cyclr-context
source_filename: cyclr-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cyclr\": \"https://cyclr.com/ns/\",\n    \"Account\": {\n      \"@id\": \"cyclr:Account\",\n      \"@context\": {\n        \"Id\": \"cyclr:accountId\",\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"ApiId\": \"cyclr:apiId\",\n        \"AudienceCount\": \"cyclr:audienceCount\",\n        \"CreatedDate\": \"schema:dateCreated\",\n        \"Connectors\": \"cyclr:hasInstalledConnector\"\n      }\n    },\n    \"Connector\": {\n      \"@id\": \"cyclr:Connector\",\n      \"@context\": {\n        \"Id\": \"cyclr:connectorId\",\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Status\": \"cyclr:status\",\n        \"Version\": \"schema:version\",\n        \"Icon\": \"schema:image\",\n        \"AuthType\": \"cyclr:authenticationType\"\n      }\n    },\n    \"InstalledConnector\": {\n      \"@id\": \"cyclr:InstalledConnector\"\
  ,\n      \"@context\": {\n        \"Id\": \"cyclr:installedConnectorId\",\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"ConnectorId\": \"cyclr:connectorId\",\n        \"Authenticated\": \"cyclr:isAuthenticated\",\n        \"Status\": \"cyclr:status\"\n      }\n    },\n    \"Template\": {\n      \"@id\": \"cyclr:Template\",\n      \"@context\": {\n        \"Id\": \"cyclr:templateId\",\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Connectors\": \"cyclr:usesConnector\",\n        \"Tags\": \"schema:keywords\"\n      }\n    },\n    \"Cycle\": {\n      \"@id\": \"cyclr:Cycle\",\n      \"@context\": {\n        \"Id\": \"cyclr:cycleId\",\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Status\": \"cyclr:status\",\n        \"CreatedDate\": \"schema:dateCreated\",\n        \"LastRunDate\": \"cyclr:lastRunDate\",\n        \"Connectors\": \"cyclr:usesInstalledConnector\"\
  ,\n        \"Steps\": \"cyclr:hasStep\"\n      }\n    },\n    \"Step\": {\n      \"@id\": \"cyclr:Step\",\n      \"@context\": {\n        \"Id\": \"cyclr:stepId\",\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"ConnectorId\": \"cyclr:connectorId\",\n        \"MethodId\": \"cyclr:methodId\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cyclr/refs/heads/main/json-ld/cyclr-context.jsonld
tags:
- Connectors
- Custom Connectors
- Data Synchronization
- Embedded iPaaS
- Embedded SaaS Integration
- Embedded UI
- Integration Platform
- Integrations
- Marketplace
- OAuth 2.0
- REST API
- SaaS
- Templates
- Webhooks
- White Label
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---

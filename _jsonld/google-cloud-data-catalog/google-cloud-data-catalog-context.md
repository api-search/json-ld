---
api_specs:
- filename: google-cloud-data-catalog-openapi.yml
  format: yaml
  label: Google Cloud Data Catalog API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-data-catalog/refs/heads/main/openapi/google-cloud-data-catalog-openapi.yml
class_count: 12
classes:
- Entry
- EntryGroup
- TagTemplate
- name
- description
- displayName
- type
- linkedResource
- fullyQualifiedName
- schema
- integratedSystem
- userSpecifiedSystem
context_file: json-ld/google-cloud-data-catalog-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-data-catalog/refs/heads/main/json-ld/google-cloud-data-catalog-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Data Catalog from Google Cloud Data Catalog.
layout: jsonld
name: Google Cloud Data Catalog Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/data-catalog/docs/reference/rest/v1/projects.locations.entryGroups.entries#
properties:
- container: ''
  name: sourceSystemTimestamps
  type: ''
property_count: 1
provider_name: Google Cloud Data Catalog
provider_slug: google-cloud-data-catalog
slug: google-cloud-data-catalog-context
source_filename: google-cloud-data-catalog-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/data-catalog/docs/reference/rest/v1/projects.locations.entryGroups.entries#\",\n    \"Entry\": \"gcloud:Entry\",\n    \"EntryGroup\": \"gcloud:EntryGroup\",\n    \"TagTemplate\": \"gcloud:TagTemplate\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"displayName\": \"schema:alternateName\",\n    \"type\": \"schema:additionalType\",\n    \"linkedResource\": \"schema:url\",\n    \"fullyQualifiedName\": \"schema:identifier\",\n    \"schema\": \"schema:schemaVersion\",\n    \"integratedSystem\": \"schema:sourceOrganization\",\n    \"userSpecifiedSystem\": \"schema:provider\",\n    \"sourceSystemTimestamps\": {\n      \"@id\": \"schema:TemporalCoverage\",\n      \"@context\": {\n        \"createTime\": \"schema:dateCreated\",\n        \"updateTime\": \"schema:dateModified\",\n        \"expireTime\": \"schema:expires\"\n      }\n    }\n \
  \ }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-data-catalog/refs/heads/main/json-ld/google-cloud-data-catalog-context.jsonld
tags:
- Data Catalog
- Data Governance
- Google Cloud
- Metadata
- JSON-LD
- Linked Data
- Semantic Web
---

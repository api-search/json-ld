---
api_specs:
- filename: cycloid-api-openapi.yml
  format: yaml
  label: Cycloid HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/openapi/cycloid-api-openapi.yml
class_count: 20
classes:
- Organization
- Project
- Environment
- Stack
- StackForm
- Pipeline
- InfrastructureResource
- Credential
- ConfigRepository
- CloudCostDashboard
- id
- type
- canonical
- name
- members
- teams
- environments
- ref
- author
- version
context_file: json-ld/cycloid-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/json-ld/cycloid-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cycloid from Cycloid.
layout: jsonld
name: Cycloid Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cycloid
  uri: https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/vocabulary/cycloid-vocabulary.yml#
properties: []
property_count: 0
provider_name: Cycloid
provider_slug: cycloid
slug: cycloid-context
source_filename: cycloid-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/vocabulary/cycloid-vocabulary.yml#\",\n    \"schema\": \"https://schema.org/\",\n    \"cycloid\": \"https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/vocabulary/cycloid-vocabulary.yml#\",\n    \"Organization\": \"cycloid:Organization\",\n    \"Project\": \"cycloid:Project\",\n    \"Environment\": \"cycloid:Environment\",\n    \"Stack\": \"cycloid:Stack\",\n    \"StackForm\": \"cycloid:StackForm\",\n    \"Pipeline\": \"cycloid:Pipeline\",\n    \"InfrastructureResource\": \"cycloid:InfrastructureResource\",\n    \"Credential\": \"cycloid:Credential\",\n    \"ConfigRepository\": \"cycloid:ConfigRepository\",\n    \"CloudCostDashboard\": \"cycloid:CloudCostDashboard\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"canonical\": \"cycloid:canonical\",\n    \"name\": \"schema:name\",\n    \"members\": \"cycloid:members\"\
  ,\n    \"teams\": \"cycloid:teams\",\n    \"environments\": \"cycloid:environments\",\n    \"ref\": \"cycloid:ref\",\n    \"author\": \"schema:author\",\n    \"version\": \"schema:version\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cycloid/refs/heads/main/json-ld/cycloid-context.jsonld
tags:
- Asset Inventory
- CI/CD
- Cloud Cost Management
- Cloud Management
- Developer Experience
- DevOps
- FinOps
- GitOps
- GreenOps
- Infrastructure as Code
- Internal Developer Platform
- Internal Developer Portal
- Multi-Cloud
- Platform Engineering
- RBAC
- Self-Service
- Service Catalog
- StackForms
- Terraform
- JSON-LD
- Linked Data
- Semantic Web
---

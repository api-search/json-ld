---
api_specs:
- filename: rely-openapi.yml
  format: yaml
  label: Rely.io Public API
  slug: public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rely/refs/heads/main/openapi/rely-openapi.yml
class_count: 7
classes:
- SoftwareApplication
- Organization
- CreativeWork
- name
- description
- url
- identifier
context_file: json-ld/rely-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rely/refs/heads/main/json-ld/rely-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rely from Rely.io.
layout: jsonld
name: Rely Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rely
  uri: https://api-evangelist.github.io/rely/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Blueprint
  type: reference
- container: ''
  name: CatalogEntity
  type: reference
- container: ''
  name: Scorecard
  type: reference
- container: ''
  name: ScorecardRule
  type: reference
- container: ''
  name: SelfServiceAction
  type: reference
- container: ''
  name: Automation
  type: reference
- container: ''
  name: blueprintId
  type: string
- container: ''
  name: entityId
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: relations
  type: reference
- container: ''
  name: scorecardLevel
  type: string
- container: ''
  name: invocationMethod
  type: string
- container: ''
  name: triggerCondition
  type: reference
property_count: 13
provider_name: Rely.io
provider_slug: rely
slug: rely-context
source_filename: rely-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rely\": \"https://api-evangelist.github.io/rely/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"Organization\": \"schema:Organization\",\n    \"CreativeWork\": \"schema:CreativeWork\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n\n    \"Blueprint\": {\n      \"@id\": \"rely:Blueprint\",\n      \"@type\": \"@id\",\n      \"comment\": \"A schema defining the structure and properties of a catalog entity type\"\n    },\n    \"CatalogEntity\": {\n      \"@id\": \"rely:CatalogEntity\",\n      \"@type\": \"@id\",\n      \"comment\": \"An instance of a blueprint in the Rely.io software catalog (service, team, deployment, etc.)\"\n    },\n    \"Scorecard\": {\n      \"@id\": \"rely:Scorecard\",\n\
  \      \"@type\": \"@id\",\n      \"comment\": \"An engineering scorecard that evaluates services against defined standards\"\n    },\n    \"ScorecardRule\": {\n      \"@id\": \"rely:ScorecardRule\",\n      \"@type\": \"@id\",\n      \"comment\": \"An individual rule within a scorecard at a specific maturity level\"\n    },\n    \"SelfServiceAction\": {\n      \"@id\": \"rely:SelfServiceAction\",\n      \"@type\": \"@id\",\n      \"comment\": \"A developer self-service action for scaffolding, provisioning, or deploying\"\n    },\n    \"Automation\": {\n      \"@id\": \"rely:Automation\",\n      \"@type\": \"@id\",\n      \"comment\": \"An automation rule triggered by catalog entity changes or external events\"\n    },\n    \"blueprintId\": {\n      \"@id\": \"rely:blueprintId\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"The identifier of the blueprint type\"\n    },\n    \"entityId\": {\n      \"@id\": \"rely:entityId\",\n      \"@type\": \"xsd:string\",\n      \"comment\"\
  : \"The unique identifier of a catalog entity\"\n    },\n    \"properties\": {\n      \"@id\": \"rely:properties\",\n      \"@type\": \"@id\",\n      \"comment\": \"The property values of a catalog entity or schema definitions of a blueprint\"\n    },\n    \"relations\": {\n      \"@id\": \"rely:relations\",\n      \"@type\": \"@id\",\n      \"comment\": \"Relations linking an entity or blueprint to other entities or blueprints\"\n    },\n    \"scorecardLevel\": {\n      \"@id\": \"rely:scorecardLevel\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"The maturity level of a scorecard rule (bronze, silver, gold)\"\n    },\n    \"invocationMethod\": {\n      \"@id\": \"rely:invocationMethod\",\n      \"@type\": \"xsd:string\",\n      \"comment\": \"The execution method for a self-service action (webhook, GitHub Actions, GitLab, etc.)\"\n    },\n    \"triggerCondition\": {\n      \"@id\": \"rely:triggerCondition\",\n      \"@type\": \"@id\",\n      \"comment\": \"The condition that\
  \ triggers an automation rule\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rely/refs/heads/main/json-ld/rely-context.jsonld
tags:
- Developer Experience
- Internal Developer Portal
- Platform Engineering
- Software Catalog
- Service Catalog
- Engineering Scorecards
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: turbonomic-rest-api-openapi.yml
  format: yaml
  label: Turbonomic REST API
  slug: turbonomic-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/turbonomic/refs/heads/main/openapi/turbonomic-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/turbonomic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/turbonomic/refs/heads/main/json-ld/turbonomic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Turbonomic from IBM Turbonomic.
layout: jsonld
name: Turbonomic Context
namespaces:
- prefix: turbo
  uri: https://www.ibm.com/products/turbonomic/vocabulary#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Entity
  type: ''
- container: ''
  name: Action
  type: ''
- container: ''
  name: Market
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Target
  type: ''
- container: ''
  name: StatSnapshot
  type: ''
property_count: 7
provider_name: IBM Turbonomic
provider_slug: turbonomic
slug: turbonomic-context
source_filename: turbonomic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"turbo\": \"https://www.ibm.com/products/turbonomic/vocabulary#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Entity\": {\n      \"@id\": \"turbo:Entity\",\n      \"@context\": {\n        \"uuid\": \"turbo:entityId\",\n        \"displayName\": \"schema:name\",\n        \"className\": \"turbo:entityType\",\n        \"environmentType\": \"turbo:environmentType\",\n        \"state\": \"turbo:operationalState\",\n        \"tags\": \"schema:additionalProperty\",\n        \"severityBreakdown\": \"turbo:severityBreakdown\",\n        \"providers\": {\n          \"@id\": \"turbo:hasProvider\",\n          \"@container\": \"@set\"\n        },\n        \"consumers\": {\n          \"@id\": \"turbo:hasConsumer\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Action\": {\n      \"@id\": \"turbo:Action\"\
  ,\n      \"@context\": {\n        \"uuid\": \"turbo:actionId\",\n        \"actionType\": \"turbo:actionType\",\n        \"actionMode\": \"turbo:executionMode\",\n        \"details\": \"schema:description\",\n        \"importance\": \"turbo:importanceScore\",\n        \"severity\": \"turbo:severityLevel\",\n        \"state\": \"turbo:actionState\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"target\": \"turbo:targetEntity\",\n        \"currentEntity\": \"turbo:currentProvider\",\n        \"newEntity\": \"turbo:recommendedProvider\",\n        \"risk\": \"turbo:riskAssessment\",\n        \"savings\": \"turbo:estimatedSavings\"\n      }\n    },\n\n    \"Market\": {\n      \"@id\": \"turbo:Market\",\n      \"@context\": {\n        \"uuid\": \"turbo:marketId\",\n        \"displayName\": \"schema:name\",\n        \"state\": \"turbo:marketState\",\n        \"type\": \"turbo:marketType\"\n      }\n    },\n\n \
  \   \"Group\": {\n      \"@id\": \"turbo:Group\",\n      \"@context\": {\n        \"uuid\": \"turbo:groupId\",\n        \"displayName\": \"schema:name\",\n        \"groupType\": \"turbo:groupEntityType\",\n        \"isStatic\": \"turbo:isStaticGroup\",\n        \"memberCount\": \"turbo:memberCount\"\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"turbo:Policy\",\n      \"@context\": {\n        \"uuid\": \"turbo:policyId\",\n        \"displayName\": \"schema:name\",\n        \"policyType\": \"turbo:policyType\",\n        \"enabled\": \"turbo:isEnabled\"\n      }\n    },\n\n    \"Target\": {\n      \"@id\": \"turbo:Target\",\n      \"@context\": {\n        \"uuid\": \"turbo:targetId\",\n        \"displayName\": \"schema:name\",\n        \"type\": \"turbo:targetType\",\n        \"status\": \"turbo:validationStatus\",\n        \"lastValidated\": {\n          \"@id\": \"turbo:lastValidated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"StatSnapshot\"\
  : {\n      \"@id\": \"turbo:StatSnapshot\",\n      \"@context\": {\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"statistics\": \"turbo:metrics\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/turbonomic/refs/heads/main/json-ld/turbonomic-context.jsonld
tags:
- Application Resource Management
- Cloud Cost Optimization
- Cloud Management
- Hybrid Cloud
- IBM
- Kubernetes
- Multi-Cloud
- Workload Optimization
- JSON-LD
- Linked Data
- Semantic Web
---

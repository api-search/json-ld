---
api_specs:
- filename: cloud-deploy-api-openapi.yml
  format: yaml
  label: Cloud Deploy API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-deploy/refs/heads/main/openapi/cloud-deploy-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-deploy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-deploy/refs/heads/main/json-ld/google-cloud-deploy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Deploy from Google Cloud Deploy.
layout: jsonld
name: Google Cloud Deploy Context
namespaces:
- prefix: cd
  uri: https://cloud.google.com/deploy/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DeliveryPipeline
  type: ''
- container: ''
  name: Target
  type: ''
- container: ''
  name: Release
  type: ''
- container: ''
  name: Rollout
  type: ''
property_count: 4
provider_name: Google Cloud Deploy
provider_slug: google-cloud-deploy
slug: google-cloud-deploy-context
source_filename: google-cloud-deploy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cd\": \"https://cloud.google.com/deploy/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DeliveryPipeline\": {\n      \"@id\": \"cd:DeliveryPipeline\",\n      \"@context\": {\n        \"name\": \"cd:pipelineName\",\n        \"description\": \"schema:description\",\n        \"serialPipeline\": \"cd:serialPipeline\",\n        \"labels\": \"cd:labels\",\n        \"annotations\": \"cd:annotations\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Target\": {\n      \"@id\": \"cd:Target\",\n      \"@context\": {\n        \"name\": \"cd:targetName\",\n        \"description\": \"schema:description\",\n      \
  \  \"requireApproval\": \"cd:requireApproval\",\n        \"gke\": \"cd:gkeTarget\",\n        \"run\": \"cd:runTarget\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Release\": {\n      \"@id\": \"cd:Release\",\n      \"@context\": {\n        \"name\": \"cd:releaseName\",\n        \"description\": \"schema:description\",\n        \"skaffoldConfigUri\": \"cd:skaffoldConfigUri\",\n        \"buildArtifacts\": \"cd:buildArtifacts\",\n        \"renderState\": \"cd:renderState\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Rollout\": {\n      \"@id\": \"cd:Rollout\",\n      \"@context\": {\n        \"name\": \"cd:rolloutName\",\n        \"description\": \"schema:description\",\n\
  \        \"targetId\": \"cd:targetId\",\n        \"approvalState\": \"cd:approvalState\",\n        \"state\": \"cd:rolloutState\",\n        \"deployStartTime\": {\n          \"@id\": \"cd:deployStartTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deployEndTime\": {\n          \"@id\": \"cd:deployEndTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-deploy/refs/heads/main/json-ld/google-cloud-deploy-context.jsonld
tags:
- Continuous Delivery
- Deployment
- DevOps
- Kubernetes
- Pipeline
- Release Management
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: jetic-platform-openapi.yml
  format: yaml
  label: Jetic Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetic/refs/heads/main/openapi/jetic-platform-openapi.yml
class_count: 0
classes: []
context_file: json-ld/jetic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jetic/refs/heads/main/json-ld/jetic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jetic from Jetic.
layout: jsonld
name: Jetic Context
namespaces:
- prefix: jetic
  uri: https://docs.jetic.io/docs/
properties:
- container: ''
  name: Integration
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: ApiSpecification
  type: ''
property_count: 5
provider_name: Jetic
provider_slug: jetic
slug: jetic-context
source_filename: jetic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"jetic\": \"https://docs.jetic.io/docs/\",\n    \"Integration\": {\n      \"@id\": \"jetic:integrations\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"status\": \"https://schema.org/status\",\n        \"routes\": {\n          \"@id\": \"jetic:routes\",\n          \"@type\": \"@id\"\n        },\n        \"gitRepository\": \"https://schema.org/codeRepository\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Route\": {\n      \"@id\": \"jetic:routes\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"from\": \"https://schema.org/source\",\n        \"to\": \"https://schema.org/target\",\n        \"processors\": \"https://schema.org/softwareRequirements\"\n      }\n    },\n    \"Deployment\"\
  : {\n      \"@id\": \"jetic:deployments\",\n      \"@context\": {\n        \"integrationId\": {\n          \"@id\": \"jetic:integrations\",\n          \"@type\": \"@id\"\n        },\n        \"integrationName\": \"https://schema.org/name\",\n        \"clusterId\": {\n          \"@id\": \"jetic:clusters\",\n          \"@type\": \"@id\"\n        },\n        \"clusterName\": \"https://schema.org/name\",\n        \"status\": \"https://schema.org/status\",\n        \"environment\": \"https://schema.org/category\",\n        \"version\": \"https://schema.org/softwareVersion\",\n        \"deployedAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Cluster\": {\n      \"@id\": \"jetic:clusters\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"provider\": \"https://schema.org/provider\",\n        \"region\": \"https://schema.org/locationCreated\",\n        \"camelBridgeStatus\": \"https://schema.org/status\"\
  ,\n        \"kubernetesVersion\": \"https://schema.org/softwareVersion\",\n        \"deploymentCount\": \"https://schema.org/quantity\",\n        \"createdAt\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"ApiSpecification\": {\n      \"@id\": \"jetic:api-specifications\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"version\": \"https://schema.org/softwareVersion\",\n        \"openApiVersion\": \"https://schema.org/schemaVersion\",\n        \"paths\": \"https://schema.org/quantity\",\n        \"integrationId\": {\n          \"@id\": \"jetic:integrations\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jetic/refs/heads/main/json-ld/jetic-context.jsonld
tags:
- Apache Camel
- Integrations
- iPaaS
- Pro-Code API Composition
- JSON-LD
- Linked Data
- Semantic Web
---

---
class_count: 0
classes: []
context_file: json-ld/databricks-asset-bundles-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/databricks-asset-bundles/refs/heads/main/json-ld/databricks-asset-bundles-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Databricks Asset Bundles from Databricks Asset Bundles.
layout: jsonld
name: Databricks Asset Bundles Context
namespaces:
- prefix: dab
  uri: https://docs.databricks.com/aws/en/dev-tools/bundles/
properties:
- container: ''
  name: Bundle
  type: ''
- container: ''
  name: Target
  type: ''
- container: ''
  name: Resource
  type: ''
- container: ''
  name: Variable
  type: ''
- container: ''
  name: Artifact
  type: ''
- container: ''
  name: Permission
  type: ''
- container: ''
  name: RunAs
  type: ''
- container: ''
  name: Workspace
  type: ''
property_count: 8
provider_name: Databricks Asset Bundles
provider_slug: databricks-asset-bundles
slug: databricks-asset-bundles-context
source_filename: databricks-asset-bundles-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dab\": \"https://docs.databricks.com/aws/en/dev-tools/bundles/\",\n    \"Bundle\": {\n      \"@id\": \"dab:reference\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"uuid\": \"https://schema.org/identifier\",\n        \"databricks_cli_version\": \"https://schema.org/softwareVersion\",\n        \"git\": \"https://schema.org/codeRepository\"\n      }\n    },\n    \"Target\": {\n      \"@id\": \"dab:deployment-modes\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"mode\": \"https://schema.org/applicationCategory\",\n        \"default\": \"https://schema.org/option\",\n        \"workspace\": \"https://schema.org/serviceUrl\"\n      }\n    },\n    \"Resource\": {\n      \"@id\": \"dab:resources\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"permissions\"\
  : \"https://schema.org/accessibilityControl\"\n      }\n    },\n    \"Variable\": {\n      \"@id\": \"dab:variables\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"default\": \"https://schema.org/defaultValue\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"lookup\": \"https://schema.org/identifier\"\n      }\n    },\n    \"Artifact\": {\n      \"@id\": \"dab:library-dependencies\",\n      \"@context\": {\n        \"type\": \"https://schema.org/encodingFormat\",\n        \"build\": \"https://schema.org/instrument\",\n        \"path\": \"https://schema.org/url\",\n        \"executable\": \"https://schema.org/applicationCategory\"\n      }\n    },\n    \"Permission\": {\n      \"@id\": \"dab:permissions\",\n      \"@context\": {\n        \"level\": \"https://schema.org/permissions\",\n        \"user_name\": \"https://schema.org/identifier\",\n        \"group_name\": \"\
  https://schema.org/identifier\",\n        \"service_principal_name\": \"https://schema.org/identifier\"\n      }\n    },\n    \"RunAs\": {\n      \"@id\": \"dab:reference\",\n      \"@context\": {\n        \"user_name\": \"https://schema.org/agent\",\n        \"service_principal_name\": \"https://schema.org/agent\"\n      }\n    },\n    \"Workspace\": {\n      \"@id\": \"dab:authentication\",\n      \"@context\": {\n        \"host\": \"https://schema.org/url\",\n        \"profile\": \"https://schema.org/identifier\",\n        \"root_path\": \"https://schema.org/contentLocation\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/databricks-asset-bundles/refs/heads/main/json-ld/databricks-asset-bundles-context.jsonld
tags:
- CI/CD
- Data Engineering
- Databricks
- Deployment
- Infrastructure as Code
- Jobs
- Machine Learning
- MLOps
- Pipelines
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---

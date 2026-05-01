---
api_specs:
- filename: datahub-openapi-openapi.yml
  format: yaml
  label: DataHub OpenAPI
  slug: datahub-openapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/openapi/datahub-openapi-openapi.yml
- filename: datahub-actions-asyncapi.yml
  format: yaml
  label: DataHub Actions Framework
  slug: datahub-actions-framework
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/asyncapi/datahub-actions-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/datahub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/json-ld/datahub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Datahub from DataHub.
layout: jsonld
name: Datahub Context
namespaces:
- prefix: datahub
  uri: https://docs.datahub.com/docs/
properties:
- container: ''
  name: Entity
  type: ''
- container: ''
  name: Aspect
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Chart
  type: ''
- container: ''
  name: Dashboard
  type: ''
- container: ''
  name: DataFlow
  type: ''
- container: ''
  name: DataJob
  type: ''
- container: ''
  name: MetadataChangeLog
  type: ''
- container: ''
  name: GlossaryTerm
  type: ''
property_count: 9
provider_name: DataHub
provider_slug: datahub
slug: datahub-context
source_filename: datahub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"datahub\": \"https://docs.datahub.com/docs/\",\n    \"Entity\": {\n      \"@id\": \"datahub:what-is-datahub/datahub-concepts\",\n      \"@context\": {\n        \"urn\": \"https://schema.org/identifier\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"platform\": \"https://schema.org/sourceOrganization\",\n        \"owners\": \"https://schema.org/owner\",\n        \"tags\": \"https://schema.org/keywords\"\n      }\n    },\n    \"Aspect\": {\n      \"@id\": \"datahub:what-is-datahub/datahub-concepts\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"version\": \"https://schema.org/version\",\n        \"value\": \"https://schema.org/value\",\n        \"createdOn\": \"https://schema.org/dateCreated\",\n        \"modifiedOn\": \"https://schema.org/dateModified\"\
  \n      }\n    },\n    \"Dataset\": {\n      \"@id\": \"https://schema.org/Dataset\",\n      \"@context\": {\n        \"urn\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"platform\": \"https://schema.org/sourceOrganization\",\n        \"schema\": \"https://schema.org/variableMeasured\"\n      }\n    },\n    \"Chart\": {\n      \"@id\": \"datahub:generated/metamodel/entities/chart\",\n      \"@context\": {\n        \"urn\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"url\": \"https://schema.org/url\"\n      }\n    },\n    \"Dashboard\": {\n      \"@id\": \"datahub:generated/metamodel/entities/dashboard\",\n      \"@context\": {\n        \"urn\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"url\": \"https://schema.org/url\"\n      }\n    },\n    \"DataFlow\": {\n      \"@id\": \"datahub:generated/metamodel/entities/dataflow\"\
  ,\n      \"@context\": {\n        \"urn\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"orchestrator\": \"https://schema.org/sourceOrganization\"\n      }\n    },\n    \"DataJob\": {\n      \"@id\": \"datahub:generated/metamodel/entities/datajob\",\n      \"@context\": {\n        \"urn\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"type\": \"https://schema.org/additionalType\"\n      }\n    },\n    \"MetadataChangeLog\": {\n      \"@id\": \"datahub:advanced/mcp-mcl\",\n      \"@context\": {\n        \"entityType\": \"https://schema.org/additionalType\",\n        \"entityUrn\": \"https://schema.org/identifier\",\n        \"aspectName\": \"https://schema.org/name\",\n        \"changeType\": \"https://schema.org/Action\",\n        \"created\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"GlossaryTerm\": {\n      \"@id\": \"datahub:glossary/business-glossary\",\n      \"@context\"\
  : {\n        \"urn\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"definition\": \"https://schema.org/description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/datahub/refs/heads/main/json-ld/datahub-context.jsonld
tags:
- Data Catalog
- Data Discovery
- Data Governance
- Data Lineage
- Metadata
- JSON-LD
- Linked Data
- Semantic Web
---

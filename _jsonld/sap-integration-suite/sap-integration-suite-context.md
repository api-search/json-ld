---
api_specs:
- filename: sap-integration-suite-cloud-integration-openapi.yml
  format: yaml
  label: SAP Cloud Integration API
  slug: sap-cloud-integration
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/openapi/sap-integration-suite-cloud-integration-openapi.yml
- filename: sap-integration-suite-api-management-openapi.yml
  format: yaml
  label: SAP API Management API
  slug: sap-api-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/openapi/sap-integration-suite-api-management-openapi.yml
class_count: 20
classes:
- id
- name
- description
- version
- vendor
- status
- creationDate
- modifiedDate
- deployedBy
- deployedOn
- sender
- receiver
- integrationFlowName
- correlationId
- basePath
- targetEndpoint
- isDeployed
- quota
- quotaInterval
- quotaTimeUnit
context_file: json-ld/sap-integration-suite-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/json-ld/sap-integration-suite-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Integration Suite from SAP Integration Suite.
layout: jsonld
name: Sap Integration Suite Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: sap
  uri: https://api.sap.com/vocabulary/
- prefix: iflow
  uri: https://help.sap.com/docs/integration-suite/terms/
properties:
- container: ''
  name: IntegrationPackage
  type: reference
- container: ''
  name: IntegrationFlow
  type: reference
- container: ''
  name: RuntimeArtifact
  type: reference
- container: ''
  name: MessageProcessingLog
  type: reference
- container: ''
  name: APIProxy
  type: reference
- container: ''
  name: APIProduct
  type: reference
property_count: 6
provider_name: SAP Integration Suite
provider_slug: sap-integration-suite
slug: sap-integration-suite-context
source_filename: sap-integration-suite-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"sap\": \"https://api.sap.com/vocabulary/\",\n    \"iflow\": \"https://help.sap.com/docs/integration-suite/terms/\",\n\n    \"IntegrationPackage\": {\n      \"@id\": \"sap:IntegrationPackage\",\n      \"@type\": \"@id\"\n    },\n    \"IntegrationFlow\": {\n      \"@id\": \"sap:IntegrationFlow\",\n      \"@type\": \"@id\"\n    },\n    \"RuntimeArtifact\": {\n      \"@id\": \"sap:RuntimeArtifact\",\n      \"@type\": \"@id\"\n    },\n    \"MessageProcessingLog\": {\n      \"@id\": \"sap:MessageProcessingLog\",\n      \"@type\": \"@id\"\n    },\n    \"APIProxy\": {\n      \"@id\": \"sap:APIProxy\",\n      \"@type\": \"@id\"\n    },\n    \"APIProduct\": {\n      \"@id\": \"sap:APIProduct\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\"\
  : \"schema:version\",\n    \"vendor\": \"schema:provider\",\n    \"status\": \"sap:status\",\n    \"creationDate\": \"schema:dateCreated\",\n    \"modifiedDate\": \"schema:dateModified\",\n    \"deployedBy\": \"sap:deployedBy\",\n    \"deployedOn\": \"sap:deployedOn\",\n    \"sender\": \"sap:sender\",\n    \"receiver\": \"sap:receiver\",\n    \"integrationFlowName\": \"sap:integrationFlowName\",\n    \"correlationId\": \"sap:correlationId\",\n    \"basePath\": \"sap:basePath\",\n    \"targetEndpoint\": \"sap:targetEndpoint\",\n    \"isDeployed\": \"sap:isDeployed\",\n    \"quota\": \"sap:quota\",\n    \"quotaInterval\": \"sap:quotaInterval\",\n    \"quotaTimeUnit\": \"sap:quotaTimeUnit\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-integration-suite/refs/heads/main/json-ld/sap-integration-suite-context.jsonld
tags:
- API Management
- Cloud Integration
- Enterprise Integration
- Event Mesh
- iPaaS
- SAP
- SAP BTP
- JSON-LD
- Linked Data
- Semantic Web
---

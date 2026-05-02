---
api_specs:
- filename: microsoft-bicep-deployments-openapi.yml
  format: yaml
  label: Bicep Deployments REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-bicep/refs/heads/main/openapi/microsoft-bicep-deployments-openapi.yml
- filename: microsoft-bicep-template-specs-openapi.yml
  format: yaml
  label: Bicep Template Specs REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-bicep/refs/heads/main/openapi/microsoft-bicep-template-specs-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-bicep-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-bicep/refs/heads/main/json-ld/microsoft-bicep-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Bicep from Microsoft Bicep.
layout: jsonld
name: Microsoft Bicep Context
namespaces:
- prefix: bicep
  uri: https://management.azure.com/schemas/microsoft-bicep/
- prefix: azure
  uri: https://management.azure.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: TemplateSpec
  type: ''
- container: ''
  name: TemplateSpecVersion
  type: ''
- container: ''
  name: TemplateLink
  type: ''
- container: ''
  name: DeploymentParameter
  type: ''
- container: ''
  name: ResourceReference
  type: ''
- container: ''
  name: Provider
  type: ''
- container: ''
  name: WhatIfChange
  type: ''
- container: ''
  name: DeploymentIdentity
  type: ''
property_count: 9
provider_name: Microsoft Bicep
provider_slug: microsoft-bicep
slug: microsoft-bicep-context
source_filename: microsoft-bicep-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bicep\": \"https://management.azure.com/schemas/microsoft-bicep/\",\n    \"azure\": \"https://management.azure.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Deployment\": {\n      \"@id\": \"bicep:Deployment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"location\": \"schema:location\",\n        \"mode\": \"bicep:deploymentMode\",\n        \"provisioningState\": \"bicep:provisioningState\",\n        \"templateHash\": \"bicep:templateHash\",\n        \"correlationId\": \"bicep:correlationId\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": \"bicep:duration\",\n        \"outputs\": \"bicep:outputs\",\n        \"outputResources\": \"bicep:outputResources\"\n      }\n    },\n\n    \"TemplateSpec\"\
  : {\n      \"@id\": \"bicep:TemplateSpec\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"displayName\": \"bicep:displayName\",\n        \"location\": \"schema:location\",\n        \"metadata\": \"bicep:metadata\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TemplateSpecVersion\": {\n      \"@id\": \"bicep:TemplateSpecVersion\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"mainTemplate\": \"bicep:mainTemplate\",\n        \"linkedTemplates\": \"bicep:linkedTemplates\",\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeModified\": {\n    \
  \      \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TemplateLink\": {\n      \"@id\": \"bicep:TemplateLink\",\n      \"@context\": {\n        \"uri\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"id\": \"bicep:templateSpecId\",\n        \"contentVersion\": \"schema:version\",\n        \"relativePath\": \"bicep:relativePath\"\n      }\n    },\n\n    \"DeploymentParameter\": {\n      \"@id\": \"bicep:DeploymentParameter\",\n      \"@context\": {\n        \"value\": \"bicep:parameterValue\",\n        \"expression\": \"bicep:parameterExpression\",\n        \"reference\": \"bicep:keyVaultReference\"\n      }\n    },\n\n    \"ResourceReference\": {\n      \"@id\": \"bicep:ResourceReference\",\n      \"@context\": {\n        \"id\": \"bicep:resourceId\",\n        \"resourceType\": \"bicep:resourceType\",\n        \"apiVersion\": \"bicep:apiVersion\"\n      }\n    },\n\n    \"Provider\"\
  : {\n      \"@id\": \"bicep:Provider\",\n      \"@context\": {\n        \"namespace\": \"bicep:providerNamespace\",\n        \"resourceTypes\": \"bicep:providerResourceTypes\"\n      }\n    },\n\n    \"WhatIfChange\": {\n      \"@id\": \"bicep:WhatIfChange\",\n      \"@context\": {\n        \"resourceId\": \"bicep:resourceId\",\n        \"changeType\": \"bicep:changeType\",\n        \"before\": \"bicep:beforeState\",\n        \"after\": \"bicep:afterState\",\n        \"delta\": \"bicep:propertyChanges\"\n      }\n    },\n\n    \"DeploymentIdentity\": {\n      \"@id\": \"bicep:DeploymentIdentity\",\n      \"@context\": {\n        \"type\": \"bicep:identityType\",\n        \"userAssignedIdentities\": \"bicep:userAssignedIdentities\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-bicep/refs/heads/main/json-ld/microsoft-bicep-context.jsonld
tags:
- ARM Templates
- Azure
- Cloud
- Deployment
- DevOps
- Infrastructure as Code
- JSON-LD
- Linked Data
- Semantic Web
---

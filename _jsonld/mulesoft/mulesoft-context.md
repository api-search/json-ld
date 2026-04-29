---
api_specs:
- filename: mulesoft-anypoint-platform-openapi.yml
  format: yaml
  label: MuleSoft Anypoint Platform Management API
  slug: mulesoft-anypoint-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mulesoft/refs/heads/main/openapi/mulesoft-anypoint-platform-openapi.yml
class_count: 0
classes: []
context_file: json-ld/mulesoft-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mulesoft/refs/heads/main/json-ld/mulesoft-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Mulesoft from MuleSoft.
layout: jsonld
name: Mulesoft Context
namespaces:
- prefix: mulesoft
  uri: https://anypoint.mulesoft.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: MuleVersion
  type: ''
- container: ''
  name: WorkerConfig
  type: ''
- container: ''
  name: WorkerType
  type: ''
- container: ''
  name: Entitlements
  type: ''
property_count: 7
provider_name: MuleSoft
provider_slug: mulesoft
slug: mulesoft-context
source_filename: mulesoft-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mulesoft\": \"https://anypoint.mulesoft.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"mulesoft:Organization\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"mulesoft:organizationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"ownerId\": {\n          \"@id\": \"mulesoft:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"clientId\": {\n          \"@id\": \"mulesoft:clientId\",\n  \
  \        \"@type\": \"xsd:string\"\n        },\n        \"isFederated\": {\n          \"@id\": \"mulesoft:isFederated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isMaster\": {\n          \"@id\": \"mulesoft:isMaster\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"domain\": {\n          \"@id\": \"mulesoft:domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mfaRequired\": {\n          \"@id\": \"mulesoft:mfaRequired\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"parentOrganizationIds\": {\n          \"@id\": \"mulesoft:parentOrganizationIds\",\n          \"@container\": \"@set\"\n        },\n        \"subOrganizationIds\": {\n          \"@id\": \"mulesoft:subOrganizationIds\",\n          \"@container\": \"@set\"\n        },\n        \"environments\": {\n          \"@id\": \"mulesoft:hasEnvironment\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"mulesoft:Environment\"\
  ,\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"mulesoft:environmentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"organizationId\": {\n          \"@id\": \"mulesoft:belongsToOrganization\",\n          \"@type\": \"@id\"\n        },\n        \"type\": {\n          \"@id\": \"mulesoft:environmentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isProduction\": {\n          \"@id\": \"mulesoft:isProduction\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"clientId\": {\n          \"@id\": \"mulesoft:clientId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n   \
  \ \"Application\": {\n      \"@id\": \"mulesoft:Application\",\n      \"@context\": {\n        \"domain\": {\n          \"@id\": \"mulesoft:applicationDomain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullDomain\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"mulesoft:deploymentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"organizationId\": {\n          \"@id\": \"mulesoft:belongsToOrganization\",\n          \"@type\": \"@id\"\n        },\n        \"environmentId\": {\n          \"@id\": \"mulesoft:deployedToEnvironment\",\n          \"@type\": \"@id\"\n        },\n        \"region\": {\n          \"@id\": \"mulesoft:deploymentRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"muleVersion\": {\n          \"@id\": \"mulesoft:muleVersion\"\
  \n        },\n        \"workers\": {\n          \"@id\": \"mulesoft:workerConfig\"\n        },\n        \"deploymentTarget\": {\n          \"@id\": \"mulesoft:deploymentTarget\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fileName\": {\n          \"@id\": \"mulesoft:fileName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"monitoringEnabled\": {\n          \"@id\": \"mulesoft:monitoringEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"staticIPsEnabled\": {\n          \"@id\": \"mulesoft:staticIPsEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"persistentQueues\": {\n          \"@id\": \"mulesoft:persistentQueues\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"loggingNgEnabled\": {\n          \"@id\": \"mulesoft:loggingNgEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"lastUpdateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n   \
  \     },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MuleVersion\": {\n      \"@id\": \"mulesoft:MuleVersion\",\n      \"@context\": {\n        \"version\": {\n          \"@id\": \"schema:softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updateId\": {\n          \"@id\": \"mulesoft:updateId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endOfSupportDate\": {\n          \"@id\": \"mulesoft:endOfSupportDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"WorkerConfig\": {\n      \"@id\": \"mulesoft:WorkerConfig\",\n      \"@context\": {\n        \"amount\": {\n          \"@id\": \"mulesoft:workerCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"type\": {\n          \"@id\": \"mulesoft:workerType\"\n        }\n      }\n    },\n\n    \"WorkerType\": {\n      \"@id\": \"mulesoft:WorkerType\",\n      \"\
  @context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"weight\": {\n          \"@id\": \"mulesoft:vCoreWeight\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"cpu\": {\n          \"@id\": \"mulesoft:cpuAllocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"memory\": {\n          \"@id\": \"mulesoft:memoryAllocation\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Entitlements\": {\n      \"@id\": \"mulesoft:Entitlements\",\n      \"@context\": {\n        \"createEnvironments\": {\n          \"@id\": \"mulesoft:canCreateEnvironments\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"globalDeployment\": {\n          \"@id\": \"mulesoft:globalDeployment\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createSubOrgs\": {\n          \"@id\": \"mulesoft:canCreateSubOrgs\",\n          \"@type\": \"xsd:boolean\"\n        },\n   \
  \     \"vCoresProduction\": {\n          \"@id\": \"mulesoft:vCoresProduction\"\n        },\n        \"vCoresSandbox\": {\n          \"@id\": \"mulesoft:vCoresSandbox\"\n        },\n        \"vCoresDesign\": {\n          \"@id\": \"mulesoft:vCoresDesign\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mulesoft/refs/heads/main/json-ld/mulesoft-context.jsonld
tags:
- API Gateway
- API Management
- Enterprise
- Integration
- JSON-LD
- Linked Data
- Semantic Web
---

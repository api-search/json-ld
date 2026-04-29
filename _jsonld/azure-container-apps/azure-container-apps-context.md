---
class_count: 13
classes:
- ContainerApp
- Configuration
- Template
- Container
- Revision
- ManagedEnvironment
- Job
- JobExecution
- JobExecutionTemplate
- Secret
- ContainerAppSecret
- AuthConfig
- name
context_file: json-ld/azure-container-apps-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/json-ld/azure-container-apps-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Container Apps from Azure Container Apps.
layout: jsonld
name: Azure Container Apps Context
namespaces:
- prefix: aca
  uri: https://azure.microsoft.com/container-apps/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: tags
  type: reference
- container: ''
  name: identity
  type: reference
- container: ''
  name: properties
  type: reference
- container: set
  name: secrets
  type: string
- container: ''
  name: activeRevisionsMode
  type: string
- container: ''
  name: ingress
  type: reference
- container: set
  name: registries
  type: string
- container: ''
  name: dapr
  type: reference
- container: ''
  name: maxInactiveRevisions
  type: integer
- container: ''
  name: revisionSuffix
  type: string
- container: ''
  name: terminationGracePeriodSeconds
  type: integer
- container: set
  name: initContainers
  type: string
- container: set
  name: containers
  type: string
- container: ''
  name: scale
  type: reference
- container: set
  name: volumes
  type: string
- container: set
  name: serviceBinds
  type: string
- container: ''
  name: image
  type: string
- container: set
  name: command
  type: string
- container: set
  name: args
  type: string
- container: set
  name: env
  type: string
- container: ''
  name: resources
  type: reference
- container: set
  name: volumeMounts
  type: string
- container: set
  name: probes
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: keyVaultUrl
  type: string
property_count: 28
provider_name: Azure Container Apps
provider_slug: azure-container-apps
slug: azure-container-apps-context
source_filename: azure-container-apps-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aca\": \"https://azure.microsoft.com/container-apps/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ContainerApp\": \"aca:ContainerApp\",\n    \"Configuration\": \"aca:Configuration\",\n    \"Template\": \"aca:Template\",\n    \"Container\": \"aca:Container\",\n    \"Revision\": \"aca:Revision\",\n    \"ManagedEnvironment\": \"aca:ManagedEnvironment\",\n    \"Job\": \"aca:Job\",\n    \"JobExecution\": \"aca:JobExecution\",\n    \"JobExecutionTemplate\": \"aca:JobExecutionTemplate\",\n    \"Secret\": \"aca:Secret\",\n    \"ContainerAppSecret\": \"aca:ContainerAppSecret\",\n    \"AuthConfig\": \"aca:AuthConfig\",\n    \"id\": {\n      \"@id\": \"aca:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"type\": {\n      \"@id\": \"aca:type\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"location\": {\n      \"@id\": \"aca:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aca:tags\",\n      \"@type\": \"@id\"\n    },\n    \"identity\": {\n      \"@id\": \"aca:identity\",\n      \"@type\": \"@id\"\n    },\n    \"properties\": {\n      \"@id\": \"aca:properties\",\n      \"@type\": \"@id\"\n    },\n    \"secrets\": {\n      \"@id\": \"aca:secrets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeRevisionsMode\": {\n      \"@id\": \"aca:activeRevisionsMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ingress\": {\n      \"@id\": \"aca:ingress\",\n      \"@type\": \"@id\"\n    },\n    \"registries\": {\n      \"@id\": \"aca:registries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dapr\": {\n      \"@id\": \"aca:dapr\",\n      \"@type\": \"@id\"\n    },\n    \"maxInactiveRevisions\": {\n      \"@id\": \"aca:maxInactiveRevisions\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"revisionSuffix\": {\n      \"@id\": \"aca:revisionSuffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminationGracePeriodSeconds\": {\n      \"@id\": \"aca:terminationGracePeriodSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"initContainers\": {\n      \"@id\": \"aca:initContainers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containers\": {\n      \"@id\": \"aca:containers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scale\": {\n      \"@id\": \"aca:scale\",\n      \"@type\": \"@id\"\n    },\n    \"volumes\": {\n      \"@id\": \"aca:volumes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceBinds\": {\n      \"@id\": \"aca:serviceBinds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"aca:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"command\"\
  : {\n      \"@id\": \"aca:command\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"args\": {\n      \"@id\": \"aca:args\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"env\": {\n      \"@id\": \"aca:env\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resources\": {\n      \"@id\": \"aca:resources\",\n      \"@type\": \"@id\"\n    },\n    \"volumeMounts\": {\n      \"@id\": \"aca:volumeMounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"probes\": {\n      \"@id\": \"aca:probes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aca:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyVaultUrl\": {\n      \"@id\": \"aca:keyVaultUrl\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-container-apps/refs/heads/main/json-ld/azure-container-apps-context.jsonld
tags:
- Azure
- Containers
- Dapr
- Kubernetes
- Microservices
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---

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

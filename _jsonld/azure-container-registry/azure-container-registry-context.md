---
class_count: 22
classes:
- Actor
- CallbackConfig
- EncryptionProperty
- Event
- EventContent
- EventInfo
- EventListResult
- EventRequestMessage
- EventResponseMessage
- IPRule
- IdentityProperties
- ImportImageParameters
- ImportSource
- ImportSourceCredentials
- KeyVaultProperties
- NetworkRuleSet
- OperationDefinition
- OperationDisplayDefinition
- OperationMetricSpecificationDefinition
- OperationPropertiesDefinition
- name
- description
context_file: json-ld/azure-container-registry-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-container-registry/refs/heads/main/json-ld/azure-container-registry-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Container Registry from Azure Container Registry.
layout: jsonld
name: Azure Container Registry Context
namespaces:
- prefix: azurecontainerregistry
  uri: https://azure.microsoft.com/azure-container-registry/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: customHeaders
  type: reference
- container: ''
  name: serviceUri
  type: string
- container: ''
  name: keyVaultProperties
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: eventRequestMessage
  type: string
- container: ''
  name: eventResponseMessage
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: actor
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: request
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: nextLink
  type: string
- container: set
  name: value
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: headers
  type: reference
- container: ''
  name: method
  type: string
- container: ''
  name: requestUri
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: reasonPhrase
  type: string
- container: ''
  name: statusCode
  type: string
- container: ''
  name: principalId
  type: string
- container: ''
  name: tenantId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: userAssignedIdentities
  type: reference
- container: ''
  name: mode
  type: string
- container: set
  name: targetTags
  type: string
- container: set
  name: untaggedTargetRepositories
  type: string
- container: ''
  name: credentials
  type: string
- container: ''
  name: registryUri
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: sourceImage
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: identity
  type: string
- container: ''
  name: keyIdentifier
  type: string
- container: ''
  name: defaultAction
  type: string
- container: set
  name: ipRules
  type: string
- container: set
  name: virtualNetworkRules
  type: string
- container: ''
  name: display
  type: string
- container: ''
  name: origin
  type: string
- container: ''
  name: properties
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: aggregationType
  type: string
- container: ''
  name: displayDescription
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: internalMetricName
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: serviceSpecification
  type: string
property_count: 52
provider_name: Azure Container Registry
provider_slug: azure-container-registry
slug: azure-container-registry-context
tags:
- Azure
- Container Images
- Containers
- Docker
- Registry
- JSON-LD
- Linked Data
- Semantic Web
---

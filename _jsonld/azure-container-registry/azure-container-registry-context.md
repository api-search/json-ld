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
source_filename: azure-container-registry-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azurecontainerregistry\": \"https://azure.microsoft.com/azure-container-registry/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Actor\": \"azurecontainerregistry:Actor\",\n    \"CallbackConfig\": \"azurecontainerregistry:CallbackConfig\",\n    \"EncryptionProperty\": \"azurecontainerregistry:EncryptionProperty\",\n    \"Event\": \"azurecontainerregistry:Event\",\n    \"EventContent\": \"azurecontainerregistry:EventContent\",\n    \"EventInfo\": \"azurecontainerregistry:EventInfo\",\n    \"EventListResult\": \"azurecontainerregistry:EventListResult\",\n    \"EventRequestMessage\": \"azurecontainerregistry:EventRequestMessage\",\n    \"EventResponseMessage\": \"azurecontainerregistry:EventResponseMessage\",\n    \"IPRule\": \"azurecontainerregistry:IPRule\",\n    \"IdentityProperties\": \"azurecontainerregistry:IdentityProperties\"\
  ,\n    \"ImportImageParameters\": \"azurecontainerregistry:ImportImageParameters\",\n    \"ImportSource\": \"azurecontainerregistry:ImportSource\",\n    \"ImportSourceCredentials\": \"azurecontainerregistry:ImportSourceCredentials\",\n    \"KeyVaultProperties\": \"azurecontainerregistry:KeyVaultProperties\",\n    \"NetworkRuleSet\": \"azurecontainerregistry:NetworkRuleSet\",\n    \"OperationDefinition\": \"azurecontainerregistry:OperationDefinition\",\n    \"OperationDisplayDefinition\": \"azurecontainerregistry:OperationDisplayDefinition\",\n    \"OperationMetricSpecificationDefinition\": \"azurecontainerregistry:OperationMetricSpecificationDefinition\",\n    \"OperationPropertiesDefinition\": \"azurecontainerregistry:OperationPropertiesDefinition\",\n    \"name\": \"schema:name\",\n    \"customHeaders\": {\n      \"@id\": \"azurecontainerregistry:customHeaders\",\n      \"@type\": \"@id\"\n    },\n    \"serviceUri\": {\n      \"@id\": \"azurecontainerregistry:serviceUri\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"keyVaultProperties\": {\n      \"@id\": \"azurecontainerregistry:keyVaultProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"azurecontainerregistry:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventRequestMessage\": {\n      \"@id\": \"azurecontainerregistry:eventRequestMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventResponseMessage\": {\n      \"@id\": \"azurecontainerregistry:eventResponseMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"azurecontainerregistry:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actor\": {\n      \"@id\": \"azurecontainerregistry:actor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"azurecontainerregistry:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"request\": {\n      \"@id\": \"azurecontainerregistry:request\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\"\
  : {\n      \"@id\": \"azurecontainerregistry:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target\": {\n      \"@id\": \"azurecontainerregistry:target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"azurecontainerregistry:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azurecontainerregistry:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azurecontainerregistry:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"azurecontainerregistry:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"azurecontainerregistry:headers\",\n      \"@type\": \"@id\"\n    },\n    \"method\": {\n      \"@id\": \"azurecontainerregistry:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestUri\": {\n      \"@id\": \"azurecontainerregistry:requestUri\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"azurecontainerregistry:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reasonPhrase\": {\n      \"@id\": \"azurecontainerregistry:reasonPhrase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"azurecontainerregistry:statusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalId\": {\n      \"@id\": \"azurecontainerregistry:principalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"azurecontainerregistry:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azurecontainerregistry:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAssignedIdentities\": {\n      \"@id\": \"azurecontainerregistry:userAssignedIdentities\",\n      \"@type\": \"@id\"\n    },\n    \"mode\": {\n      \"@id\": \"azurecontainerregistry:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetTags\": {\n      \"@id\"\
  : \"azurecontainerregistry:targetTags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"untaggedTargetRepositories\": {\n      \"@id\": \"azurecontainerregistry:untaggedTargetRepositories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"credentials\": {\n      \"@id\": \"azurecontainerregistry:credentials\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registryUri\": {\n      \"@id\": \"azurecontainerregistry:registryUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceId\": {\n      \"@id\": \"azurecontainerregistry:resourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceImage\": {\n      \"@id\": \"azurecontainerregistry:sourceImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"azurecontainerregistry:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"azurecontainerregistry:username\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"identity\": {\n      \"@id\": \"azurecontainerregistry:identity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyIdentifier\": {\n      \"@id\": \"azurecontainerregistry:keyIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultAction\": {\n      \"@id\": \"azurecontainerregistry:defaultAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipRules\": {\n      \"@id\": \"azurecontainerregistry:ipRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualNetworkRules\": {\n      \"@id\": \"azurecontainerregistry:virtualNetworkRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"display\": {\n      \"@id\": \"azurecontainerregistry:display\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"azurecontainerregistry:origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"azurecontainerregistry:properties\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"operation\": {\n      \"@id\": \"azurecontainerregistry:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"azurecontainerregistry:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"azurecontainerregistry:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregationType\": {\n      \"@id\": \"azurecontainerregistry:aggregationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayDescription\": {\n      \"@id\": \"azurecontainerregistry:displayDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"azurecontainerregistry:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internalMetricName\": {\n      \"@id\": \"azurecontainerregistry:internalMetricName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"azurecontainerregistry:unit\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceSpecification\": {\n      \"@id\": \"azurecontainerregistry:serviceSpecification\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-container-registry/refs/heads/main/json-ld/azure-container-registry-context.jsonld
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

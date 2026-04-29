---
class_count: 0
classes: []
context_file: json-ld/microsoft-azure-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure/refs/heads/main/json-ld/microsoft-azure-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Azure from Microsoft Azure.
layout: jsonld
name: Microsoft Azure Context
namespaces:
- prefix: azure
  uri: https://schema.api.gov/microsoft-azure/
- prefix: arm
  uri: https://schema.api.gov/microsoft-azure/resource-manager/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: Resource
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: ResourceGroup
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: ManagedCluster
  type: ''
- container: ''
  name: AgentPool
  type: ''
- container: ''
  name: KeyVaultKey
  type: ''
- container: ''
  name: KeyVaultSecret
  type: ''
- container: ''
  name: CognitiveServicesAccount
  type: ''
- container: ''
  name: CosmosDBDatabase
  type: ''
- container: ''
  name: CosmosDBContainer
  type: ''
- container: ''
  name: BlobContainer
  type: ''
- container: ''
  name: Blob
  type: ''
- container: ''
  name: ContainerImage
  type: ''
- container: ''
  name: OpenAIDeployment
  type: ''
- container: ''
  name: ChatCompletion
  type: ''
- container: ''
  name: ManagedServiceIdentity
  type: ''
- container: ''
  name: Sku
  type: ''
- container: ''
  name: provisioningState
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: resourceGroup
  type: string
- container: ''
  name: subscriptionId
  type: string
- container: ''
  name: tenantId
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: lastModifiedAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: url
  type: reference
property_count: 28
provider_name: Microsoft Azure
provider_slug: microsoft-azure
slug: microsoft-azure-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.api.gov/microsoft-azure/\",\n    \"azure\": \"https://schema.api.gov/microsoft-azure/\",\n    \"arm\": \"https://schema.api.gov/microsoft-azure/resource-manager/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"Resource\": {\n      \"@id\": \"azure:Resource\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azure:resourceId\",\n          \"@type\": \"@id\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"azure:resourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"azure:location\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"tags\": {\n          \"@id\": \"azure:tags\",\n          \"@container\": \"@index\"\n        },\n        \"managedBy\": {\n          \"@id\": \"azure:managedBy\",\n          \"@type\": \"@id\"\n        },\n        \"kind\": {\n          \"@id\": \"azure:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"azure:etag\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"azure:Subscription\",\n      \"@context\": {\n        \"subscriptionId\": {\n          \"@id\": \"azure:subscriptionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tenantId\": {\n          \"@id\": \"azure:tenantId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"azure:subscriptionState\",\n   \
  \       \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ResourceGroup\": {\n      \"@id\": \"azure:ResourceGroup\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azure:resourceGroupId\",\n          \"@type\": \"@id\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"azure:location\",\n          \"@type\": \"xsd:string\"\n        },\n        \"provisioningState\": {\n          \"@id\": \"azure:provisioningState\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"arm:Deployment\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"provisioningState\": {\n          \"@id\": \"azure:provisioningState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timestamp\": {\n          \"@id\":\
  \ \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"mode\": {\n          \"@id\": \"arm:deploymentMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"arm:correlationId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ManagedCluster\": {\n      \"@id\": \"azure:ManagedCluster\",\n      \"@context\": {\n        \"kubernetesVersion\": {\n          \"@id\": \"azure:kubernetesVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dnsPrefix\": {\n          \"@id\": \"azure:dnsPrefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fqdn\": {\n          \"@id\": \"azure:fqdn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"agentPoolProfiles\": {\n          \"@id\": \"azure:agentPoolProfiles\",\n          \"@container\": \"@set\"\n        },\n        \"networkProfile\": {\n          \"@id\": \"azure:networkProfile\"\n        }\n      }\n\
  \    },\n\n    \"AgentPool\": {\n      \"@id\": \"azure:AgentPool\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"count\": {\n          \"@id\": \"azure:nodeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"vmSize\": {\n          \"@id\": \"azure:vmSize\",\n          \"@type\": \"xsd:string\"\n        },\n        \"osType\": {\n          \"@id\": \"azure:osType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mode\": {\n          \"@id\": \"azure:agentPoolMode\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"KeyVaultKey\": {\n      \"@id\": \"azure:KeyVaultKey\",\n      \"@context\": {\n        \"kid\": {\n          \"@id\": \"azure:keyIdentifier\",\n          \"@type\": \"@id\"\n        },\n        \"kty\": {\n          \"@id\": \"azure:keyType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"key_ops\": {\n        \
  \  \"@id\": \"azure:keyOperations\",\n          \"@container\": \"@set\"\n        },\n        \"enabled\": {\n          \"@id\": \"azure:enabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"KeyVaultSecret\": {\n      \"@id\": \"azure:KeyVaultSecret\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azure:secretIdentifier\",\n          \"@type\": \"@id\"\n        },\n        \"contentType\": {\n          \"@id\": \"azure:contentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabled\": {\n          \"@id\": \"azure:enabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"CognitiveServicesAccount\": {\n      \"@id\": \"azure:CognitiveServicesAccount\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"azure:cognitiveServiceKind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endpoint\": {\n          \"@id\": \"azure:endpoint\",\n          \"@type\": \"@id\"\n \
  \       },\n        \"customSubDomainName\": {\n          \"@id\": \"azure:customSubDomainName\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"CosmosDBDatabase\": {\n      \"@id\": \"azure:CosmosDBDatabase\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azure:databaseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"_rid\": {\n          \"@id\": \"azure:resourceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"_ts\": {\n          \"@id\": \"azure:timestamp\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"CosmosDBContainer\": {\n      \"@id\": \"azure:CosmosDBContainer\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azure:containerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"partitionKey\": {\n          \"@id\": \"azure:partitionKey\"\n        },\n        \"indexingPolicy\": {\n          \"@id\": \"azure:indexingPolicy\"\n        },\n     \
  \   \"defaultTtl\": {\n          \"@id\": \"azure:defaultTtl\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"BlobContainer\": {\n      \"@id\": \"azure:BlobContainer\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publicAccess\": {\n          \"@id\": \"azure:publicAccess\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Blob\": {\n      \"@id\": \"azure:Blob\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentType\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentLength\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"blobType\": {\n          \"@id\": \"azure:blobType\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"accessTier\": {\n          \"@id\": \"azure:accessTier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ContainerImage\": {\n      \"@id\": \"azure:ContainerImage\",\n      \"@context\": {\n        \"repository\": {\n          \"@id\": \"azure:repository\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tag\": {\n          \"@id\": \"azure:tag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"digest\": {\n          \"@id\": \"azure:digest\",\n          \"@type\": \"xsd:string\"\n        },\n        \"architecture\": {\n          \"@id\": \"azure:architecture\",\n          \"@type\": \"xsd:string\"\n        },\n        \"os\": {\n          \"@id\": \"azure:operatingSystem\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"OpenAIDeployment\": {\n      \"@id\": \"azure:OpenAIDeployment\",\n      \"@context\": {\n        \"model\": {\n          \"@id\": \"azure:modelId\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"azure:deploymentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scaleSettings\": {\n          \"@id\": \"azure:scaleSettings\"\n        }\n      }\n    },\n\n    \"ChatCompletion\": {\n      \"@id\": \"azure:ChatCompletion\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azure:completionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"model\": {\n          \"@id\": \"azure:modelId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"choices\": {\n          \"@id\": \"azure:choices\",\n          \"@container\": \"@list\"\n        },\n        \"usage\": {\n          \"@id\": \"azure:tokenUsage\"\n        }\n      }\n    },\n\n    \"ManagedServiceIdentity\": {\n      \"@id\": \"azure:ManagedServiceIdentity\",\n      \"@context\": {\n        \"principalId\": {\n          \"@id\": \"azure:principalId\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"tenantId\": {\n          \"@id\": \"azure:tenantId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"azure:identityType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Sku\": {\n      \"@id\": \"azure:Sku\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"azure:skuName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tier\": {\n          \"@id\": \"azure:skuTier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"capacity\": {\n          \"@id\": \"azure:skuCapacity\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"provisioningState\": {\n      \"@id\": \"azure:provisioningState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azure:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceGroup\": {\n      \"@id\": \"azure:resourceGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  subscriptionId\": {\n      \"@id\": \"azure:subscriptionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"azure:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedAt\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure/refs/heads/main/json-ld/microsoft-azure-context.jsonld
tags:
- API Management
- Cloud
- Cloud Computing
- Enterprise
- Infrastructure as a Service
- Platform as a Service
- T1
- JSON-LD
- Linked Data
- Semantic Web
---

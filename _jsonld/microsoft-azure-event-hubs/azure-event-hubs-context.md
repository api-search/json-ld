---
api_specs:
- filename: resource-manager
  format: yaml
  label: Azure Event Hubs REST API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/resource-manager
- filename: data-plane
  format: yaml
  label: Azure Event Hubs Data Plane API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/data-plane
- filename: azure-event-hubs-messaging-asyncapi.yml
  format: yaml
  label: Azure Event Hubs Messaging API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-event-hubs/refs/heads/main/asyncapi/azure-event-hubs-messaging-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/azure-event-hubs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-event-hubs/refs/heads/main/json-ld/azure-event-hubs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Event Hubs from Azure Event Hubs.
layout: jsonld
name: Azure Event Hubs Context
namespaces:
- prefix: azure
  uri: https://schema.azure.com/
- prefix: eh
  uri: https://schema.azure.com/eventhub/
- prefix: arm
  uri: https://schema.azure.com/arm/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: id
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: location
  type: string
- container: index
  name: tags
  type: ''
- container: ''
  name: EHNamespace
  type: ''
- container: ''
  name: EventHub
  type: ''
- container: ''
  name: ConsumerGroup
  type: ''
- container: ''
  name: EventData
  type: ''
- container: ''
  name: SchemaGroup
  type: ''
- container: ''
  name: CaptureDescription
  type: ''
- container: ''
  name: DisasterRecoveryConfig
  type: ''
- container: ''
  name: Sku
  type: ''
- container: ''
  name: AuthorizationRule
  type: ''
- container: ''
  name: NetworkRuleSet
  type: ''
property_count: 15
provider_name: Azure Event Hubs
provider_slug: microsoft-azure-event-hubs
slug: azure-event-hubs-context
source_filename: azure-event-hubs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.azure.com/eventhub/\",\n    \"azure\": \"https://schema.azure.com/\",\n    \"eh\": \"https://schema.azure.com/eventhub/\",\n    \"arm\": \"https://schema.azure.com/arm/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"id\": {\n      \"@id\": \"arm:resourceId\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"arm:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azure:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"azure:tags\",\n      \"@container\": \"@index\"\n    },\n    \"EHNamespace\": {\n      \"@id\": \"eh:Namespace\",\n      \"@context\": {\n        \"sku\": {\n          \"@id\": \"eh:sku\",\n          \"@type\": \"\
  @id\"\n        },\n        \"identity\": {\n          \"@id\": \"azure:identity\",\n          \"@type\": \"@id\"\n        },\n        \"provisioningState\": {\n          \"@id\": \"azure:provisioningState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"eh:namespaceStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"serviceBusEndpoint\": {\n          \"@id\": \"eh:serviceBusEndpoint\",\n          \"@type\": \"@id\"\n        },\n        \"clusterArmId\": {\n          \"@id\": \"eh:clusterArmId\",\n          \"@type\": \"@id\"\n        },\n        \"isAutoInflateEnabled\": {\n          \"@id\": \"eh:isAutoInflateEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"maximumThroughputUnits\"\
  : {\n          \"@id\": \"eh:maximumThroughputUnits\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"kafkaEnabled\": {\n          \"@id\": \"eh:kafkaEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"zoneRedundant\": {\n          \"@id\": \"eh:zoneRedundant\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"disableLocalAuth\": {\n          \"@id\": \"eh:disableLocalAuth\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"minimumTlsVersion\": {\n          \"@id\": \"eh:minimumTlsVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publicNetworkAccess\": {\n          \"@id\": \"eh:publicNetworkAccess\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"EventHub\": {\n      \"@id\": \"eh:EventHub\",\n      \"@context\": {\n        \"partitionIds\": {\n          \"@id\": \"eh:partitionIds\",\n          \"@container\": \"@list\"\n        },\n        \"messageRetentionInDays\": {\n          \"\
  @id\": \"eh:messageRetentionInDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"partitionCount\": {\n          \"@id\": \"eh:partitionCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"eh:eventHubStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userMetadata\": {\n          \"@id\": \"eh:userMetadata\",\n          \"@type\": \"xsd:string\"\n        },\n        \"captureDescription\": {\n          \"@id\": \"eh:captureDescription\",\n          \"@type\": \"@id\"\n        },\n        \"retentionDescription\": {\n          \"@id\": \"eh:retentionDescription\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"ConsumerGroup\": {\n      \"@id\": \"eh:ConsumerGroup\",\n      \"@context\": {\n        \"userMetadata\": {\n          \"@id\": \"eh:userMetadata\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"EventData\": {\n      \"@id\": \"eh:EventData\",\n      \"\
  @context\": {\n        \"body\": {\n          \"@id\": \"eh:eventBody\"\n        },\n        \"properties\": {\n          \"@id\": \"eh:eventProperties\",\n          \"@container\": \"@index\"\n        },\n        \"systemProperties\": {\n          \"@id\": \"eh:systemProperties\",\n          \"@type\": \"@id\"\n        },\n        \"sequenceNumber\": {\n          \"@id\": \"eh:sequenceNumber\",\n          \"@type\": \"xsd:long\"\n        },\n        \"offset\": {\n          \"@id\": \"eh:offset\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enqueuedTimeUtc\": {\n          \"@id\": \"eh:enqueuedTimeUtc\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"partitionKey\": {\n          \"@id\": \"eh:partitionKey\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SchemaGroup\": {\n      \"@id\": \"eh:SchemaGroup\",\n      \"@context\": {\n        \"schemaCompatibility\": {\n          \"@id\": \"eh:schemaCompatibility\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"schemaType\": {\n          \"@id\": \"eh:schemaType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"groupProperties\": {\n          \"@id\": \"eh:groupProperties\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n    \"CaptureDescription\": {\n      \"@id\": \"eh:CaptureDescription\",\n      \"@context\": {\n        \"enabled\": {\n          \"@id\": \"eh:captureEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"encoding\": {\n          \"@id\": \"eh:captureEncoding\",\n          \"@type\": \"xsd:string\"\n        },\n        \"intervalInSeconds\": {\n          \"@id\": \"eh:captureIntervalInSeconds\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sizeLimitInBytes\": {\n          \"@id\": \"eh:captureSizeLimitInBytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"destination\": {\n          \"@id\": \"eh:captureDestination\",\n          \"@type\": \"@id\"\n   \
  \     }\n      }\n    },\n    \"DisasterRecoveryConfig\": {\n      \"@id\": \"eh:DisasterRecoveryConfig\",\n      \"@context\": {\n        \"partnerNamespace\": {\n          \"@id\": \"eh:partnerNamespace\",\n          \"@type\": \"@id\"\n        },\n        \"role\": {\n          \"@id\": \"eh:drRole\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pendingReplicationOperationsCount\": {\n          \"@id\": \"eh:pendingReplicationOperationsCount\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n    \"Sku\": {\n      \"@id\": \"eh:Sku\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"eh:skuName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tier\": {\n          \"@id\": \"eh:skuTier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"capacity\": {\n          \"@id\": \"eh:skuCapacity\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"AuthorizationRule\": {\n      \"@id\": \"eh:AuthorizationRule\"\
  ,\n      \"@context\": {\n        \"rights\": {\n          \"@id\": \"eh:accessRights\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n    \"NetworkRuleSet\": {\n      \"@id\": \"eh:NetworkRuleSet\",\n      \"@context\": {\n        \"defaultAction\": {\n          \"@id\": \"eh:defaultAction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"trustedServiceAccessEnabled\": {\n          \"@id\": \"eh:trustedServiceAccessEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"virtualNetworkRules\": {\n          \"@id\": \"eh:virtualNetworkRules\",\n          \"@container\": \"@list\"\n        },\n        \"ipRules\": {\n          \"@id\": \"eh:ipRules\",\n          \"@container\": \"@list\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-event-hubs/refs/heads/main/json-ld/azure-event-hubs-context.jsonld
tags:
- Big Data
- Event Streaming
- IoT
- Message Ingestion
- Real-Time Processing
- JSON-LD
- Linked Data
- Semantic Web
---

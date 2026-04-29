---
api_specs:
- filename: amazon-iot-twinmaker-openapi-original.yml
  format: yaml
  label: AWS IoT TwinMaker API
  slug: aws-iot-twinmaker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-twinmaker/refs/heads/main/openapi/amazon-iot-twinmaker-openapi-original.yml
class_count: 102
classes:
- BatchPutPropertyError
- BatchPutPropertyErrorEntry
- BatchPutPropertyValuesRequest
- BatchPutPropertyValuesResponse
- BundleInformation
- ColumnDescription
- ComponentPropertyGroupRequest
- ComponentPropertyGroupRequests
- ComponentPropertyGroupResponse
- ComponentPropertyGroupResponses
- ComponentRequest
- ComponentResponse
- ComponentTypeSummary
- ComponentUpdateRequest
- ComponentUpdatesMapRequest
- ComponentsMap
- ComponentsMapRequest
- Configuration
- CreateComponentTypeRequest
- CreateComponentTypeResponse
- CreateEntityRequest
- CreateEntityResponse
- CreateSceneRequest
- CreateSceneResponse
- CreateSyncJobRequest
- CreateSyncJobResponse
- CreateWorkspaceRequest
- CreateWorkspaceResponse
- DataConnector
- DataType
- DataValue
- DataValueMap
- DeleteComponentTypeRequest
- DeleteComponentTypeResponse
- DeleteEntityRequest
- DeleteEntityResponse
- DeleteSceneRequest
- DeleteSceneResponse
- DeleteSyncJobRequest
- DeleteSyncJobResponse
- DeleteWorkspaceRequest
- DeleteWorkspaceResponse
- EntityPropertyReference
- EntitySummary
- ErrorDetails
- ExecuteQueryRequest
- ExecuteQueryResponse
- ExternalIdProperty
- FunctionRequest
- FunctionResponse
- FunctionsRequest
- FunctionsResponse
- GeneratedSceneMetadataMap
- GetComponentTypeRequest
- GetComponentTypeResponse
- GetEntityRequest
- GetEntityResponse
- GetPricingPlanRequest
- GetPricingPlanResponse
- GetPropertyValueHistoryRequest
- GetPropertyValueHistoryResponse
- GetPropertyValueRequest
- GetPropertyValueResponse
- GetSceneRequest
- GetSceneResponse
- GetSyncJobRequest
- GetSyncJobResponse
- GetWorkspaceRequest
- GetWorkspaceResponse
- InterpolationParameters
- LambdaFunction
- ListComponentTypesFilter
- ListComponentTypesRequest
- ListComponentTypesResponse
- ListEntitiesFilter
- ListEntitiesRequest
- ListEntitiesResponse
- ListScenesRequest
- ListScenesResponse
- ListSyncJobsRequest
- ListSyncJobsResponse
- ListSyncResourcesRequest
- ListSyncResourcesResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ListWorkspacesRequest
- ListWorkspacesResponse
- OrderBy
- ParentEntityUpdateRequest
- PricingPlan
- PropertyDefinitionRequest
- PropertyDefinitionResponse
- PropertyDefinitionsRequest
- PropertyDefinitionsResponse
- PropertyFilter
- PropertyGroupRequest
- PropertyGroupResponse
- PropertyGroupsRequest
- PropertyGroupsResponse
- PropertyLatestValue
- description
- name
context_file: json-ld/amazon-iot-twinmaker-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-twinmaker/refs/heads/main/json-ld/amazon-iot-twinmaker-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iot Twinmaker from Amazon IoT TwinMaker.
layout: jsonld
name: Amazon Iot Twinmaker Context
namespaces:
- prefix: amzn
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: allowedValues
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: billableEntityCount
  type: string
- container: ''
  name: booleanValue
  type: string
- container: ''
  name: bundleInformation
  type: string
- container: ''
  name: bundleNames
  type: string
- container: ''
  name: capabilities
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: columnDescriptions
  type: string
- container: ''
  name: componentName
  type: string
- container: ''
  name: componentTypeId
  type: string
- container: ''
  name: componentTypeName
  type: string
- container: ''
  name: componentTypeSummaries
  type: string
- container: ''
  name: componentUpdates
  type: string
- container: ''
  name: components
  type: string
- container: ''
  name: configuration
  type: string
- container: ''
  name: contentLocation
  type: string
- container: ''
  name: creationDateTime
  type: string
- container: ''
  name: currentPricingPlan
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: definedIn
  type: string
- container: ''
  name: definition
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: doubleValue
  type: string
- container: ''
  name: effectiveDateTime
  type: string
- container: ''
  name: endDateTime
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: entityId
  type: string
- container: ''
  name: entityName
  type: string
- container: ''
  name: entityPropertyReference
  type: string
- container: ''
  name: entitySummaries
  type: string
- container: ''
  name: entries
  type: string
- container: ''
  name: entry
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorEntries
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: errors
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: extendsFrom
  type: string
- container: ''
  name: externalId
  type: string
- container: ''
  name: externalIdProperty
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: functions
  type: string
- container: ''
  name: generatedSceneMetadata
  type: string
- container: ''
  name: groupType
  type: string
- container: ''
  name: hasChildEntities
  type: string
- container: ''
  name: implementedBy
  type: string
- container: ''
  name: integerValue
  type: string
- container: ''
  name: interpolation
  type: string
- container: ''
  name: interpolationType
  type: string
- container: ''
  name: intervalInSeconds
  type: string
- container: ''
  name: isAbstract
  type: string
- container: ''
  name: isExternalId
  type: string
- container: ''
  name: isFinal
  type: string
- container: ''
  name: isImported
  type: string
- container: ''
  name: isInherited
  type: string
- container: ''
  name: isNative
  type: string
- container: ''
  name: isRequiredInEntity
  type: string
- container: ''
  name: isSchemaInitialized
  type: string
- container: ''
  name: isSingleton
  type: string
- container: ''
  name: isStoredExternally
  type: string
- container: ''
  name: isTimeSeries
  type: string
- container: ''
  name: lambda
  type: string
- container: ''
  name: listValue
  type: string
- container: ''
  name: longValue
  type: string
- container: ''
  name: mapValue
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: nestedType
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: order
  type: string
- container: ''
  name: orderBy
  type: string
- container: ''
  name: orderByTime
  type: string
- container: ''
  name: parentEntityId
  type: string
- container: ''
  name: parentEntityUpdate
  type: string
- container: ''
  name: pendingPricingPlan
  type: string
- container: ''
  name: pricingMode
  type: string
- container: ''
  name: pricingTier
  type: string
- container: ''
  name: properties
  type: string
- container: ''
  name: propertyDefinitions
  type: string
- container: ''
  name: propertyFilters
  type: string
- container: ''
  name: propertyGroupName
  type: string
- container: ''
  name: propertyGroupUpdates
  type: string
- container: ''
  name: propertyGroups
  type: string
- container: ''
  name: propertyName
  type: string
- container: ''
  name: propertyNames
  type: string
- container: ''
  name: propertyReference
  type: string
- container: ''
  name: propertyUpdates
  type: string
- container: ''
  name: propertyValue
  type: string
- container: ''
  name: propertyValues
  type: string
- container: ''
  name: queryStatement
  type: string
- container: ''
  name: relationship
  type: string
- container: ''
  name: relationshipType
  type: string
- container: ''
  name: relationshipValue
  type: string
- container: ''
  name: requiredProperties
  type: string
- container: ''
  name: resourceARN
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: rowData
  type: string
- container: ''
  name: rows
  type: string
- container: ''
  name: s3Location
  type: string
- container: ''
  name: sceneId
  type: string
- container: ''
  name: sceneMetadata
  type: string
- container: ''
  name: sceneSummaries
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: selectedProperties
  type: string
- container: ''
  name: startDateTime
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: stringValue
  type: string
- container: ''
  name: syncJobSummaries
  type: string
- container: ''
  name: syncResources
  type: string
- container: ''
  name: syncRole
  type: string
- container: ''
  name: syncSource
  type: string
- container: ''
  name: tabularConditions
  type: string
- container: ''
  name: tabularPropertyValues
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: targetComponentName
  type: string
- container: ''
  name: targetComponentTypeId
  type: string
- container: ''
  name: targetEntityId
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: unitOfMeasure
  type: string
- container: ''
  name: updateDateTime
  type: string
- container: ''
  name: updateReason
  type: string
- container: ''
  name: updateType
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: values
  type: string
- container: ''
  name: workspaceId
  type: string
- container: ''
  name: workspaceSummaries
  type: string
property_count: 137
provider_name: Amazon IoT TwinMaker
provider_slug: amazon-iot-twinmaker
slug: amazon-iot-twinmaker-context
source_filename: amazon-iot-twinmaker-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BatchPutPropertyError\": \"amzn:BatchPutPropertyError\",\n    \"BatchPutPropertyErrorEntry\": \"amzn:BatchPutPropertyErrorEntry\",\n    \"BatchPutPropertyValuesRequest\": \"amzn:BatchPutPropertyValuesRequest\",\n    \"BatchPutPropertyValuesResponse\": \"amzn:BatchPutPropertyValuesResponse\",\n    \"BundleInformation\": \"amzn:BundleInformation\",\n    \"ColumnDescription\": \"amzn:ColumnDescription\",\n    \"ComponentPropertyGroupRequest\": \"amzn:ComponentPropertyGroupRequest\",\n    \"ComponentPropertyGroupRequests\": \"amzn:ComponentPropertyGroupRequests\",\n    \"ComponentPropertyGroupResponse\": \"amzn:ComponentPropertyGroupResponse\",\n    \"ComponentPropertyGroupResponses\": \"amzn:ComponentPropertyGroupResponses\",\n    \"ComponentRequest\"\
  : \"amzn:ComponentRequest\",\n    \"ComponentResponse\": \"amzn:ComponentResponse\",\n    \"ComponentTypeSummary\": \"amzn:ComponentTypeSummary\",\n    \"ComponentUpdateRequest\": \"amzn:ComponentUpdateRequest\",\n    \"ComponentUpdatesMapRequest\": \"amzn:ComponentUpdatesMapRequest\",\n    \"ComponentsMap\": \"amzn:ComponentsMap\",\n    \"ComponentsMapRequest\": \"amzn:ComponentsMapRequest\",\n    \"Configuration\": \"amzn:Configuration\",\n    \"CreateComponentTypeRequest\": \"amzn:CreateComponentTypeRequest\",\n    \"CreateComponentTypeResponse\": \"amzn:CreateComponentTypeResponse\",\n    \"CreateEntityRequest\": \"amzn:CreateEntityRequest\",\n    \"CreateEntityResponse\": \"amzn:CreateEntityResponse\",\n    \"CreateSceneRequest\": \"amzn:CreateSceneRequest\",\n    \"CreateSceneResponse\": \"amzn:CreateSceneResponse\",\n    \"CreateSyncJobRequest\": \"amzn:CreateSyncJobRequest\",\n    \"CreateSyncJobResponse\": \"amzn:CreateSyncJobResponse\",\n    \"CreateWorkspaceRequest\": \"amzn:CreateWorkspaceRequest\"\
  ,\n    \"CreateWorkspaceResponse\": \"amzn:CreateWorkspaceResponse\",\n    \"DataConnector\": \"amzn:DataConnector\",\n    \"DataType\": \"amzn:DataType\",\n    \"DataValue\": \"amzn:DataValue\",\n    \"DataValueMap\": \"amzn:DataValueMap\",\n    \"DeleteComponentTypeRequest\": \"amzn:DeleteComponentTypeRequest\",\n    \"DeleteComponentTypeResponse\": \"amzn:DeleteComponentTypeResponse\",\n    \"DeleteEntityRequest\": \"amzn:DeleteEntityRequest\",\n    \"DeleteEntityResponse\": \"amzn:DeleteEntityResponse\",\n    \"DeleteSceneRequest\": \"amzn:DeleteSceneRequest\",\n    \"DeleteSceneResponse\": \"amzn:DeleteSceneResponse\",\n    \"DeleteSyncJobRequest\": \"amzn:DeleteSyncJobRequest\",\n    \"DeleteSyncJobResponse\": \"amzn:DeleteSyncJobResponse\",\n    \"DeleteWorkspaceRequest\": \"amzn:DeleteWorkspaceRequest\",\n    \"DeleteWorkspaceResponse\": \"amzn:DeleteWorkspaceResponse\",\n    \"EntityPropertyReference\": \"amzn:EntityPropertyReference\",\n    \"EntitySummary\": \"amzn:EntitySummary\"\
  ,\n    \"ErrorDetails\": \"amzn:ErrorDetails\",\n    \"ExecuteQueryRequest\": \"amzn:ExecuteQueryRequest\",\n    \"ExecuteQueryResponse\": \"amzn:ExecuteQueryResponse\",\n    \"ExternalIdProperty\": \"amzn:ExternalIdProperty\",\n    \"FunctionRequest\": \"amzn:FunctionRequest\",\n    \"FunctionResponse\": \"amzn:FunctionResponse\",\n    \"FunctionsRequest\": \"amzn:FunctionsRequest\",\n    \"FunctionsResponse\": \"amzn:FunctionsResponse\",\n    \"GeneratedSceneMetadataMap\": \"amzn:GeneratedSceneMetadataMap\",\n    \"GetComponentTypeRequest\": \"amzn:GetComponentTypeRequest\",\n    \"GetComponentTypeResponse\": \"amzn:GetComponentTypeResponse\",\n    \"GetEntityRequest\": \"amzn:GetEntityRequest\",\n    \"GetEntityResponse\": \"amzn:GetEntityResponse\",\n    \"GetPricingPlanRequest\": \"amzn:GetPricingPlanRequest\",\n    \"GetPricingPlanResponse\": \"amzn:GetPricingPlanResponse\",\n    \"GetPropertyValueHistoryRequest\": \"amzn:GetPropertyValueHistoryRequest\",\n    \"GetPropertyValueHistoryResponse\"\
  : \"amzn:GetPropertyValueHistoryResponse\",\n    \"GetPropertyValueRequest\": \"amzn:GetPropertyValueRequest\",\n    \"GetPropertyValueResponse\": \"amzn:GetPropertyValueResponse\",\n    \"GetSceneRequest\": \"amzn:GetSceneRequest\",\n    \"GetSceneResponse\": \"amzn:GetSceneResponse\",\n    \"GetSyncJobRequest\": \"amzn:GetSyncJobRequest\",\n    \"GetSyncJobResponse\": \"amzn:GetSyncJobResponse\",\n    \"GetWorkspaceRequest\": \"amzn:GetWorkspaceRequest\",\n    \"GetWorkspaceResponse\": \"amzn:GetWorkspaceResponse\",\n    \"InterpolationParameters\": \"amzn:InterpolationParameters\",\n    \"LambdaFunction\": \"amzn:LambdaFunction\",\n    \"ListComponentTypesFilter\": \"amzn:ListComponentTypesFilter\",\n    \"ListComponentTypesRequest\": \"amzn:ListComponentTypesRequest\",\n    \"ListComponentTypesResponse\": \"amzn:ListComponentTypesResponse\",\n    \"ListEntitiesFilter\": \"amzn:ListEntitiesFilter\",\n    \"ListEntitiesRequest\": \"amzn:ListEntitiesRequest\",\n    \"ListEntitiesResponse\"\
  : \"amzn:ListEntitiesResponse\",\n    \"ListScenesRequest\": \"amzn:ListScenesRequest\",\n    \"ListScenesResponse\": \"amzn:ListScenesResponse\",\n    \"ListSyncJobsRequest\": \"amzn:ListSyncJobsRequest\",\n    \"ListSyncJobsResponse\": \"amzn:ListSyncJobsResponse\",\n    \"ListSyncResourcesRequest\": \"amzn:ListSyncResourcesRequest\",\n    \"ListSyncResourcesResponse\": \"amzn:ListSyncResourcesResponse\",\n    \"ListTagsForResourceRequest\": \"amzn:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"ListWorkspacesRequest\": \"amzn:ListWorkspacesRequest\",\n    \"ListWorkspacesResponse\": \"amzn:ListWorkspacesResponse\",\n    \"OrderBy\": \"amzn:OrderBy\",\n    \"ParentEntityUpdateRequest\": \"amzn:ParentEntityUpdateRequest\",\n    \"PricingPlan\": \"amzn:PricingPlan\",\n    \"PropertyDefinitionRequest\": \"amzn:PropertyDefinitionRequest\",\n    \"PropertyDefinitionResponse\": \"amzn:PropertyDefinitionResponse\",\n    \"PropertyDefinitionsRequest\"\
  : \"amzn:PropertyDefinitionsRequest\",\n    \"PropertyDefinitionsResponse\": \"amzn:PropertyDefinitionsResponse\",\n    \"PropertyFilter\": \"amzn:PropertyFilter\",\n    \"PropertyGroupRequest\": \"amzn:PropertyGroupRequest\",\n    \"PropertyGroupResponse\": \"amzn:PropertyGroupResponse\",\n    \"PropertyGroupsRequest\": \"amzn:PropertyGroupsRequest\",\n    \"PropertyGroupsResponse\": \"amzn:PropertyGroupsResponse\",\n    \"PropertyLatestValue\": \"amzn:PropertyLatestValue\",\n    \"allowedValues\": {\n      \"@id\": \"amzn:allowedValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billableEntityCount\": {\n      \"@id\": \"amzn:billableEntityCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"booleanValue\": {\n      \"@id\": \"amzn:booleanValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundleInformation\": {\n      \"@id\": \"amzn:bundleInformation\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"bundleNames\": {\n      \"@id\": \"amzn:bundleNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilities\": {\n      \"@id\": \"amzn:capabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"amzn:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"columnDescriptions\": {\n      \"@id\": \"amzn:columnDescriptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentName\": {\n      \"@id\": \"amzn:componentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentTypeId\": {\n      \"@id\": \"amzn:componentTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentTypeName\": {\n      \"@id\": \"amzn:componentTypeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentTypeSummaries\": {\n      \"@id\": \"amzn:componentTypeSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentUpdates\": {\n      \"@id\": \"amzn:componentUpdates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  components\": {\n      \"@id\": \"amzn:components\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"amzn:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentLocation\": {\n      \"@id\": \"amzn:contentLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDateTime\": {\n      \"@id\": \"amzn:creationDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentPricingPlan\": {\n      \"@id\": \"amzn:currentPricingPlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataType\": {\n      \"@id\": \"amzn:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"amzn:defaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"definedIn\": {\n      \"@id\": \"amzn:definedIn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"definition\": {\n      \"@id\": \"amzn:definition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"displayName\"\
  : {\n      \"@id\": \"amzn:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"doubleValue\": {\n      \"@id\": \"amzn:doubleValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDateTime\": {\n      \"@id\": \"amzn:effectiveDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDateTime\": {\n      \"@id\": \"amzn:endDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"amzn:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityId\": {\n      \"@id\": \"amzn:entityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityName\": {\n      \"@id\": \"amzn:entityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityPropertyReference\": {\n      \"@id\": \"amzn:entityPropertyReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entitySummaries\": {\n      \"@id\": \"amzn:entitySummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entries\": {\n      \"@id\": \"amzn:entries\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"entry\": {\n      \"@id\": \"amzn:entry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"amzn:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"amzn:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorEntries\": {\n      \"@id\": \"amzn:errorEntries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"amzn:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amzn:errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expression\": {\n      \"@id\": \"amzn:expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extendsFrom\": {\n      \"@id\": \"amzn:extendsFrom\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalId\": {\n      \"@id\": \"amzn:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalIdProperty\": {\n      \"@id\": \"amzn:externalIdProperty\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"amzn:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functions\": {\n      \"@id\": \"amzn:functions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generatedSceneMetadata\": {\n      \"@id\": \"amzn:generatedSceneMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupType\": {\n      \"@id\": \"amzn:groupType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasChildEntities\": {\n      \"@id\": \"amzn:hasChildEntities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"implementedBy\": {\n      \"@id\": \"amzn:implementedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integerValue\": {\n      \"@id\": \"amzn:integerValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interpolation\": {\n      \"@id\": \"amzn:interpolation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interpolationType\": {\n      \"@id\": \"amzn:interpolationType\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"intervalInSeconds\": {\n      \"@id\": \"amzn:intervalInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isAbstract\": {\n      \"@id\": \"amzn:isAbstract\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isExternalId\": {\n      \"@id\": \"amzn:isExternalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isFinal\": {\n      \"@id\": \"amzn:isFinal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isImported\": {\n      \"@id\": \"amzn:isImported\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isInherited\": {\n      \"@id\": \"amzn:isInherited\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isNative\": {\n      \"@id\": \"amzn:isNative\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isRequiredInEntity\": {\n      \"@id\": \"amzn:isRequiredInEntity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isSchemaInitialized\": {\n      \"@id\": \"amzn:isSchemaInitialized\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isSingleton\": {\n      \"@id\": \"amzn:isSingleton\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"isStoredExternally\": {\n      \"@id\": \"amzn:isStoredExternally\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isTimeSeries\": {\n      \"@id\": \"amzn:isTimeSeries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambda\": {\n      \"@id\": \"amzn:lambda\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listValue\": {\n      \"@id\": \"amzn:listValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longValue\": {\n      \"@id\": \"amzn:longValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapValue\": {\n      \"@id\": \"amzn:mapValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amzn:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amzn:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"namespace\": {\n      \"@id\": \"amzn:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nestedType\"\
  : {\n      \"@id\": \"amzn:nestedType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"amzn:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"order\": {\n      \"@id\": \"amzn:order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderBy\": {\n      \"@id\": \"amzn:orderBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderByTime\": {\n      \"@id\": \"amzn:orderByTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentEntityId\": {\n      \"@id\": \"amzn:parentEntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentEntityUpdate\": {\n      \"@id\": \"amzn:parentEntityUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pendingPricingPlan\": {\n      \"@id\": \"amzn:pendingPricingPlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pricingMode\": {\n      \"@id\": \"amzn:pricingMode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"pricingTier\": {\n      \"@id\": \"amzn:pricingTier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"amzn:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyDefinitions\": {\n      \"@id\": \"amzn:propertyDefinitions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyFilters\": {\n      \"@id\": \"amzn:propertyFilters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyGroupName\": {\n      \"@id\": \"amzn:propertyGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyGroupUpdates\": {\n      \"@id\": \"amzn:propertyGroupUpdates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyGroups\": {\n      \"@id\": \"amzn:propertyGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyName\": {\n      \"@id\": \"amzn:propertyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyNames\": {\n      \"@id\": \"amzn:propertyNames\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"propertyReference\": {\n      \"@id\": \"amzn:propertyReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyUpdates\": {\n      \"@id\": \"amzn:propertyUpdates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyValue\": {\n      \"@id\": \"amzn:propertyValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyValues\": {\n      \"@id\": \"amzn:propertyValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryStatement\": {\n      \"@id\": \"amzn:queryStatement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationship\": {\n      \"@id\": \"amzn:relationship\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipType\": {\n      \"@id\": \"amzn:relationshipType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipValue\": {\n      \"@id\": \"amzn:relationshipValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requiredProperties\": {\n      \"@id\": \"amzn:requiredProperties\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"resourceARN\": {\n      \"@id\": \"amzn:resourceARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceId\": {\n      \"@id\": \"amzn:resourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"amzn:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"amzn:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rowData\": {\n      \"@id\": \"amzn:rowData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rows\": {\n      \"@id\": \"amzn:rows\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Location\": {\n      \"@id\": \"amzn:s3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sceneId\": {\n      \"@id\": \"amzn:sceneId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sceneMetadata\": {\n      \"@id\": \"amzn:sceneMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sceneSummaries\": {\n      \"@id\": \"amzn:sceneSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  scope\": {\n      \"@id\": \"amzn:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedProperties\": {\n      \"@id\": \"amzn:selectedProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDateTime\": {\n      \"@id\": \"amzn:startDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amzn:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"amzn:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stringValue\": {\n      \"@id\": \"amzn:stringValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncJobSummaries\": {\n      \"@id\": \"amzn:syncJobSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncResources\": {\n      \"@id\": \"amzn:syncResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncRole\": {\n      \"@id\": \"amzn:syncRole\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"syncSource\": {\n      \"@id\": \"amzn:syncSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tabularConditions\": {\n      \"@id\": \"amzn:tabularConditions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tabularPropertyValues\": {\n      \"@id\": \"amzn:tabularPropertyValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetComponentName\": {\n      \"@id\": \"amzn:targetComponentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetComponentTypeId\": {\n      \"@id\": \"amzn:targetComponentTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetEntityId\": {\n      \"@id\": \"amzn:targetEntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"amzn:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"amzn:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n     \
  \ \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitOfMeasure\": {\n      \"@id\": \"amzn:unitOfMeasure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateDateTime\": {\n      \"@id\": \"amzn:updateDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateReason\": {\n      \"@id\": \"amzn:updateReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateType\": {\n      \"@id\": \"amzn:updateType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amzn:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"amzn:values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"amzn:workspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workspaceSummaries\": {\n      \"@id\": \"amzn:workspaceSummaries\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-twinmaker/refs/heads/main/json-ld/amazon-iot-twinmaker-context.jsonld
tags:
- AWS
- 3D Visualization
- Digital Twin
- Industrial IoT
- IoT
- JSON-LD
- Linked Data
- Semantic Web
---

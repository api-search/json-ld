---
class_count: 108
classes:
- EncryptionMapperAESConfiguration
- NotificationConfig
- ResourceRequirements
- RowFilteringOperation
- ApplicationCreate
- StreamConfigurations
- GroupMemberResponse
- CreateDeclarativeSourceDefinitionRequest
- TagResponse
- DataplaneCreateRequest
- PermissionResponseRead
- DeclarativeSourceDefinitionsResponse
- EmbeddedWidgetRequest
- RowFilteringMapperConfiguration
- EmbeddedWidgetResponse
- RegionsResponse
- InitiateOauthRequest
- TagPatchRequest
- RowFilteringOperationNot
- SourcePutRequest
- WebhookNotificationConfig
- DefinitionsResponse
- ConnectionResponse
- SourceConfiguration
- SourceResponse
- DataplaneResponse
- UserResponse
- OAuthCredentialsConfiguration
- GroupPermissionsResponse
- EmailNotificationConfig
- ConnectionsResponse
- TagsResponse
- JobTypeResourceLimit
- RegionPatchRequest
- FieldRenamingMapperConfiguration
- EmbeddedOrganizationListItem
- StreamConfiguration
- WorkspaceResponse
- EmbeddedOrganizationsList
- DefinitionResponse
- ConnectorDefinitionsResponse
- RegionCreateRequest
- DestinationPatchRequest
- SourceDefinitionSpecification
- EmbeddedScopedTokenRequest
- WorkspaceOAuthCredentialsRequest
- GroupPermissionResponse
- PermissionResponse
- EncryptionMapperConfiguration
- StreamProperties
- NotificationsConfig
- WorkspaceCreateRequest
- SelectedFieldInfo
- ApplicationTokenRequestWithGrant
- RedirectUrlResponse
- DeclarativeManifest
- WorkspacesResponse
- OrganizationOAuthCredentialsRequest
- GroupCreateRequest
- CreateDefinitionRequest
- UpdateDeclarativeSourceDefinitionRequest
- DestinationResponse
- DataplanesResponse
- DeclarativeSourceDefinitionResponse
- JobsResponse
- GroupMemberAddRequest
- UsersResponse
- DestinationConfiguration
- SourcesResponse
- GroupsResponse
- PermissionCreateRequest
- UpdateDefinitionRequest
- ScopedResourceRequirements
- ConfiguredStreamMapper
- SourceCreateRequest
- ConnectionCreateRequest
- TagCreateRequest
- ApplicationReadList
- DestinationPutRequest
- AirbyteApiConnectionSchedule
- FieldFilteringMapperConfiguration
- EncryptionMapperRSAConfiguration
- JobResponse
- WorkspaceUpdateRequest
- Tag
- ConnectionScheduleResponse
- GroupUpdateRequest
- ConnectorDefinitionResponse
- OrganizationResponse
- MapperConfiguration
- RowFilteringOperationEqual
- DataplanePatchRequest
- GroupPermissionCreateRequest
- DestinationsResponse
- ApplicationRead
- DestinationCreateRequest
- GroupMembersResponse
- OrganizationsResponse
- PublicAccessTokenResponse
- RegionResponse
- HashingMapperConfiguration
- EmbeddedScopedTokenResponse
- PermissionUpdateRequest
- ConnectionPatchRequest
- GroupResponse
- SourcePatchRequest
- PermissionsResponse
- JobCreateRequest
context_file: json-ld/airbyte-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/json-ld/airbyte-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Airbyte from Airbyte.
layout: jsonld
name: Airbyte Context
namespaces:
- prefix: airbyte
  uri: https://airbyte.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: algorithm
  type: ''
- container: ''
  name: fieldNameSuffix
  type: ''
- container: ''
  name: key
  type: ''
- container: ''
  name: mode
  type: ''
- container: ''
  name: padding
  type: ''
- container: ''
  name: targetField
  type: ''
- container: ''
  name: email
  type: ''
- container: ''
  name: webhook
  type: ''
- container: ''
  name: cpuRequest
  type: ''
- container: ''
  name: cpuLimit
  type: ''
- container: ''
  name: memoryRequest
  type: ''
- container: ''
  name: memoryLimit
  type: ''
- container: ''
  name: ephemeralStorageRequest
  type: ''
- container: ''
  name: ephemeralStorageLimit
  type: ''
- container: ''
  name: name
  type: ''
- container: set
  name: streams
  type: string
- container: ''
  name: memberId
  type: ''
- container: ''
  name: groupId
  type: ''
- container: ''
  name: userId
  type: ''
- container: ''
  name: userEmail
  type: ''
- container: ''
  name: userName
  type: ''
- container: ''
  name: manifest
  type: ''
- container: ''
  name: tagId
  type: ''
- container: ''
  name: color
  type: ''
- container: ''
  name: workspaceId
  type: ''
- container: ''
  name: regionId
  type: ''
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: permissionId
  type: ''
- container: ''
  name: permissionType
  type: ''
- container: ''
  name: scopeId
  type: ''
- container: ''
  name: scope
  type: ''
- container: ''
  name: previous
  type: ''
- container: ''
  name: next
  type: ''
- container: set
  name: data
  type: string
- container: ''
  name: allowedOrigin
  type: ''
- container: ''
  name: externalUserId
  type: ''
- container: ''
  name: organizationId
  type: ''
- container: ''
  name: conditions
  type: ''
- container: ''
  name: token
  type: ''
- container: ''
  name: sourceType
  type: ''
- container: ''
  name: redirectUrl
  type: ''
- container: ''
  name: oAuthInputConfiguration
  type: ''
- container: set
  name: requestedScopes
  type: string
- container: set
  name: requestedOptionalScopes
  type: string
- container: ''
  name: type
  type: ''
- container: ''
  name: configuration
  type: ''
- container: ''
  name: resourceAllocation
  type: ''
- container: ''
  name: url
  type: ''
- container: ''
  name: connectionId
  type: ''
- container: ''
  name: sourceId
  type: ''
- container: ''
  name: destinationId
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: schedule
  type: ''
- container: ''
  name: nonBreakingSchemaUpdatesBehavior
  type: ''
- container: ''
  name: namespaceDefinition
  type: ''
- container: ''
  name: namespaceFormat
  type: ''
- container: ''
  name: prefix
  type: ''
- container: ''
  name: configurations
  type: ''
- container: ''
  name: createdAt
  type: ''
- container: set
  name: tags
  type: string
- container: ''
  name: statusReason
  type: ''
- container: ''
  name: definitionId
  type: ''
- container: ''
  name: dataplaneId
  type: ''
- container: ''
  name: updatedAt
  type: ''
- container: ''
  name: id
  type: ''
- container: ''
  name: jobType
  type: ''
- container: ''
  name: resourceRequirements
  type: ''
- container: ''
  name: newFieldName
  type: ''
- container: ''
  name: originalFieldName
  type: ''
- container: ''
  name: organizationName
  type: ''
- container: ''
  name: permission
  type: ''
- container: ''
  name: namespace
  type: ''
- container: ''
  name: syncMode
  type: ''
- container: set
  name: cursorField
  type: string
- container: set
  name: primaryKey
  type: string
- container: ''
  name: includeFiles
  type: boolean
- container: ''
  name: destinationObjectName
  type: ''
- container: ''
  name: selectedFields
  type: ''
- container: set
  name: mappers
  type: string
- container: ''
  name: dataResidency
  type: ''
- container: ''
  name: notifications
  type: ''
- container: set
  name: organizations
  type: string
- container: ''
  name: dockerRepository
  type: ''
- container: ''
  name: dockerImageTag
  type: ''
- container: ''
  name: documentationUrl
  type: ''
- container: ''
  name: actorType
  type: ''
- container: ''
  name: streamName
  type: ''
- container: set
  name: syncModes
  type: string
- container: ''
  name: streamnamespace
  type: ''
- container: set
  name: defaultCursorField
  type: string
- container: ''
  name: sourceDefinedCursorField
  type: boolean
- container: set
  name: sourceDefinedPrimaryKey
  type: string
- container: set
  name: propertyFields
  type: string
- container: ''
  name: failure
  type: ''
- container: ''
  name: success
  type: ''
- container: ''
  name: connectionUpdate
  type: ''
- container: ''
  name: connectionUpdateActionRequired
  type: ''
- container: ''
  name: syncDisabled
  type: ''
- container: ''
  name: syncDisabledWarning
  type: ''
- container: set
  name: fieldPath
  type: string
- container: ''
  name: clientId
  type: ''
- container: ''
  name: clientSecret
  type: ''
- container: ''
  name: grant-type
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: destinationType
  type: ''
- container: ''
  name: version
  type: ''
- container: ''
  name: default
  type: ''
- container: set
  name: jobSpecific
  type: string
- container: ''
  name: mapperConfiguration
  type: ''
- container: ''
  name: secretId
  type: ''
- container: set
  name: applications
  type: string
- container: ''
  name: scheduleType
  type: ''
- container: ''
  name: cronExpression
  type: ''
- container: ''
  name: publicKey
  type: ''
- container: ''
  name: jobId
  type: ''
- container: ''
  name: startTime
  type: ''
- container: ''
  name: lastUpdatedAt
  type: ''
- container: ''
  name: duration
  type: ''
- container: ''
  name: bytesSynced
  type: ''
- container: ''
  name: rowsSynced
  type: ''
- container: ''
  name: basicTiming
  type: ''
- container: ''
  name: connectorDefinitionType
  type: ''
- container: ''
  name: comparisonValue
  type: ''
- container: ''
  name: fieldName
  type: ''
- container: ''
  name: accessToken
  type: ''
- container: ''
  name: tokenType
  type: ''
- container: ''
  name: expiresIn
  type: ''
- container: ''
  name: method
  type: ''
- container: ''
  name: memberCount
  type: ''
property_count: 129
provider_name: Airbyte
provider_slug: airbyte
slug: airbyte-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"airbyte\": \"https://airbyte.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EncryptionMapperAESConfiguration\": \"airbyte:EncryptionMapperAESConfiguration\",\n    \"NotificationConfig\": \"airbyte:NotificationConfig\",\n    \"ResourceRequirements\": \"airbyte:ResourceRequirements\",\n    \"RowFilteringOperation\": \"airbyte:RowFilteringOperation\",\n    \"ApplicationCreate\": \"airbyte:ApplicationCreate\",\n    \"StreamConfigurations\": \"airbyte:StreamConfigurations\",\n    \"GroupMemberResponse\": \"airbyte:GroupMemberResponse\",\n    \"CreateDeclarativeSourceDefinitionRequest\": \"airbyte:CreateDeclarativeSourceDefinitionRequest\",\n    \"TagResponse\": \"airbyte:TagResponse\",\n    \"DataplaneCreateRequest\": \"airbyte:DataplaneCreateRequest\",\n    \"PermissionResponseRead\": \"airbyte:PermissionResponseRead\"\
  ,\n    \"DeclarativeSourceDefinitionsResponse\": \"airbyte:DeclarativeSourceDefinitionsResponse\",\n    \"EmbeddedWidgetRequest\": \"airbyte:EmbeddedWidgetRequest\",\n    \"RowFilteringMapperConfiguration\": \"airbyte:RowFilteringMapperConfiguration\",\n    \"EmbeddedWidgetResponse\": \"airbyte:EmbeddedWidgetResponse\",\n    \"RegionsResponse\": \"airbyte:RegionsResponse\",\n    \"InitiateOauthRequest\": \"airbyte:InitiateOauthRequest\",\n    \"TagPatchRequest\": \"airbyte:TagPatchRequest\",\n    \"RowFilteringOperationNot\": \"airbyte:RowFilteringOperationNot\",\n    \"SourcePutRequest\": \"airbyte:SourcePutRequest\",\n    \"WebhookNotificationConfig\": \"airbyte:WebhookNotificationConfig\",\n    \"DefinitionsResponse\": \"airbyte:DefinitionsResponse\",\n    \"ConnectionResponse\": \"airbyte:ConnectionResponse\",\n    \"SourceConfiguration\": \"airbyte:SourceConfiguration\",\n    \"SourceResponse\": \"airbyte:SourceResponse\",\n    \"DataplaneResponse\": \"airbyte:DataplaneResponse\"\
  ,\n    \"UserResponse\": \"airbyte:UserResponse\",\n    \"OAuthCredentialsConfiguration\": \"airbyte:OAuthCredentialsConfiguration\",\n    \"GroupPermissionsResponse\": \"airbyte:GroupPermissionsResponse\",\n    \"EmailNotificationConfig\": \"airbyte:EmailNotificationConfig\",\n    \"ConnectionsResponse\": \"airbyte:ConnectionsResponse\",\n    \"TagsResponse\": \"airbyte:TagsResponse\",\n    \"JobTypeResourceLimit\": \"airbyte:JobTypeResourceLimit\",\n    \"RegionPatchRequest\": \"airbyte:RegionPatchRequest\",\n    \"FieldRenamingMapperConfiguration\": \"airbyte:FieldRenamingMapperConfiguration\",\n    \"EmbeddedOrganizationListItem\": \"airbyte:EmbeddedOrganizationListItem\",\n    \"StreamConfiguration\": \"airbyte:StreamConfiguration\",\n    \"WorkspaceResponse\": \"airbyte:WorkspaceResponse\",\n    \"EmbeddedOrganizationsList\": \"airbyte:EmbeddedOrganizationsList\",\n    \"DefinitionResponse\": \"airbyte:DefinitionResponse\",\n    \"ConnectorDefinitionsResponse\": \"airbyte:ConnectorDefinitionsResponse\"\
  ,\n    \"RegionCreateRequest\": \"airbyte:RegionCreateRequest\",\n    \"DestinationPatchRequest\": \"airbyte:DestinationPatchRequest\",\n    \"SourceDefinitionSpecification\": \"airbyte:SourceDefinitionSpecification\",\n    \"EmbeddedScopedTokenRequest\": \"airbyte:EmbeddedScopedTokenRequest\",\n    \"WorkspaceOAuthCredentialsRequest\": \"airbyte:WorkspaceOAuthCredentialsRequest\",\n    \"GroupPermissionResponse\": \"airbyte:GroupPermissionResponse\",\n    \"PermissionResponse\": \"airbyte:PermissionResponse\",\n    \"EncryptionMapperConfiguration\": \"airbyte:EncryptionMapperConfiguration\",\n    \"StreamProperties\": \"airbyte:StreamProperties\",\n    \"NotificationsConfig\": \"airbyte:NotificationsConfig\",\n    \"WorkspaceCreateRequest\": \"airbyte:WorkspaceCreateRequest\",\n    \"SelectedFieldInfo\": \"airbyte:SelectedFieldInfo\",\n    \"ApplicationTokenRequestWithGrant\": \"airbyte:ApplicationTokenRequestWithGrant\",\n    \"RedirectUrlResponse\": \"airbyte:RedirectUrlResponse\",\n\
  \    \"DeclarativeManifest\": \"airbyte:DeclarativeManifest\",\n    \"WorkspacesResponse\": \"airbyte:WorkspacesResponse\",\n    \"OrganizationOAuthCredentialsRequest\": \"airbyte:OrganizationOAuthCredentialsRequest\",\n    \"GroupCreateRequest\": \"airbyte:GroupCreateRequest\",\n    \"CreateDefinitionRequest\": \"airbyte:CreateDefinitionRequest\",\n    \"UpdateDeclarativeSourceDefinitionRequest\": \"airbyte:UpdateDeclarativeSourceDefinitionRequest\",\n    \"DestinationResponse\": \"airbyte:DestinationResponse\",\n    \"DataplanesResponse\": \"airbyte:DataplanesResponse\",\n    \"DeclarativeSourceDefinitionResponse\": \"airbyte:DeclarativeSourceDefinitionResponse\",\n    \"JobsResponse\": \"airbyte:JobsResponse\",\n    \"GroupMemberAddRequest\": \"airbyte:GroupMemberAddRequest\",\n    \"UsersResponse\": \"airbyte:UsersResponse\",\n    \"DestinationConfiguration\": \"airbyte:DestinationConfiguration\",\n    \"SourcesResponse\": \"airbyte:SourcesResponse\",\n    \"GroupsResponse\": \"airbyte:GroupsResponse\"\
  ,\n    \"PermissionCreateRequest\": \"airbyte:PermissionCreateRequest\",\n    \"UpdateDefinitionRequest\": \"airbyte:UpdateDefinitionRequest\",\n    \"ScopedResourceRequirements\": \"airbyte:ScopedResourceRequirements\",\n    \"ConfiguredStreamMapper\": \"airbyte:ConfiguredStreamMapper\",\n    \"SourceCreateRequest\": \"airbyte:SourceCreateRequest\",\n    \"ConnectionCreateRequest\": \"airbyte:ConnectionCreateRequest\",\n    \"TagCreateRequest\": \"airbyte:TagCreateRequest\",\n    \"ApplicationReadList\": \"airbyte:ApplicationReadList\",\n    \"DestinationPutRequest\": \"airbyte:DestinationPutRequest\",\n    \"AirbyteApiConnectionSchedule\": \"airbyte:AirbyteApiConnectionSchedule\",\n    \"FieldFilteringMapperConfiguration\": \"airbyte:FieldFilteringMapperConfiguration\",\n    \"EncryptionMapperRSAConfiguration\": \"airbyte:EncryptionMapperRSAConfiguration\",\n    \"JobResponse\": \"airbyte:JobResponse\",\n    \"WorkspaceUpdateRequest\": \"airbyte:WorkspaceUpdateRequest\",\n    \"Tag\"\
  : \"airbyte:Tag\",\n    \"ConnectionScheduleResponse\": \"airbyte:ConnectionScheduleResponse\",\n    \"GroupUpdateRequest\": \"airbyte:GroupUpdateRequest\",\n    \"ConnectorDefinitionResponse\": \"airbyte:ConnectorDefinitionResponse\",\n    \"OrganizationResponse\": \"airbyte:OrganizationResponse\",\n    \"MapperConfiguration\": \"airbyte:MapperConfiguration\",\n    \"RowFilteringOperationEqual\": \"airbyte:RowFilteringOperationEqual\",\n    \"DataplanePatchRequest\": \"airbyte:DataplanePatchRequest\",\n    \"GroupPermissionCreateRequest\": \"airbyte:GroupPermissionCreateRequest\",\n    \"DestinationsResponse\": \"airbyte:DestinationsResponse\",\n    \"ApplicationRead\": \"airbyte:ApplicationRead\",\n    \"DestinationCreateRequest\": \"airbyte:DestinationCreateRequest\",\n    \"GroupMembersResponse\": \"airbyte:GroupMembersResponse\",\n    \"OrganizationsResponse\": \"airbyte:OrganizationsResponse\",\n    \"PublicAccessTokenResponse\": \"airbyte:PublicAccessTokenResponse\",\n    \"RegionResponse\"\
  : \"airbyte:RegionResponse\",\n    \"HashingMapperConfiguration\": \"airbyte:HashingMapperConfiguration\",\n    \"EmbeddedScopedTokenResponse\": \"airbyte:EmbeddedScopedTokenResponse\",\n    \"PermissionUpdateRequest\": \"airbyte:PermissionUpdateRequest\",\n    \"ConnectionPatchRequest\": \"airbyte:ConnectionPatchRequest\",\n    \"GroupResponse\": \"airbyte:GroupResponse\",\n    \"SourcePatchRequest\": \"airbyte:SourcePatchRequest\",\n    \"PermissionsResponse\": \"airbyte:PermissionsResponse\",\n    \"JobCreateRequest\": \"airbyte:JobCreateRequest\",\n    \"algorithm\": {\n      \"@id\": \"airbyte:algorithm\"\n    },\n    \"fieldNameSuffix\": {\n      \"@id\": \"airbyte:fieldNameSuffix\"\n    },\n    \"key\": {\n      \"@id\": \"airbyte:key\"\n    },\n    \"mode\": {\n      \"@id\": \"airbyte:mode\"\n    },\n    \"padding\": {\n      \"@id\": \"airbyte:padding\"\n    },\n    \"targetField\": {\n      \"@id\": \"airbyte:targetField\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\
  \n    },\n    \"webhook\": {\n      \"@id\": \"airbyte:webhook\"\n    },\n    \"cpuRequest\": {\n      \"@id\": \"airbyte:cpu_request\"\n    },\n    \"cpuLimit\": {\n      \"@id\": \"airbyte:cpu_limit\"\n    },\n    \"memoryRequest\": {\n      \"@id\": \"airbyte:memory_request\"\n    },\n    \"memoryLimit\": {\n      \"@id\": \"airbyte:memory_limit\"\n    },\n    \"ephemeralStorageRequest\": {\n      \"@id\": \"airbyte:ephemeral_storage_request\"\n    },\n    \"ephemeralStorageLimit\": {\n      \"@id\": \"airbyte:ephemeral_storage_limit\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"streams\": {\n      \"@id\": \"airbyte:streams\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memberId\": {\n      \"@id\": \"airbyte:memberId\"\n    },\n    \"groupId\": {\n      \"@id\": \"airbyte:groupId\"\n    },\n    \"userId\": {\n      \"@id\": \"airbyte:userId\"\n    },\n    \"userEmail\": {\n      \"@id\": \"airbyte:userEmail\"\n    },\n\
  \    \"userName\": {\n      \"@id\": \"airbyte:userName\"\n    },\n    \"manifest\": {\n      \"@id\": \"airbyte:manifest\"\n    },\n    \"tagId\": {\n      \"@id\": \"airbyte:tagId\"\n    },\n    \"color\": {\n      \"@id\": \"airbyte:color\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"airbyte:workspaceId\"\n    },\n    \"regionId\": {\n      \"@id\": \"airbyte:regionId\"\n    },\n    \"enabled\": {\n      \"@id\": \"airbyte:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"permissionId\": {\n      \"@id\": \"airbyte:permissionId\"\n    },\n    \"permissionType\": {\n      \"@id\": \"airbyte:permissionType\"\n    },\n    \"scopeId\": {\n      \"@id\": \"airbyte:scopeId\"\n    },\n    \"scope\": {\n      \"@id\": \"airbyte:scope\"\n    },\n    \"previous\": {\n      \"@id\": \"airbyte:previous\"\n    },\n    \"next\": {\n      \"@id\": \"airbyte:next\"\n    },\n    \"data\": {\n      \"@id\": \"airbyte:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"allowedOrigin\": {\n      \"@id\": \"airbyte:allowedOrigin\"\n    },\n    \"externalUserId\": {\n      \"@id\": \"airbyte:externalUserId\"\n    },\n    \"organizationId\": {\n      \"@id\": \"airbyte:organizationId\"\n    },\n    \"conditions\": {\n      \"@id\": \"airbyte:conditions\"\n    },\n    \"token\": {\n      \"@id\": \"airbyte:token\"\n    },\n    \"sourceType\": {\n      \"@id\": \"airbyte:sourceType\"\n    },\n    \"redirectUrl\": {\n      \"@id\": \"airbyte:redirectUrl\"\n    },\n    \"oAuthInputConfiguration\": {\n      \"@id\": \"airbyte:oAuthInputConfiguration\"\n    },\n    \"requestedScopes\": {\n      \"@id\": \"airbyte:requestedScopes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedOptionalScopes\": {\n      \"@id\": \"airbyte:requestedOptionalScopes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"airbyte:type\"\n    },\n    \"configuration\"\
  : {\n      \"@id\": \"airbyte:configuration\"\n    },\n    \"resourceAllocation\": {\n      \"@id\": \"airbyte:resourceAllocation\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"connectionId\": {\n      \"@id\": \"airbyte:connectionId\"\n    },\n    \"sourceId\": {\n      \"@id\": \"airbyte:sourceId\"\n    },\n    \"destinationId\": {\n      \"@id\": \"airbyte:destinationId\"\n    },\n    \"status\": {\n      \"@id\": \"airbyte:status\"\n    },\n    \"schedule\": {\n      \"@id\": \"airbyte:schedule\"\n    },\n    \"nonBreakingSchemaUpdatesBehavior\": {\n      \"@id\": \"airbyte:nonBreakingSchemaUpdatesBehavior\"\n    },\n    \"namespaceDefinition\": {\n      \"@id\": \"airbyte:namespaceDefinition\"\n    },\n    \"namespaceFormat\": {\n      \"@id\": \"airbyte:namespaceFormat\"\n    },\n    \"prefix\": {\n      \"@id\": \"airbyte:prefix\"\n    },\n    \"configurations\": {\n      \"@id\": \"airbyte:configurations\"\n    },\n    \"createdAt\": {\n      \"@id\": \"\
  airbyte:createdAt\"\n    },\n    \"tags\": {\n      \"@id\": \"airbyte:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"airbyte:statusReason\"\n    },\n    \"definitionId\": {\n      \"@id\": \"airbyte:definitionId\"\n    },\n    \"dataplaneId\": {\n      \"@id\": \"airbyte:dataplaneId\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"airbyte:updatedAt\"\n    },\n    \"id\": {\n      \"@id\": \"airbyte:id\"\n    },\n    \"jobType\": {\n      \"@id\": \"airbyte:jobType\"\n    },\n    \"resourceRequirements\": {\n      \"@id\": \"airbyte:resourceRequirements\"\n    },\n    \"newFieldName\": {\n      \"@id\": \"airbyte:newFieldName\"\n    },\n    \"originalFieldName\": {\n      \"@id\": \"airbyte:originalFieldName\"\n    },\n    \"organizationName\": {\n      \"@id\": \"airbyte:organizationName\"\n    },\n    \"permission\": {\n      \"@id\": \"airbyte:permission\"\n    },\n    \"namespace\": {\n      \"@id\": \"\
  airbyte:namespace\"\n    },\n    \"syncMode\": {\n      \"@id\": \"airbyte:syncMode\"\n    },\n    \"cursorField\": {\n      \"@id\": \"airbyte:cursorField\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryKey\": {\n      \"@id\": \"airbyte:primaryKey\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeFiles\": {\n      \"@id\": \"airbyte:includeFiles\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"destinationObjectName\": {\n      \"@id\": \"airbyte:destinationObjectName\"\n    },\n    \"selectedFields\": {\n      \"@id\": \"airbyte:selectedFields\"\n    },\n    \"mappers\": {\n      \"@id\": \"airbyte:mappers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataResidency\": {\n      \"@id\": \"airbyte:dataResidency\"\n    },\n    \"notifications\": {\n      \"@id\": \"airbyte:notifications\"\n    },\n    \"organizations\": {\n      \"@id\": \"airbyte:organizations\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dockerRepository\": {\n      \"@id\": \"airbyte:dockerRepository\"\n    },\n    \"dockerImageTag\": {\n      \"@id\": \"airbyte:dockerImageTag\"\n    },\n    \"documentationUrl\": {\n      \"@id\": \"airbyte:documentationUrl\"\n    },\n    \"actorType\": {\n      \"@id\": \"airbyte:actorType\"\n    },\n    \"streamName\": {\n      \"@id\": \"airbyte:streamName\"\n    },\n    \"syncModes\": {\n      \"@id\": \"airbyte:syncModes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamnamespace\": {\n      \"@id\": \"airbyte:streamnamespace\"\n    },\n    \"defaultCursorField\": {\n      \"@id\": \"airbyte:defaultCursorField\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceDefinedCursorField\": {\n      \"@id\": \"airbyte:sourceDefinedCursorField\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sourceDefinedPrimaryKey\": {\n     \
  \ \"@id\": \"airbyte:sourceDefinedPrimaryKey\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyFields\": {\n      \"@id\": \"airbyte:propertyFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failure\": {\n      \"@id\": \"airbyte:failure\"\n    },\n    \"success\": {\n      \"@id\": \"airbyte:success\"\n    },\n    \"connectionUpdate\": {\n      \"@id\": \"airbyte:connectionUpdate\"\n    },\n    \"connectionUpdateActionRequired\": {\n      \"@id\": \"airbyte:connectionUpdateActionRequired\"\n    },\n    \"syncDisabled\": {\n      \"@id\": \"airbyte:syncDisabled\"\n    },\n    \"syncDisabledWarning\": {\n      \"@id\": \"airbyte:syncDisabledWarning\"\n    },\n    \"fieldPath\": {\n      \"@id\": \"airbyte:fieldPath\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"airbyte:client_id\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"airbyte:client_secret\"\
  \n    },\n    \"grant-type\": {\n      \"@id\": \"airbyte:grant-type\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"destinationType\": {\n      \"@id\": \"airbyte:destinationType\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"default\": {\n      \"@id\": \"airbyte:default\"\n    },\n    \"jobSpecific\": {\n      \"@id\": \"airbyte:jobSpecific\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapperConfiguration\": {\n      \"@id\": \"airbyte:mapperConfiguration\"\n    },\n    \"secretId\": {\n      \"@id\": \"airbyte:secretId\"\n    },\n    \"applications\": {\n      \"@id\": \"airbyte:applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleType\": {\n      \"@id\": \"airbyte:scheduleType\"\n    },\n    \"cronExpression\": {\n      \"@id\": \"airbyte:cronExpression\"\n    },\n    \"publicKey\": {\n      \"@id\": \"airbyte:publicKey\"\
  \n    },\n    \"jobId\": {\n      \"@id\": \"airbyte:jobId\"\n    },\n    \"startTime\": {\n      \"@id\": \"airbyte:startTime\"\n    },\n    \"lastUpdatedAt\": {\n      \"@id\": \"airbyte:lastUpdatedAt\"\n    },\n    \"duration\": {\n      \"@id\": \"airbyte:duration\"\n    },\n    \"bytesSynced\": {\n      \"@id\": \"airbyte:bytesSynced\"\n    },\n    \"rowsSynced\": {\n      \"@id\": \"airbyte:rowsSynced\"\n    },\n    \"basicTiming\": {\n      \"@id\": \"airbyte:basicTiming\"\n    },\n    \"connectorDefinitionType\": {\n      \"@id\": \"airbyte:connectorDefinitionType\"\n    },\n    \"comparisonValue\": {\n      \"@id\": \"airbyte:comparisonValue\"\n    },\n    \"fieldName\": {\n      \"@id\": \"airbyte:fieldName\"\n    },\n    \"accessToken\": {\n      \"@id\": \"airbyte:access_token\"\n    },\n    \"tokenType\": {\n      \"@id\": \"airbyte:token_type\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"airbyte:expires_in\"\n    },\n    \"method\": {\n      \"@id\": \"airbyte:method\"\
  \n    },\n    \"memberCount\": {\n      \"@id\": \"airbyte:memberCount\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/airbyte/refs/heads/main/json-ld/airbyte-context.jsonld
tags:
- Data Integration
- ETL
- ELT
- Open Source
- Data Pipeline
- Connectors
- Data
- JSON-LD
- Linked Data
- Semantic Web
---

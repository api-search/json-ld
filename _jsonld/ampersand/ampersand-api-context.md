---
api_specs:
- filename: ampersand-api-openapi-original.yml
  format: yaml
  label: Ampersand API
  slug: ampersand-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ampersand/refs/heads/main/openapi/ampersand-api-openapi-original.yml
class_count: 49
classes:
- AssociationLabels
- Oauth2AuthorizationCode
- PatchApiKeyRequest
- Project
- name
- HydratedRevision
- Destination
- FieldDefinition
- description
- UpsertMetadataRequest
- NotificationEventTopicRoute
- BillingAccount
- BuilderInfo
- WebhookHeaders
- ProviderAppMetadata
- JWTKeyResponse
- Oauth2AuthorizationCodeTokensOnly
- StringFieldOptions
- Org
- UpsertMetadataResponse
- UpdateConnectionRequest
- Topic
- ProviderMetadataInfo
- BackfillProgress
- ConnectionRequest
- ApiKeyRequest
- PatchJWTKeyRequest
- ApiKey
- SignedUrl
- url
- ProviderMetadata
- DestinationWithSecrets
- Integration
- Config
- AssociationDefinition
- Installation
- TopicDestinationRoute
- Revision
- FieldUpsertResult
- NumericFieldOptions
- JSONPatchOperation
- ClaimedDomainResponse
- PaginationInfo
- Builder
- CreateJWTKeyRequest
- ProviderApp
- Invite
- ObjectMetadata
- JWTKey
context_file: json-ld/ampersand-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ampersand/refs/heads/main/json-ld/ampersand-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ampersand Api from Ampersand.
layout: jsonld
name: Ampersand Api Context
namespaces:
- prefix: amp
  uri: https://withampersand.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: singular
  type: string
- container: ''
  name: plural
  type: string
- container: ''
  name: accessToken
  type: reference
- container: ''
  name: refreshToken
  type: reference
- container: set
  name: scopes
  type: string
- container: set
  name: updateMask
  type: string
- container: ''
  name: apiKey
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: appName
  type: string
- container: ''
  name: orgId
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: entitlements
  type: reference
- container: ''
  name: specVersion
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: fieldName
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: valueType
  type: string
- container: ''
  name: required
  type: boolean
- container: ''
  name: unique
  type: boolean
- container: ''
  name: indexed
  type: boolean
- container: ''
  name: stringOptions
  type: string
- container: ''
  name: numericOptions
  type: string
- container: ''
  name: association
  type: string
- container: ''
  name: groupRef
  type: string
- container: ''
  name: fields
  type: reference
- container: ''
  name: eventType
  type: string
- container: ''
  name: topicId
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: billingProvider
  type: string
- container: ''
  name: billingProviderRef
  type: string
- container: ''
  name: builder
  type: string
- container: ''
  name: projectRoles
  type: reference
- container: ''
  name: orgRole
  type: reference
- container: ''
  name: authQueryParams
  type: reference
- container: ''
  name: providerParams
  type: reference
- container: ''
  name: kid
  type: string
- container: ''
  name: length
  type: integer
- container: ''
  name: pattern
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: valuesRestricted
  type: boolean
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: defaultTeamId
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: connection
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: installationId
  type: string
- container: ''
  name: objectName
  type: string
- container: ''
  name: operationId
  type: string
- container: ''
  name: recordsProcessed
  type: integer
- container: ''
  name: recordsEstimatedTotal
  type: integer
- container: ''
  name: providerWorkspaceRef
  type: string
- container: ''
  name: providerMetadata
  type: string
- container: ''
  name: groupName
  type: string
- container: ''
  name: consumerName
  type: string
- container: ''
  name: consumerRef
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: customAuth
  type: reference
- container: ''
  name: basicAuth
  type: reference
- container: ''
  name: oauth2ClientCredentials
  type: reference
- container: ''
  name: oauth2PasswordCredentials
  type: reference
- container: ''
  name: oauth2AuthorizationCode
  type: string
- container: ''
  name: jwtKey
  type: reference
- container: ''
  name: key
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: bucket
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: secrets
  type: reference
- container: ''
  name: latestRevision
  type: string
- container: ''
  name: revisionId
  type: string
- container: ''
  name: createdBy
  type: string
- container: ''
  name: associationType
  type: string
- container: ''
  name: targetObject
  type: string
- container: ''
  name: targetField
  type: string
- container: ''
  name: cardinality
  type: string
- container: ''
  name: onDelete
  type: string
- container: ''
  name: reverseLookupFieldName
  type: string
- container: ''
  name: labels
  type: string
- container: ''
  name: integrationId
  type: string
- container: ''
  name: group
  type: string
- container: ''
  name: healthStatus
  type: string
- container: ''
  name: lastOperationStatus
  type: string
- container: ''
  name: config
  type: string
- container: ''
  name: destinationId
  type: string
- container: ''
  name: action
  type: string
- container: set
  name: warnings
  type: string
- container: ''
  name: precision
  type: integer
- container: ''
  name: scale
  type: integer
- container: ''
  name: min
  type: decimal
- container: ''
  name: max
  type: decimal
- container: ''
  name: op
  type: string
- container: ''
  name: parentType
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: done
  type: boolean
- container: ''
  name: nextPageToken
  type: string
- container: ''
  name: idpProvider
  type: string
- container: ''
  name: idpRef
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: primaryEmail
  type: string
- container: ''
  name: algorithm
  type: string
- container: ''
  name: publicKeyPem
  type: string
- container: ''
  name: externalRef
  type: string
- container: ''
  name: clientId
  type: string
- container: ''
  name: invitedEmail
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: mappedObjectName
  type: string
property_count: 113
provider_name: Ampersand
provider_slug: ampersand
slug: ampersand-api-context
source_filename: ampersand-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amp\": \"https://withampersand.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssociationLabels\": \"amp:AssociationLabels\",\n    \"singular\": {\n      \"@id\": \"amp:singular\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plural\": {\n      \"@id\": \"amp:plural\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Oauth2AuthorizationCode\": \"amp:Oauth2AuthorizationCode\",\n    \"accessToken\": {\n      \"@id\": \"amp:accessToken\",\n      \"@type\": \"@id\"\n    },\n    \"refreshToken\": {\n      \"@id\": \"amp:refreshToken\",\n      \"@type\": \"@id\"\n    },\n    \"scopes\": {\n      \"@id\": \"amp:scopes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PatchApiKeyRequest\": \"amp:PatchApiKeyRequest\",\n    \"updateMask\": {\n      \"@id\": \"amp:updateMask\",\n \
  \     \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiKey\": {\n      \"@id\": \"amp:apiKey\",\n      \"@type\": \"@id\"\n    },\n    \"Project\": \"amp:Project\",\n    \"id\": {\n      \"@id\": \"amp:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"appName\": {\n      \"@id\": \"amp:appName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orgId\": {\n      \"@id\": \"amp:orgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"amp:createTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTime\": {\n      \"@id\": \"amp:updateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"entitlements\": {\n      \"@id\": \"amp:entitlements\",\n      \"@type\": \"@id\"\n    },\n    \"HydratedRevision\": \"amp:HydratedRevision\",\n    \"specVersion\": {\n      \"@id\": \"amp:specVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"amp:content\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Destination\": \"amp:Destination\",\n    \"type\": {\n      \"@id\": \"amp:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"amp:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"FieldDefinition\": \"amp:FieldDefinition\",\n    \"fieldName\": {\n      \"@id\": \"amp:fieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"amp:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"valueType\": {\n      \"@id\": \"amp:valueType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"required\": {\n      \"@id\": \"amp:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"unique\": {\n      \"@id\": \"amp:unique\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"indexed\": {\n      \"@id\": \"amp:indexed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"stringOptions\": {\n      \"@id\": \"amp:stringOptions\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"numericOptions\": {\n      \"@id\": \"amp:numericOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"association\": {\n      \"@id\": \"amp:association\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpsertMetadataRequest\": \"amp:UpsertMetadataRequest\",\n    \"groupRef\": {\n      \"@id\": \"amp:groupRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fields\": {\n      \"@id\": \"amp:fields\",\n      \"@type\": \"@id\"\n    },\n    \"NotificationEventTopicRoute\": \"amp:NotificationEventTopicRoute\",\n    \"eventType\": {\n      \"@id\": \"amp:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topicId\": {\n      \"@id\": \"amp:topicId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"amp:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BillingAccount\": \"amp:BillingAccount\",\n    \"billingProvider\": {\n      \"@id\": \"amp:billingProvider\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"billingProviderRef\": {\n      \"@id\": \"amp:billingProviderRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BuilderInfo\": \"amp:BuilderInfo\",\n    \"builder\": {\n      \"@id\": \"amp:builder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectRoles\": {\n      \"@id\": \"amp:projectRoles\",\n      \"@type\": \"@id\"\n    },\n    \"orgRole\": {\n      \"@id\": \"amp:orgRole\",\n      \"@type\": \"@id\"\n    },\n    \"WebhookHeaders\": \"amp:WebhookHeaders\",\n    \"ProviderAppMetadata\": \"amp:ProviderAppMetadata\",\n    \"authQueryParams\": {\n      \"@id\": \"amp:authQueryParams\",\n      \"@type\": \"@id\"\n    },\n    \"providerParams\": {\n      \"@id\": \"amp:providerParams\",\n      \"@type\": \"@id\"\n    },\n    \"JWTKeyResponse\": \"amp:JWTKeyResponse\",\n    \"kid\": {\n      \"@id\": \"amp:kid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Oauth2AuthorizationCodeTokensOnly\": \"amp:Oauth2AuthorizationCodeTokensOnly\",\n    \"\
  StringFieldOptions\": \"amp:StringFieldOptions\",\n    \"length\": {\n      \"@id\": \"amp:length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pattern\": {\n      \"@id\": \"amp:pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"amp:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valuesRestricted\": {\n      \"@id\": \"amp:valuesRestricted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"amp:defaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Org\": \"amp:Org\",\n    \"label\": {\n      \"@id\": \"amp:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultTeamId\": {\n      \"@id\": \"amp:defaultTeamId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpsertMetadataResponse\": \"amp:UpsertMetadataResponse\",\n    \"success\": {\n      \"@id\": \"amp:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"UpdateConnectionRequest\": \"amp:UpdateConnectionRequest\"\
  ,\n    \"connection\": {\n      \"@id\": \"amp:connection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Topic\": \"amp:Topic\",\n    \"ProviderMetadataInfo\": \"amp:ProviderMetadataInfo\",\n    \"value\": {\n      \"@id\": \"amp:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amp:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BackfillProgress\": \"amp:BackfillProgress\",\n    \"installationId\": {\n      \"@id\": \"amp:installationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectName\": {\n      \"@id\": \"amp:objectName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationId\": {\n      \"@id\": \"amp:operationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordsProcessed\": {\n      \"@id\": \"amp:recordsProcessed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recordsEstimatedTotal\": {\n      \"@id\": \"amp:recordsEstimatedTotal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ConnectionRequest\"\
  : \"amp:ConnectionRequest\",\n    \"providerWorkspaceRef\": {\n      \"@id\": \"amp:providerWorkspaceRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providerMetadata\": {\n      \"@id\": \"amp:providerMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupName\": {\n      \"@id\": \"amp:groupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumerName\": {\n      \"@id\": \"amp:consumerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumerRef\": {\n      \"@id\": \"amp:consumerRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"amp:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customAuth\": {\n      \"@id\": \"amp:customAuth\",\n      \"@type\": \"@id\"\n    },\n    \"basicAuth\": {\n      \"@id\": \"amp:basicAuth\",\n      \"@type\": \"@id\"\n    },\n    \"oauth2ClientCredentials\": {\n      \"@id\": \"amp:oauth2ClientCredentials\",\n      \"@type\": \"@id\"\n    },\n    \"oauth2PasswordCredentials\":\
  \ {\n      \"@id\": \"amp:oauth2PasswordCredentials\",\n      \"@type\": \"@id\"\n    },\n    \"oauth2AuthorizationCode\": {\n      \"@id\": \"amp:oauth2AuthorizationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApiKeyRequest\": \"amp:ApiKeyRequest\",\n    \"PatchJWTKeyRequest\": \"amp:PatchJWTKeyRequest\",\n    \"jwtKey\": {\n      \"@id\": \"amp:jwtKey\",\n      \"@type\": \"@id\"\n    },\n    \"ApiKey\": \"amp:ApiKey\",\n    \"key\": {\n      \"@id\": \"amp:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active\": {\n      \"@id\": \"amp:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"SignedUrl\": \"amp:SignedUrl\",\n    \"url\": \"schema:url\",\n    \"bucket\": {\n      \"@id\": \"amp:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"amp:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProviderMetadata\": \"amp:ProviderMetadata\",\n    \"DestinationWithSecrets\": \"amp:DestinationWithSecrets\",\n    \"secrets\"\
  : {\n      \"@id\": \"amp:secrets\",\n      \"@type\": \"@id\"\n    },\n    \"Integration\": \"amp:Integration\",\n    \"latestRevision\": {\n      \"@id\": \"amp:latestRevision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Config\": \"amp:Config\",\n    \"revisionId\": {\n      \"@id\": \"amp:revisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdBy\": {\n      \"@id\": \"amp:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociationDefinition\": \"amp:AssociationDefinition\",\n    \"associationType\": {\n      \"@id\": \"amp:associationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetObject\": {\n      \"@id\": \"amp:targetObject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetField\": {\n      \"@id\": \"amp:targetField\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardinality\": {\n      \"@id\": \"amp:cardinality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onDelete\": {\n      \"@id\": \"amp:onDelete\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"reverseLookupFieldName\": {\n      \"@id\": \"amp:reverseLookupFieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"amp:labels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Installation\": \"amp:Installation\",\n    \"integrationId\": {\n      \"@id\": \"amp:integrationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"amp:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"healthStatus\": {\n      \"@id\": \"amp:healthStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastOperationStatus\": {\n      \"@id\": \"amp:lastOperationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"config\": {\n      \"@id\": \"amp:config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TopicDestinationRoute\": \"amp:TopicDestinationRoute\",\n    \"destinationId\": {\n      \"@id\": \"amp:destinationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Revision\": \"amp:Revision\"\
  ,\n    \"FieldUpsertResult\": \"amp:FieldUpsertResult\",\n    \"action\": {\n      \"@id\": \"amp:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warnings\": {\n      \"@id\": \"amp:warnings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NumericFieldOptions\": \"amp:NumericFieldOptions\",\n    \"precision\": {\n      \"@id\": \"amp:precision\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scale\": {\n      \"@id\": \"amp:scale\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"min\": {\n      \"@id\": \"amp:min\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"max\": {\n      \"@id\": \"amp:max\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"JSONPatchOperation\": \"amp:JSONPatchOperation\",\n    \"op\": {\n      \"@id\": \"amp:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClaimedDomainResponse\": \"amp:ClaimedDomainResponse\",\n    \"parentType\": {\n      \"@id\": \"amp:parentType\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"parentId\": {\n      \"@id\": \"amp:parentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"amp:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaginationInfo\": \"amp:PaginationInfo\",\n    \"done\": {\n      \"@id\": \"amp:done\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nextPageToken\": {\n      \"@id\": \"amp:nextPageToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Builder\": \"amp:Builder\",\n    \"idpProvider\": {\n      \"@id\": \"amp:idpProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idpRef\": {\n      \"@id\": \"amp:idpRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"amp:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"amp:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"amp:fullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryEmail\": {\n      \"@id\": \"\
  amp:primaryEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateJWTKeyRequest\": \"amp:CreateJWTKeyRequest\",\n    \"algorithm\": {\n      \"@id\": \"amp:algorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicKeyPem\": {\n      \"@id\": \"amp:publicKeyPem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProviderApp\": \"amp:ProviderApp\",\n    \"externalRef\": {\n      \"@id\": \"amp:externalRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"amp:clientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Invite\": \"amp:Invite\",\n    \"invitedEmail\": {\n      \"@id\": \"amp:invitedEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amp:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ObjectMetadata\": \"amp:ObjectMetadata\",\n    \"mappedObjectName\": {\n      \"@id\": \"amp:mappedObjectName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JWTKey\": \"amp:JWTKey\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ampersand/refs/heads/main/json-ld/ampersand-api-context.jsonld
tags:
- Developer Tools
- Integrations
- Platform
- SaaS
- OAuth
- Data Sync
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---

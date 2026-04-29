---
api_specs:
- filename: amazon-iot-sitewise-openapi-original.yml
  format: yaml
  label: AWS IoT SiteWise API
  slug: aws-iot-sitewise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-sitewise/refs/heads/main/openapi/amazon-iot-sitewise-openapi-original.yml
class_count: 102
classes:
- AccessPolicySummary
- AggregatedValue
- Aggregates
- Alarms
- AssetCompositeModel
- AssetErrorDetails
- AssetHierarchy
- AssetHierarchyInfo
- AssetModelCompositeModel
- AssetModelCompositeModelDefinition
- AssetModelHierarchy
- AssetModelHierarchyDefinition
- AssetModelProperty
- AssetModelPropertyDefinition
- AssetModelPropertySummary
- AssetModelStatus
- AssetModelSummary
- AssetProperty
- AssetPropertySummary
- AssetPropertyValue
- AssetRelationshipSummary
- AssetStatus
- AssetSummary
- AssociateAssetsRequest
- AssociateTimeSeriesToAssetPropertyRequest
- AssociatedAssetsSummary
- Attribute
- BatchAssociateProjectAssetsRequest
- BatchAssociateProjectAssetsResponse
- BatchDisassociateProjectAssetsRequest
- BatchDisassociateProjectAssetsResponse
- BatchGetAssetPropertyAggregatesEntry
- BatchGetAssetPropertyAggregatesErrorEntry
- BatchGetAssetPropertyAggregatesErrorInfo
- BatchGetAssetPropertyAggregatesRequest
- BatchGetAssetPropertyAggregatesResponse
- BatchGetAssetPropertyAggregatesSkippedEntry
- BatchGetAssetPropertyAggregatesSuccessEntry
- BatchGetAssetPropertyValueEntry
- BatchGetAssetPropertyValueErrorEntry
- BatchGetAssetPropertyValueErrorInfo
- BatchGetAssetPropertyValueHistoryEntry
- BatchGetAssetPropertyValueHistoryErrorEntry
- BatchGetAssetPropertyValueHistoryErrorInfo
- BatchGetAssetPropertyValueHistoryRequest
- BatchGetAssetPropertyValueHistoryResponse
- BatchGetAssetPropertyValueHistorySkippedEntry
- BatchGetAssetPropertyValueHistorySuccessEntry
- BatchGetAssetPropertyValueRequest
- BatchGetAssetPropertyValueResponse
- BatchGetAssetPropertyValueSkippedEntry
- BatchGetAssetPropertyValueSuccessEntry
- BatchPutAssetPropertyError
- BatchPutAssetPropertyErrorEntry
- BatchPutAssetPropertyValueRequest
- BatchPutAssetPropertyValueResponse
- CompositeModelProperty
- CreateAccessPolicyResponse
- CreateAssetModelResponse
- CreateAssetResponse
- CreateBulkImportJobResponse
- CreateDashboardResponse
- CreateGatewayResponse
- CreatePortalResponse
- CreateProjectResponse
- CustomerManagedS3Storage
- DeleteAccessPolicyResponse
- DeleteAssetModelResponse
- DeleteAssetResponse
- DeleteDashboardResponse
- DeletePortalResponse
- DeleteProjectResponse
- DescribeAccessPolicyResponse
- DescribeAssetModelResponse
- DescribeAssetPropertyResponse
- DescribeAssetResponse
- DescribeBulkImportJobResponse
- DescribeDashboardResponse
- DescribeDefaultEncryptionConfigurationResponse
- DescribeGatewayCapabilityConfigurationResponse
- DescribeGatewayResponse
- DescribeLoggingOptionsResponse
- DescribePortalResponse
- DescribeProjectResponse
- DescribeStorageConfigurationResponse
- DescribeTimeSeriesResponse
- ErrorDetails
- File
- FileFormat
- GetAssetPropertyAggregatesResponse
- GetAssetPropertyValueHistoryResponse
- GetAssetPropertyValueResponse
- GetInterpolatedAssetPropertyValuesResponse
- Greengrass
- GreengrassV2
- GroupIdentity
- IAMRoleIdentity
- IAMUserIdentity
- Identity
- ImageFile
- description
- name
context_file: json-ld/amazon-iot-sitewise-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-sitewise/refs/heads/main/json-ld/amazon-iot-sitewise-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iot Sitewise from Amazon IoT SiteWise.
layout: jsonld
name: Amazon Iot Sitewise Context
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
  name: TimeSeriesSummaries
  type: string
- container: ''
  name: accessPolicyArn
  type: string
- container: ''
  name: accessPolicyCreationDate
  type: string
- container: ''
  name: accessPolicyId
  type: string
- container: ''
  name: accessPolicyIdentity
  type: string
- container: ''
  name: accessPolicyLastUpdateDate
  type: string
- container: ''
  name: accessPolicyPermission
  type: string
- container: ''
  name: accessPolicyResource
  type: string
- container: ''
  name: accessPolicySummaries
  type: string
- container: ''
  name: aggregateTypes
  type: string
- container: ''
  name: aggregatedValues
  type: string
- container: ''
  name: alarmRoleArn
  type: string
- container: ''
  name: alarms
  type: string
- container: ''
  name: alias
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: assetArn
  type: string
- container: ''
  name: assetCompositeModelId
  type: string
- container: ''
  name: assetCompositeModels
  type: string
- container: ''
  name: assetCreationDate
  type: string
- container: ''
  name: assetDescription
  type: string
- container: ''
  name: assetHierarchies
  type: string
- container: ''
  name: assetId
  type: string
- container: ''
  name: assetIds
  type: string
- container: ''
  name: assetLastUpdateDate
  type: string
- container: ''
  name: assetModelArn
  type: string
- container: ''
  name: assetModelCompositeModelId
  type: string
- container: ''
  name: assetModelCompositeModels
  type: string
- container: ''
  name: assetModelCreationDate
  type: string
- container: ''
  name: assetModelDescription
  type: string
- container: ''
  name: assetModelHierarchies
  type: string
- container: ''
  name: assetModelId
  type: string
- container: ''
  name: assetModelLastUpdateDate
  type: string
- container: ''
  name: assetModelName
  type: string
- container: ''
  name: assetModelProperties
  type: string
- container: ''
  name: assetModelPropertySummaries
  type: string
- container: ''
  name: assetModelStatus
  type: string
- container: ''
  name: assetModelSummaries
  type: string
- container: ''
  name: assetName
  type: string
- container: ''
  name: assetProperties
  type: string
- container: ''
  name: assetProperty
  type: string
- container: ''
  name: assetPropertySummaries
  type: string
- container: ''
  name: assetPropertyValue
  type: string
- container: ''
  name: assetPropertyValueHistory
  type: string
- container: ''
  name: assetRelationshipSummaries
  type: string
- container: ''
  name: assetStatus
  type: string
- container: ''
  name: assetSummaries
  type: string
- container: ''
  name: attribute
  type: string
- container: ''
  name: average
  type: string
- container: ''
  name: booleanValue
  type: string
- container: ''
  name: bucket
  type: string
- container: ''
  name: capabilityConfiguration
  type: string
- container: ''
  name: capabilityNamespace
  type: string
- container: ''
  name: capabilitySyncStatus
  type: string
- container: ''
  name: childAssetId
  type: string
- container: ''
  name: childAssetModelId
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: completionStatus
  type: string
- container: ''
  name: compositeModel
  type: string
- container: ''
  name: configurationStatus
  type: string
- container: ''
  name: coreDeviceThingName
  type: string
- container: ''
  name: count
  type: string
- container: ''
  name: creationDate
  type: string
- container: ''
  name: csv
  type: string
- container: ''
  name: dashboardArn
  type: string
- container: ''
  name: dashboardCreationDate
  type: string
- container: ''
  name: dashboardDefinition
  type: string
- container: ''
  name: dashboardDescription
  type: string
- container: ''
  name: dashboardId
  type: string
- container: ''
  name: dashboardLastUpdateDate
  type: string
- container: ''
  name: dashboardName
  type: string
- container: ''
  name: dashboardSummaries
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: dataTypeSpec
  type: string
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: details
  type: string
- container: ''
  name: disassociatedDataStorage
  type: string
- container: ''
  name: doubleValue
  type: string
- container: ''
  name: encryptionType
  type: string
- container: ''
  name: endDate
  type: string
- container: ''
  name: entries
  type: string
- container: ''
  name: entryId
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
  name: errorInfo
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: errorReportLocation
  type: string
- container: ''
  name: errorTimestamp
  type: string
- container: ''
  name: errors
  type: string
- container: ''
  name: files
  type: string
- container: ''
  name: gatewayArn
  type: string
- container: ''
  name: gatewayCapabilitySummaries
  type: string
- container: ''
  name: gatewayId
  type: string
- container: ''
  name: gatewayName
  type: string
- container: ''
  name: gatewayPlatform
  type: string
- container: ''
  name: gatewaySummaries
  type: string
- container: ''
  name: group
  type: string
- container: ''
  name: groupArn
  type: string
- container: ''
  name: hierarchies
  type: string
- container: ''
  name: hierarchyId
  type: string
- container: ''
  name: hierarchyInfo
  type: string
- container: ''
  name: iamRole
  type: string
- container: ''
  name: iamUser
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: identity
  type: string
- container: ''
  name: integerValue
  type: string
- container: ''
  name: interpolatedAssetPropertyValues
  type: string
- container: ''
  name: jobConfiguration
  type: string
- container: ''
  name: jobCreationDate
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: jobLastUpdateDate
  type: string
- container: ''
  name: jobName
  type: string
- container: ''
  name: jobRoleArn
  type: string
- container: ''
  name: jobStatus
  type: string
- container: ''
  name: jobSummaries
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: kmsKeyArn
  type: string
- container: ''
  name: lastUpdateDate
  type: string
- container: ''
  name: loggingOptions
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: maximum
  type: string
- container: ''
  name: measurement
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: metric
  type: string
- container: ''
  name: minimum
  type: string
- container: ''
  name: multiLayerStorage
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: notification
  type: string
- container: ''
  name: notificationLambdaArn
  type: string
- container: ''
  name: notificationSenderEmail
  type: string
- container: ''
  name: offsetInNanos
  type: string
- container: ''
  name: parentAssetId
  type: string
- container: ''
  name: permission
  type: string
- container: ''
  name: portal
  type: string
- container: ''
  name: portalArn
  type: string
- container: ''
  name: portalAuthMode
  type: string
- container: ''
  name: portalClientId
  type: string
- container: ''
  name: portalContactEmail
  type: string
- container: ''
  name: portalCreationDate
  type: string
- container: ''
  name: portalDescription
  type: string
- container: ''
  name: portalId
  type: string
- container: ''
  name: portalLastUpdateDate
  type: string
- container: ''
  name: portalLogoImageLocation
  type: string
- container: ''
  name: portalName
  type: string
- container: ''
  name: portalStartUrl
  type: string
- container: ''
  name: portalStatus
  type: string
- container: ''
  name: portalSummaries
  type: string
- container: ''
  name: project
  type: string
- container: ''
  name: projectArn
  type: string
- container: ''
  name: projectCreationDate
  type: string
- container: ''
  name: projectDescription
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: projectLastUpdateDate
  type: string
- container: ''
  name: projectName
  type: string
- container: ''
  name: projectSummaries
  type: string
- container: ''
  name: properties
  type: string
- container: ''
  name: propertyAlias
  type: string
- container: ''
  name: propertyId
  type: string
- container: ''
  name: propertyValue
  type: string
- container: ''
  name: propertyValues
  type: string
- container: ''
  name: qualities
  type: string
- container: ''
  name: quality
  type: string
- container: ''
  name: relationshipType
  type: string
- container: ''
  name: resolution
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: retentionPeriod
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: s3ResourceArn
  type: string
- container: ''
  name: skippedEntries
  type: string
- container: ''
  name: ssoApplicationId
  type: string
- container: ''
  name: standardDeviation
  type: string
- container: ''
  name: startDate
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: storageType
  type: string
- container: ''
  name: stringValue
  type: string
- container: ''
  name: successEntries
  type: string
- container: ''
  name: sum
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: timeInSeconds
  type: string
- container: ''
  name: timeOrdering
  type: string
- container: ''
  name: timeSeriesArn
  type: string
- container: ''
  name: timeSeriesCreationDate
  type: string
- container: ''
  name: timeSeriesId
  type: string
- container: ''
  name: timeSeriesLastUpdateDate
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: timestamps
  type: string
- container: ''
  name: topic
  type: string
- container: ''
  name: transform
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: versionId
  type: string
property_count: 196
provider_name: Amazon IoT SiteWise
provider_slug: amazon-iot-sitewise
slug: amazon-iot-sitewise-context
source_filename: amazon-iot-sitewise-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessPolicySummary\": \"amzn:AccessPolicySummary\",\n    \"AggregatedValue\": \"amzn:AggregatedValue\",\n    \"Aggregates\": \"amzn:Aggregates\",\n    \"Alarms\": \"amzn:Alarms\",\n    \"AssetCompositeModel\": \"amzn:AssetCompositeModel\",\n    \"AssetErrorDetails\": \"amzn:AssetErrorDetails\",\n    \"AssetHierarchy\": \"amzn:AssetHierarchy\",\n    \"AssetHierarchyInfo\": \"amzn:AssetHierarchyInfo\",\n    \"AssetModelCompositeModel\": \"amzn:AssetModelCompositeModel\",\n    \"AssetModelCompositeModelDefinition\": \"amzn:AssetModelCompositeModelDefinition\",\n    \"AssetModelHierarchy\": \"amzn:AssetModelHierarchy\",\n    \"AssetModelHierarchyDefinition\": \"amzn:AssetModelHierarchyDefinition\",\n    \"AssetModelProperty\": \"amzn:AssetModelProperty\"\
  ,\n    \"AssetModelPropertyDefinition\": \"amzn:AssetModelPropertyDefinition\",\n    \"AssetModelPropertySummary\": \"amzn:AssetModelPropertySummary\",\n    \"AssetModelStatus\": \"amzn:AssetModelStatus\",\n    \"AssetModelSummary\": \"amzn:AssetModelSummary\",\n    \"AssetProperty\": \"amzn:AssetProperty\",\n    \"AssetPropertySummary\": \"amzn:AssetPropertySummary\",\n    \"AssetPropertyValue\": \"amzn:AssetPropertyValue\",\n    \"AssetRelationshipSummary\": \"amzn:AssetRelationshipSummary\",\n    \"AssetStatus\": \"amzn:AssetStatus\",\n    \"AssetSummary\": \"amzn:AssetSummary\",\n    \"AssociateAssetsRequest\": \"amzn:AssociateAssetsRequest\",\n    \"AssociateTimeSeriesToAssetPropertyRequest\": \"amzn:AssociateTimeSeriesToAssetPropertyRequest\",\n    \"AssociatedAssetsSummary\": \"amzn:AssociatedAssetsSummary\",\n    \"Attribute\": \"amzn:Attribute\",\n    \"BatchAssociateProjectAssetsRequest\": \"amzn:BatchAssociateProjectAssetsRequest\",\n    \"BatchAssociateProjectAssetsResponse\"\
  : \"amzn:BatchAssociateProjectAssetsResponse\",\n    \"BatchDisassociateProjectAssetsRequest\": \"amzn:BatchDisassociateProjectAssetsRequest\",\n    \"BatchDisassociateProjectAssetsResponse\": \"amzn:BatchDisassociateProjectAssetsResponse\",\n    \"BatchGetAssetPropertyAggregatesEntry\": \"amzn:BatchGetAssetPropertyAggregatesEntry\",\n    \"BatchGetAssetPropertyAggregatesErrorEntry\": \"amzn:BatchGetAssetPropertyAggregatesErrorEntry\",\n    \"BatchGetAssetPropertyAggregatesErrorInfo\": \"amzn:BatchGetAssetPropertyAggregatesErrorInfo\",\n    \"BatchGetAssetPropertyAggregatesRequest\": \"amzn:BatchGetAssetPropertyAggregatesRequest\",\n    \"BatchGetAssetPropertyAggregatesResponse\": \"amzn:BatchGetAssetPropertyAggregatesResponse\",\n    \"BatchGetAssetPropertyAggregatesSkippedEntry\": \"amzn:BatchGetAssetPropertyAggregatesSkippedEntry\",\n    \"BatchGetAssetPropertyAggregatesSuccessEntry\": \"amzn:BatchGetAssetPropertyAggregatesSuccessEntry\",\n    \"BatchGetAssetPropertyValueEntry\": \"\
  amzn:BatchGetAssetPropertyValueEntry\",\n    \"BatchGetAssetPropertyValueErrorEntry\": \"amzn:BatchGetAssetPropertyValueErrorEntry\",\n    \"BatchGetAssetPropertyValueErrorInfo\": \"amzn:BatchGetAssetPropertyValueErrorInfo\",\n    \"BatchGetAssetPropertyValueHistoryEntry\": \"amzn:BatchGetAssetPropertyValueHistoryEntry\",\n    \"BatchGetAssetPropertyValueHistoryErrorEntry\": \"amzn:BatchGetAssetPropertyValueHistoryErrorEntry\",\n    \"BatchGetAssetPropertyValueHistoryErrorInfo\": \"amzn:BatchGetAssetPropertyValueHistoryErrorInfo\",\n    \"BatchGetAssetPropertyValueHistoryRequest\": \"amzn:BatchGetAssetPropertyValueHistoryRequest\",\n    \"BatchGetAssetPropertyValueHistoryResponse\": \"amzn:BatchGetAssetPropertyValueHistoryResponse\",\n    \"BatchGetAssetPropertyValueHistorySkippedEntry\": \"amzn:BatchGetAssetPropertyValueHistorySkippedEntry\",\n    \"BatchGetAssetPropertyValueHistorySuccessEntry\": \"amzn:BatchGetAssetPropertyValueHistorySuccessEntry\",\n    \"BatchGetAssetPropertyValueRequest\"\
  : \"amzn:BatchGetAssetPropertyValueRequest\",\n    \"BatchGetAssetPropertyValueResponse\": \"amzn:BatchGetAssetPropertyValueResponse\",\n    \"BatchGetAssetPropertyValueSkippedEntry\": \"amzn:BatchGetAssetPropertyValueSkippedEntry\",\n    \"BatchGetAssetPropertyValueSuccessEntry\": \"amzn:BatchGetAssetPropertyValueSuccessEntry\",\n    \"BatchPutAssetPropertyError\": \"amzn:BatchPutAssetPropertyError\",\n    \"BatchPutAssetPropertyErrorEntry\": \"amzn:BatchPutAssetPropertyErrorEntry\",\n    \"BatchPutAssetPropertyValueRequest\": \"amzn:BatchPutAssetPropertyValueRequest\",\n    \"BatchPutAssetPropertyValueResponse\": \"amzn:BatchPutAssetPropertyValueResponse\",\n    \"CompositeModelProperty\": \"amzn:CompositeModelProperty\",\n    \"CreateAccessPolicyResponse\": \"amzn:CreateAccessPolicyResponse\",\n    \"CreateAssetModelResponse\": \"amzn:CreateAssetModelResponse\",\n    \"CreateAssetResponse\": \"amzn:CreateAssetResponse\",\n    \"CreateBulkImportJobResponse\": \"amzn:CreateBulkImportJobResponse\"\
  ,\n    \"CreateDashboardResponse\": \"amzn:CreateDashboardResponse\",\n    \"CreateGatewayResponse\": \"amzn:CreateGatewayResponse\",\n    \"CreatePortalResponse\": \"amzn:CreatePortalResponse\",\n    \"CreateProjectResponse\": \"amzn:CreateProjectResponse\",\n    \"CustomerManagedS3Storage\": \"amzn:CustomerManagedS3Storage\",\n    \"DeleteAccessPolicyResponse\": \"amzn:DeleteAccessPolicyResponse\",\n    \"DeleteAssetModelResponse\": \"amzn:DeleteAssetModelResponse\",\n    \"DeleteAssetResponse\": \"amzn:DeleteAssetResponse\",\n    \"DeleteDashboardResponse\": \"amzn:DeleteDashboardResponse\",\n    \"DeletePortalResponse\": \"amzn:DeletePortalResponse\",\n    \"DeleteProjectResponse\": \"amzn:DeleteProjectResponse\",\n    \"DescribeAccessPolicyResponse\": \"amzn:DescribeAccessPolicyResponse\",\n    \"DescribeAssetModelResponse\": \"amzn:DescribeAssetModelResponse\",\n    \"DescribeAssetPropertyResponse\": \"amzn:DescribeAssetPropertyResponse\",\n    \"DescribeAssetResponse\": \"amzn:DescribeAssetResponse\"\
  ,\n    \"DescribeBulkImportJobResponse\": \"amzn:DescribeBulkImportJobResponse\",\n    \"DescribeDashboardResponse\": \"amzn:DescribeDashboardResponse\",\n    \"DescribeDefaultEncryptionConfigurationResponse\": \"amzn:DescribeDefaultEncryptionConfigurationResponse\",\n    \"DescribeGatewayCapabilityConfigurationResponse\": \"amzn:DescribeGatewayCapabilityConfigurationResponse\",\n    \"DescribeGatewayResponse\": \"amzn:DescribeGatewayResponse\",\n    \"DescribeLoggingOptionsResponse\": \"amzn:DescribeLoggingOptionsResponse\",\n    \"DescribePortalResponse\": \"amzn:DescribePortalResponse\",\n    \"DescribeProjectResponse\": \"amzn:DescribeProjectResponse\",\n    \"DescribeStorageConfigurationResponse\": \"amzn:DescribeStorageConfigurationResponse\",\n    \"DescribeTimeSeriesResponse\": \"amzn:DescribeTimeSeriesResponse\",\n    \"ErrorDetails\": \"amzn:ErrorDetails\",\n    \"File\": \"amzn:File\",\n    \"FileFormat\": \"amzn:FileFormat\",\n    \"GetAssetPropertyAggregatesResponse\": \"\
  amzn:GetAssetPropertyAggregatesResponse\",\n    \"GetAssetPropertyValueHistoryResponse\": \"amzn:GetAssetPropertyValueHistoryResponse\",\n    \"GetAssetPropertyValueResponse\": \"amzn:GetAssetPropertyValueResponse\",\n    \"GetInterpolatedAssetPropertyValuesResponse\": \"amzn:GetInterpolatedAssetPropertyValuesResponse\",\n    \"Greengrass\": \"amzn:Greengrass\",\n    \"GreengrassV2\": \"amzn:GreengrassV2\",\n    \"GroupIdentity\": \"amzn:GroupIdentity\",\n    \"IAMRoleIdentity\": \"amzn:IAMRoleIdentity\",\n    \"IAMUserIdentity\": \"amzn:IAMUserIdentity\",\n    \"Identity\": \"amzn:Identity\",\n    \"ImageFile\": \"amzn:ImageFile\",\n    \"TimeSeriesSummaries\": {\n      \"@id\": \"amzn:TimeSeriesSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPolicyArn\": {\n      \"@id\": \"amzn:accessPolicyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPolicyCreationDate\": {\n      \"@id\": \"amzn:accessPolicyCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"accessPolicyId\": {\n      \"@id\": \"amzn:accessPolicyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPolicyIdentity\": {\n      \"@id\": \"amzn:accessPolicyIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPolicyLastUpdateDate\": {\n      \"@id\": \"amzn:accessPolicyLastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPolicyPermission\": {\n      \"@id\": \"amzn:accessPolicyPermission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPolicyResource\": {\n      \"@id\": \"amzn:accessPolicyResource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPolicySummaries\": {\n      \"@id\": \"amzn:accessPolicySummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregateTypes\": {\n      \"@id\": \"amzn:aggregateTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregatedValues\": {\n      \"@id\": \"amzn:aggregatedValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmRoleArn\": {\n      \"@id\": \"amzn:alarmRoleArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"alarms\": {\n      \"@id\": \"amzn:alarms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alias\": {\n      \"@id\": \"amzn:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetArn\": {\n      \"@id\": \"amzn:assetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetCompositeModelId\": {\n      \"@id\": \"amzn:assetCompositeModelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetCompositeModels\": {\n      \"@id\": \"amzn:assetCompositeModels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetCreationDate\": {\n      \"@id\": \"amzn:assetCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetDescription\": {\n      \"@id\": \"amzn:assetDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetHierarchies\": {\n      \"@id\": \"amzn:assetHierarchies\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"assetId\": {\n      \"@id\": \"amzn:assetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetIds\": {\n      \"@id\": \"amzn:assetIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetLastUpdateDate\": {\n      \"@id\": \"amzn:assetLastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelArn\": {\n      \"@id\": \"amzn:assetModelArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelCompositeModelId\": {\n      \"@id\": \"amzn:assetModelCompositeModelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelCompositeModels\": {\n      \"@id\": \"amzn:assetModelCompositeModels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelCreationDate\": {\n      \"@id\": \"amzn:assetModelCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelDescription\": {\n      \"@id\": \"amzn:assetModelDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelHierarchies\": {\n      \"@id\": \"amzn:assetModelHierarchies\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelId\": {\n      \"@id\": \"amzn:assetModelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelLastUpdateDate\": {\n      \"@id\": \"amzn:assetModelLastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelName\": {\n      \"@id\": \"amzn:assetModelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelProperties\": {\n      \"@id\": \"amzn:assetModelProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelPropertySummaries\": {\n      \"@id\": \"amzn:assetModelPropertySummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelStatus\": {\n      \"@id\": \"amzn:assetModelStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelSummaries\": {\n      \"@id\": \"amzn:assetModelSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetName\": {\n      \"@id\": \"amzn:assetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetProperties\": {\n\
  \      \"@id\": \"amzn:assetProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetProperty\": {\n      \"@id\": \"amzn:assetProperty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetPropertySummaries\": {\n      \"@id\": \"amzn:assetPropertySummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetPropertyValue\": {\n      \"@id\": \"amzn:assetPropertyValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetPropertyValueHistory\": {\n      \"@id\": \"amzn:assetPropertyValueHistory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetRelationshipSummaries\": {\n      \"@id\": \"amzn:assetRelationshipSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetStatus\": {\n      \"@id\": \"amzn:assetStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetSummaries\": {\n      \"@id\": \"amzn:assetSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attribute\": {\n      \"@id\": \"amzn:attribute\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"average\": {\n      \"@id\": \"amzn:average\",\n      \"@type\": \"xsd:string\"\n    },\n    \"booleanValue\": {\n      \"@id\": \"amzn:booleanValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucket\": {\n      \"@id\": \"amzn:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilityConfiguration\": {\n      \"@id\": \"amzn:capabilityConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilityNamespace\": {\n      \"@id\": \"amzn:capabilityNamespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilitySyncStatus\": {\n      \"@id\": \"amzn:capabilitySyncStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"childAssetId\": {\n      \"@id\": \"amzn:childAssetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"childAssetModelId\": {\n      \"@id\": \"amzn:childAssetModelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amzn:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\"\
  : {\n      \"@id\": \"amzn:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completionStatus\": {\n      \"@id\": \"amzn:completionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compositeModel\": {\n      \"@id\": \"amzn:compositeModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationStatus\": {\n      \"@id\": \"amzn:configurationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coreDeviceThingName\": {\n      \"@id\": \"amzn:coreDeviceThingName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"amzn:count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"amzn:creationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"csv\": {\n      \"@id\": \"amzn:csv\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardArn\": {\n      \"@id\": \"amzn:dashboardArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardCreationDate\": {\n      \"@id\": \"amzn:dashboardCreationDate\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardDefinition\": {\n      \"@id\": \"amzn:dashboardDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardDescription\": {\n      \"@id\": \"amzn:dashboardDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardId\": {\n      \"@id\": \"amzn:dashboardId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardLastUpdateDate\": {\n      \"@id\": \"amzn:dashboardLastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardName\": {\n      \"@id\": \"amzn:dashboardName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashboardSummaries\": {\n      \"@id\": \"amzn:dashboardSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"amzn:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataType\": {\n      \"@id\": \"amzn:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataTypeSpec\": {\n      \"@id\": \"amzn:dataTypeSpec\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"amzn:defaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"details\": {\n      \"@id\": \"amzn:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disassociatedDataStorage\": {\n      \"@id\": \"amzn:disassociatedDataStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"doubleValue\": {\n      \"@id\": \"amzn:doubleValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionType\": {\n      \"@id\": \"amzn:encryptionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endDate\": {\n      \"@id\": \"amzn:endDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entries\": {\n      \"@id\": \"amzn:entries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entryId\": {\n      \"@id\": \"amzn:entryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"amzn:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\"\
  : {\n      \"@id\": \"amzn:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorEntries\": {\n      \"@id\": \"amzn:errorEntries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorInfo\": {\n      \"@id\": \"amzn:errorInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"amzn:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorReportLocation\": {\n      \"@id\": \"amzn:errorReportLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorTimestamp\": {\n      \"@id\": \"amzn:errorTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amzn:errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"amzn:files\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewayArn\": {\n      \"@id\": \"amzn:gatewayArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewayCapabilitySummaries\": {\n      \"@id\": \"amzn:gatewayCapabilitySummaries\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"gatewayId\": {\n      \"@id\": \"amzn:gatewayId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewayName\": {\n      \"@id\": \"amzn:gatewayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewayPlatform\": {\n      \"@id\": \"amzn:gatewayPlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewaySummaries\": {\n      \"@id\": \"amzn:gatewaySummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"amzn:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupArn\": {\n      \"@id\": \"amzn:groupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hierarchies\": {\n      \"@id\": \"amzn:hierarchies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hierarchyId\": {\n      \"@id\": \"amzn:hierarchyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hierarchyInfo\": {\n      \"@id\": \"amzn:hierarchyInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iamRole\": {\n      \"@id\"\
  : \"amzn:iamRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iamUser\": {\n      \"@id\": \"amzn:iamUser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amzn:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identity\": {\n      \"@id\": \"amzn:identity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integerValue\": {\n      \"@id\": \"amzn:integerValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interpolatedAssetPropertyValues\": {\n      \"@id\": \"amzn:interpolatedAssetPropertyValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobConfiguration\": {\n      \"@id\": \"amzn:jobConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobCreationDate\": {\n      \"@id\": \"amzn:jobCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"amzn:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobLastUpdateDate\": {\n      \"@id\": \"amzn:jobLastUpdateDate\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"jobName\": {\n      \"@id\": \"amzn:jobName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobRoleArn\": {\n      \"@id\": \"amzn:jobRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobStatus\": {\n      \"@id\": \"amzn:jobStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobSummaries\": {\n      \"@id\": \"amzn:jobSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amzn:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyArn\": {\n      \"@id\": \"amzn:kmsKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdateDate\": {\n      \"@id\": \"amzn:lastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loggingOptions\": {\n      \"@id\": \"amzn:loggingOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amzn:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximum\": {\n      \"@id\": \"amzn:maximum\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"measurement\": {\n      \"@id\": \"amzn:measurement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amzn:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metric\": {\n      \"@id\": \"amzn:metric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minimum\": {\n      \"@id\": \"amzn:minimum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multiLayerStorage\": {\n      \"@id\": \"amzn:multiLayerStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notification\": {\n      \"@id\": \"amzn:notification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationLambdaArn\": {\n      \"@id\": \"amzn:notificationLambdaArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationSenderEmail\": {\n      \"@id\": \"amzn:notificationSenderEmail\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"offsetInNanos\": {\n      \"@id\": \"amzn:offsetInNanos\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentAssetId\": {\n      \"@id\": \"amzn:parentAssetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permission\": {\n      \"@id\": \"amzn:permission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portal\": {\n      \"@id\": \"amzn:portal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalArn\": {\n      \"@id\": \"amzn:portalArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalAuthMode\": {\n      \"@id\": \"amzn:portalAuthMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalClientId\": {\n      \"@id\": \"amzn:portalClientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalContactEmail\": {\n      \"@id\": \"amzn:portalContactEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalCreationDate\": {\n      \"@id\": \"amzn:portalCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalDescription\": {\n      \"@id\"\
  : \"amzn:portalDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalId\": {\n      \"@id\": \"amzn:portalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalLastUpdateDate\": {\n      \"@id\": \"amzn:portalLastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalLogoImageLocation\": {\n      \"@id\": \"amzn:portalLogoImageLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalName\": {\n      \"@id\": \"amzn:portalName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalStartUrl\": {\n      \"@id\": \"amzn:portalStartUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalStatus\": {\n      \"@id\": \"amzn:portalStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalSummaries\": {\n      \"@id\": \"amzn:portalSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project\": {\n      \"@id\": \"amzn:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectArn\": {\n      \"@id\": \"amzn:projectArn\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"projectCreationDate\": {\n      \"@id\": \"amzn:projectCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectDescription\": {\n      \"@id\": \"amzn:projectDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"amzn:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectLastUpdateDate\": {\n      \"@id\": \"amzn:projectLastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectName\": {\n      \"@id\": \"amzn:projectName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectSummaries\": {\n      \"@id\": \"amzn:projectSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"amzn:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyAlias\": {\n      \"@id\": \"amzn:propertyAlias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyId\": {\n      \"@id\": \"amzn:propertyId\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"propertyValue\": {\n      \"@id\": \"amzn:propertyValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyValues\": {\n      \"@id\": \"amzn:propertyValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"qualities\": {\n      \"@id\": \"amzn:qualities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quality\": {\n      \"@id\": \"amzn:quality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipType\": {\n      \"@id\": \"amzn:relationshipType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"amzn:resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"amzn:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retentionPeriod\": {\n      \"@id\": \"amzn:retentionPeriod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"amzn:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3ResourceArn\": {\n      \"@id\": \"amzn:s3ResourceArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"skippedEntries\": {\n      \"@id\": \"amzn:skippedEntries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssoApplicationId\": {\n      \"@id\": \"amzn:ssoApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standardDeviation\": {\n      \"@id\": \"amzn:standardDeviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"amzn:startDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"amzn:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageType\": {\n      \"@id\": \"amzn:storageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stringValue\": {\n      \"@id\": \"amzn:stringValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"successEntries\": {\n      \"@id\": \"amzn:successEntries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sum\": {\n    \
  \  \"@id\": \"amzn:sum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeInSeconds\": {\n      \"@id\": \"amzn:timeInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeOrdering\": {\n      \"@id\": \"amzn:timeOrdering\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeSeriesArn\": {\n      \"@id\": \"amzn:timeSeriesArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeSeriesCreationDate\": {\n      \"@id\": \"amzn:timeSeriesCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeSeriesId\": {\n      \"@id\": \"amzn:timeSeriesId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeSeriesLastUpdateDate\": {\n      \"@id\": \"amzn:timeSeriesLastUpdateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"amzn:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamps\": {\n      \"@id\": \"amzn:timestamps\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"topic\": {\n      \"@id\": \"amzn:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transform\": {\n      \"@id\": \"amzn:transform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"amzn:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"amzn:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amzn:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionId\": {\n      \"@id\": \"amzn:versionId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-sitewise/refs/heads/main/json-ld/amazon-iot-sitewise-context.jsonld
tags:
- AWS
- Asset Management
- Industrial IoT
- IoT
- Time Series Data
- JSON-LD
- Linked Data
- Semantic Web
---

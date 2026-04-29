---
api_specs:
- filename: amazon-iot-device-management-openapi-original.yml
  format: yaml
  label: AWS IoT Device Management API
  slug: aws-iot-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-management/refs/heads/main/openapi/amazon-iot-device-management-openapi-original.yml
class_count: 102
classes:
- Action
- AddThingToBillingGroupResponse
- AddThingToThingGroupResponse
- AddThingsToThingGroupParams
- AlertTarget
- AssociateTargetsWithJobResponse
- AttachSecurityProfileResponse
- AttachThingPrincipalResponse
- AttributePayload
- Attributes
- AwsJobExponentialRolloutRate
- Behavior
- CancelAuditMitigationActionsTaskResponse
- CancelAuditTaskResponse
- CancelDetectMitigationActionsTaskResponse
- CancelJobResponse
- ClearDefaultAuthorizerResponse
- ConfirmTopicRuleDestinationResponse
- CreateAuditSuppressionResponse
- CreateAuthorizerResponse
- CreateBillingGroupResponse
- CreateCertificateFromCsrResponse
- CreateCustomMetricResponse
- CreateDimensionResponse
- CreateDomainConfigurationResponse
- CreateDynamicThingGroupResponse
- CreateFleetMetricResponse
- CreateJobResponse
- CreateJobTemplateResponse
- CreateKeysAndCertificateResponse
- CreateMitigationActionResponse
- CreateOTAUpdateResponse
- CreatePolicyResponse
- CreatePolicyVersionResponse
- CreateProvisioningClaimResponse
- CreateProvisioningTemplateResponse
- CreateProvisioningTemplateVersionResponse
- CreateRoleAliasResponse
- CreateScheduledAuditResponse
- CreateSecurityProfileResponse
- CreateStreamResponse
- CreateThingGroupResponse
- CreateThingResponse
- CreateThingTypeResponse
- CreateTopicRuleDestinationResponse
- DeleteAccountAuditConfigurationResponse
- DeleteAuditSuppressionResponse
- DeleteAuthorizerResponse
- DeleteBillingGroupResponse
- DeleteCACertificateResponse
- DeleteCustomMetricResponse
- DeleteDimensionResponse
- DeleteDomainConfigurationResponse
- DeleteDynamicThingGroupResponse
- DeleteMitigationActionResponse
- DeleteOTAUpdateResponse
- DeleteProvisioningTemplateResponse
- DeleteProvisioningTemplateVersionResponse
- DeleteRegistrationCodeResponse
- DeleteRoleAliasResponse
- DeleteScheduledAuditResponse
- DeleteSecurityProfileResponse
- DeleteStreamResponse
- DeleteThingGroupResponse
- DeleteThingResponse
- DeleteThingTypeResponse
- DeleteTopicRuleDestinationResponse
- DeprecateThingTypeResponse
- DescribeAccountAuditConfigurationResponse
- DescribeAuditFindingResponse
- DescribeAuditMitigationActionsTaskResponse
- DescribeAuditSuppressionResponse
- DescribeAuditTaskResponse
- DescribeAuthorizerResponse
- DescribeBillingGroupResponse
- DescribeCACertificateResponse
- DescribeCertificateResponse
- DescribeCustomMetricResponse
- DescribeDefaultAuthorizerResponse
- DescribeDetectMitigationActionsTaskResponse
- DescribeDimensionResponse
- DescribeDomainConfigurationResponse
- DescribeEndpointResponse
- DescribeEventConfigurationsResponse
- DescribeFleetMetricResponse
- DescribeIndexResponse
- DescribeJobExecutionResponse
- DescribeJobResponse
- DescribeJobTemplateResponse
- DescribeManagedJobTemplateResponse
- DescribeMitigationActionResponse
- DescribeProvisioningTemplateResponse
- DescribeProvisioningTemplateVersionResponse
- DescribeRoleAliasResponse
- DescribeScheduledAuditResponse
- DescribeSecurityProfileResponse
- DescribeStreamResponse
- DescribeThingGroupResponse
- DescribeThingRegistrationTaskResponse
- DescribeThingResponse
- description
- name
context_file: json-ld/amazon-iot-device-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-management/refs/heads/main/json-ld/amazon-iot-device-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iot Device Management from Amazon IoT Device Management.
layout: jsonld
name: Amazon Iot Device Management Context
namespaces:
- prefix: amzn
  uri: https://amazonaws.com/schema/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: schema
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: abortConfig
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: actionArn
  type: string
- container: ''
  name: actionId
  type: string
- container: ''
  name: actionIdentifiers
  type: string
- container: ''
  name: actionName
  type: string
- container: ''
  name: actionParams
  type: string
- container: ''
  name: actionType
  type: string
- container: ''
  name: actionsDefinition
  type: string
- container: ''
  name: actionsExecutions
  type: string
- container: ''
  name: activeViolations
  type: string
- container: ''
  name: additionalMetricsToRetain
  type: string
- container: ''
  name: additionalMetricsToRetainV2
  type: string
- container: ''
  name: aggregationField
  type: string
- container: ''
  name: aggregationType
  type: string
- container: ''
  name: alertTargetArn
  type: string
- container: ''
  name: alertTargets
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: attributes
  type: string
- container: ''
  name: auditCheckConfigurations
  type: string
- container: ''
  name: auditCheckToActionsMapping
  type: string
- container: ''
  name: auditDetails
  type: string
- container: ''
  name: auditNotificationTargetConfigurations
  type: string
- container: ''
  name: authorizerArn
  type: string
- container: ''
  name: authorizerConfig
  type: string
- container: ''
  name: authorizerDescription
  type: string
- container: ''
  name: authorizerName
  type: string
- container: ''
  name: authorizers
  type: string
- container: ''
  name: awsIotJobArn
  type: string
- container: ''
  name: awsIotJobId
  type: string
- container: ''
  name: baseRatePerMinute
  type: string
- container: ''
  name: behaviors
  type: string
- container: ''
  name: billingGroupArn
  type: string
- container: ''
  name: billingGroupId
  type: string
- container: ''
  name: billingGroupMetadata
  type: string
- container: ''
  name: billingGroupName
  type: string
- container: ''
  name: billingGroupProperties
  type: string
- container: ''
  name: billingGroups
  type: string
- container: ''
  name: buckets
  type: string
- container: ''
  name: cardinality
  type: string
- container: ''
  name: certificateArn
  type: string
- container: ''
  name: certificateDescription
  type: string
- container: ''
  name: certificateId
  type: string
- container: ''
  name: certificatePem
  type: string
- container: ''
  name: certificates
  type: string
- container: ''
  name: checkName
  type: string
- container: ''
  name: cloudwatchAlarm
  type: string
- container: ''
  name: cloudwatchLogs
  type: string
- container: ''
  name: cloudwatchMetric
  type: string
- container: ''
  name: codeSigning
  type: string
- container: ''
  name: confirmationUrl
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: creationDate
  type: string
- container: ''
  name: criteria
  type: string
- container: ''
  name: dayOfMonth
  type: string
- container: ''
  name: dayOfWeek
  type: string
- container: ''
  name: defaultClientId
  type: string
- container: ''
  name: defaultLogLevel
  type: string
- container: ''
  name: defaultVersionId
  type: string
- container: ''
  name: destinationSummaries
  type: string
- container: ''
  name: dimensionNames
  type: string
- container: ''
  name: disableAllLogs
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: document
  type: string
- container: ''
  name: documentParameters
  type: string
- container: ''
  name: documentSource
  type: string
- container: ''
  name: domainConfigurationArn
  type: string
- container: ''
  name: domainConfigurationName
  type: string
- container: ''
  name: domainConfigurationStatus
  type: string
- container: ''
  name: domainConfigurations
  type: string
- container: ''
  name: domainName
  type: string
- container: ''
  name: domainType
  type: string
- container: ''
  name: durationInMinutes
  type: string
- container: ''
  name: dynamoDB
  type: string
- container: ''
  name: dynamoDBv2
  type: string
- container: ''
  name: effectivePolicies
  type: string
- container: ''
  name: elasticsearch
  type: string
- container: ''
  name: enabled
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: endpointAddress
  type: string
- container: ''
  name: environments
  type: string
- container: ''
  name: eventConfigurations
  type: string
- container: ''
  name: execution
  type: string
- container: ''
  name: executionSummaries
  type: string
- container: ''
  name: expiration
  type: string
- container: ''
  name: expirationDate
  type: string
- container: ''
  name: failureCount
  type: string
- container: ''
  name: fileId
  type: string
- container: ''
  name: fileLocation
  type: string
- container: ''
  name: fileName
  type: string
- container: ''
  name: fileType
  type: string
- container: ''
  name: fileVersion
  type: string
- container: ''
  name: finding
  type: string
- container: ''
  name: findings
  type: string
- container: ''
  name: firehose
  type: string
- container: ''
  name: fleetMetrics
  type: string
- container: ''
  name: frequency
  type: string
- container: ''
  name: generationId
  type: string
- container: ''
  name: http
  type: string
- container: ''
  name: incrementFactor
  type: string
- container: ''
  name: indexName
  type: string
- container: ''
  name: indexNames
  type: string
- container: ''
  name: indexStatus
  type: string
- container: ''
  name: inputFileBucket
  type: string
- container: ''
  name: inputFileKey
  type: string
- container: ''
  name: iotAnalytics
  type: string
- container: ''
  name: iotEvents
  type: string
- container: ''
  name: iotSiteWise
  type: string
- container: ''
  name: isDefaultVersion
  type: string
- container: ''
  name: issuerCertificateSerialNumber
  type: string
- container: ''
  name: issuerCertificateSubject
  type: string
- container: ''
  name: issuerId
  type: string
- container: ''
  name: job
  type: string
- container: ''
  name: jobArn
  type: string
- container: ''
  name: jobExecutionsRetryConfig
  type: string
- container: ''
  name: jobExecutionsRolloutConfig
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: jobTemplateArn
  type: string
- container: ''
  name: jobTemplateId
  type: string
- container: ''
  name: jobTemplates
  type: string
- container: ''
  name: jobs
  type: string
- container: ''
  name: kafka
  type: string
- container: ''
  name: keyPair
  type: string
- container: ''
  name: kinesis
  type: string
- container: ''
  name: lambda
  type: string
- container: ''
  name: lastModifiedDate
  type: string
- container: ''
  name: lastStatusChangeDate
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: logLevel
  type: string
- container: ''
  name: maintenanceWindows
  type: string
- container: ''
  name: managedJobTemplates
  type: string
- container: ''
  name: maxBuckets
  type: string
- container: ''
  name: merge
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: metric
  type: string
- container: ''
  name: metricArn
  type: string
- container: ''
  name: metricDatumList
  type: string
- container: ''
  name: metricDimension
  type: string
- container: ''
  name: metricName
  type: string
- container: ''
  name: metricNames
  type: string
- container: ''
  name: metricType
  type: string
- container: ''
  name: nextMarker
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: openSearch
  type: string
- container: ''
  name: otaUpdateArn
  type: string
- container: ''
  name: otaUpdateId
  type: string
- container: ''
  name: otaUpdateInfo
  type: string
- container: ''
  name: otaUpdateStatus
  type: string
- container: ''
  name: otaUpdates
  type: string
- container: ''
  name: outgoingCertificates
  type: string
- container: ''
  name: overrideDynamicGroups
  type: string
- container: ''
  name: percentageProgress
  type: string
- container: ''
  name: percentiles
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: policies
  type: string
- container: ''
  name: policyArn
  type: string
- container: ''
  name: policyDocument
  type: string
- container: ''
  name: policyName
  type: string
- container: ''
  name: policyVersionId
  type: string
- container: ''
  name: policyVersions
  type: string
- container: ''
  name: preProvisioningHook
  type: string
- container: ''
  name: presignedUrlConfig
  type: string
- container: ''
  name: principals
  type: string
- container: ''
  name: provisioningRoleArn
  type: string
- container: ''
  name: queryString
  type: string
- container: ''
  name: queryVersion
  type: string
- container: ''
  name: rateIncreaseCriteria
  type: string
- container: ''
  name: registrationCode
  type: string
- container: ''
  name: registrationConfig
  type: string
- container: ''
  name: relatedResources
  type: string
- container: ''
  name: reportType
  type: string
- container: ''
  name: republish
  type: string
- container: ''
  name: resourceIdentifier
  type: string
- container: ''
  name: resourceLinks
  type: string
- container: ''
  name: roleAlias
  type: string
- container: ''
  name: roleAliasArn
  type: string
- container: ''
  name: roleAliasDescription
  type: string
- container: ''
  name: roleAliases
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: roleArnForLogging
  type: string
- container: ''
  name: rule
  type: string
- container: ''
  name: ruleArn
  type: string
- container: ''
  name: rules
  type: string
- container: ''
  name: s3
  type: string
- container: ''
  name: s3Location
  type: string
- container: ''
  name: salesforce
  type: string
- container: ''
  name: scheduledAuditArn
  type: string
- container: ''
  name: scheduledAuditName
  type: string
- container: ''
  name: scheduledAudits
  type: string
- container: ''
  name: securityGroups
  type: string
- container: ''
  name: securityProfileArn
  type: string
- container: ''
  name: securityProfileDescription
  type: string
- container: ''
  name: securityProfileIdentifiers
  type: string
- container: ''
  name: securityProfileName
  type: string
- container: ''
  name: securityProfileTargetMappings
  type: string
- container: ''
  name: securityProfileTargets
  type: string
- container: ''
  name: serverCertificates
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: sns
  type: string
- container: ''
  name: sqs
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: statistics
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: stepFunctions
  type: string
- container: ''
  name: streamArn
  type: string
- container: ''
  name: streamId
  type: string
- container: ''
  name: streamInfo
  type: string
- container: ''
  name: streamVersion
  type: string
- container: ''
  name: streams
  type: string
- container: ''
  name: stringValues
  type: string
- container: ''
  name: subnetIds
  type: string
- container: ''
  name: successCount
  type: string
- container: ''
  name: summaries
  type: string
- container: ''
  name: suppressAlerts
  type: string
- container: ''
  name: suppressIndefinitely
  type: string
- container: ''
  name: suppressions
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: targetCheckNames
  type: string
- container: ''
  name: targets
  type: string
- container: ''
  name: taskId
  type: string
- container: ''
  name: taskIds
  type: string
- container: ''
  name: taskStartTime
  type: string
- container: ''
  name: taskStatistics
  type: string
- container: ''
  name: taskStatus
  type: string
- container: ''
  name: taskSummary
  type: string
- container: ''
  name: taskType
  type: string
- container: ''
  name: tasks
  type: string
- container: ''
  name: templateArn
  type: string
- container: ''
  name: templateBody
  type: string
- container: ''
  name: templateName
  type: string
- container: ''
  name: templateVersion
  type: string
- container: ''
  name: templates
  type: string
- container: ''
  name: thingArn
  type: string
- container: ''
  name: thingGroupArn
  type: string
- container: ''
  name: thingGroupId
  type: string
- container: ''
  name: thingGroupIndexingConfiguration
  type: string
- container: ''
  name: thingGroupMetadata
  type: string
- container: ''
  name: thingGroupName
  type: string
- container: ''
  name: thingGroupNames
  type: string
- container: ''
  name: thingGroupProperties
  type: string
- container: ''
  name: thingGroups
  type: string
- container: ''
  name: thingId
  type: string
- container: ''
  name: thingIndexingConfiguration
  type: string
- container: ''
  name: thingName
  type: string
- container: ''
  name: thingTypeArn
  type: string
- container: ''
  name: thingTypeId
  type: string
- container: ''
  name: thingTypeMetadata
  type: string
- container: ''
  name: thingTypeName
  type: string
- container: ''
  name: thingTypeProperties
  type: string
- container: ''
  name: thingTypes
  type: string
- container: ''
  name: things
  type: string
- container: ''
  name: timeoutConfig
  type: string
- container: ''
  name: timestream
  type: string
- container: ''
  name: topicArn
  type: string
- container: ''
  name: topicRuleDestination
  type: string
- container: ''
  name: totalCount
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: versionId
  type: string
- container: ''
  name: versions
  type: string
- container: ''
  name: vpcId
  type: string
property_count: 266
provider_name: Amazon IoT Device Management
provider_slug: amazon-iot-device-management
slug: amazon-iot-device-management-context
source_filename: amazon-iot-device-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": {\n      \"@id\": \"amzn:schema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Action\": \"amzn:Action\",\n    \"AddThingToBillingGroupResponse\": \"amzn:AddThingToBillingGroupResponse\",\n    \"AddThingToThingGroupResponse\": \"amzn:AddThingToThingGroupResponse\",\n    \"AddThingsToThingGroupParams\": \"amzn:AddThingsToThingGroupParams\",\n    \"AlertTarget\": \"amzn:AlertTarget\",\n    \"AssociateTargetsWithJobResponse\": \"amzn:AssociateTargetsWithJobResponse\",\n    \"AttachSecurityProfileResponse\": \"amzn:AttachSecurityProfileResponse\",\n    \"AttachThingPrincipalResponse\": \"amzn:AttachThingPrincipalResponse\",\n    \"AttributePayload\": \"amzn:AttributePayload\",\n    \"Attributes\": \"amzn:Attributes\",\n    \"AwsJobExponentialRolloutRate\": \"amzn:AwsJobExponentialRolloutRate\"\
  ,\n    \"Behavior\": \"amzn:Behavior\",\n    \"CancelAuditMitigationActionsTaskResponse\": \"amzn:CancelAuditMitigationActionsTaskResponse\",\n    \"CancelAuditTaskResponse\": \"amzn:CancelAuditTaskResponse\",\n    \"CancelDetectMitigationActionsTaskResponse\": \"amzn:CancelDetectMitigationActionsTaskResponse\",\n    \"CancelJobResponse\": \"amzn:CancelJobResponse\",\n    \"ClearDefaultAuthorizerResponse\": \"amzn:ClearDefaultAuthorizerResponse\",\n    \"ConfirmTopicRuleDestinationResponse\": \"amzn:ConfirmTopicRuleDestinationResponse\",\n    \"CreateAuditSuppressionResponse\": \"amzn:CreateAuditSuppressionResponse\",\n    \"CreateAuthorizerResponse\": \"amzn:CreateAuthorizerResponse\",\n    \"CreateBillingGroupResponse\": \"amzn:CreateBillingGroupResponse\",\n    \"CreateCertificateFromCsrResponse\": \"amzn:CreateCertificateFromCsrResponse\",\n    \"CreateCustomMetricResponse\": \"amzn:CreateCustomMetricResponse\",\n    \"CreateDimensionResponse\": \"amzn:CreateDimensionResponse\",\n\
  \    \"CreateDomainConfigurationResponse\": \"amzn:CreateDomainConfigurationResponse\",\n    \"CreateDynamicThingGroupResponse\": \"amzn:CreateDynamicThingGroupResponse\",\n    \"CreateFleetMetricResponse\": \"amzn:CreateFleetMetricResponse\",\n    \"CreateJobResponse\": \"amzn:CreateJobResponse\",\n    \"CreateJobTemplateResponse\": \"amzn:CreateJobTemplateResponse\",\n    \"CreateKeysAndCertificateResponse\": \"amzn:CreateKeysAndCertificateResponse\",\n    \"CreateMitigationActionResponse\": \"amzn:CreateMitigationActionResponse\",\n    \"CreateOTAUpdateResponse\": \"amzn:CreateOTAUpdateResponse\",\n    \"CreatePolicyResponse\": \"amzn:CreatePolicyResponse\",\n    \"CreatePolicyVersionResponse\": \"amzn:CreatePolicyVersionResponse\",\n    \"CreateProvisioningClaimResponse\": \"amzn:CreateProvisioningClaimResponse\",\n    \"CreateProvisioningTemplateResponse\": \"amzn:CreateProvisioningTemplateResponse\",\n    \"CreateProvisioningTemplateVersionResponse\": \"amzn:CreateProvisioningTemplateVersionResponse\"\
  ,\n    \"CreateRoleAliasResponse\": \"amzn:CreateRoleAliasResponse\",\n    \"CreateScheduledAuditResponse\": \"amzn:CreateScheduledAuditResponse\",\n    \"CreateSecurityProfileResponse\": \"amzn:CreateSecurityProfileResponse\",\n    \"CreateStreamResponse\": \"amzn:CreateStreamResponse\",\n    \"CreateThingGroupResponse\": \"amzn:CreateThingGroupResponse\",\n    \"CreateThingResponse\": \"amzn:CreateThingResponse\",\n    \"CreateThingTypeResponse\": \"amzn:CreateThingTypeResponse\",\n    \"CreateTopicRuleDestinationResponse\": \"amzn:CreateTopicRuleDestinationResponse\",\n    \"DeleteAccountAuditConfigurationResponse\": \"amzn:DeleteAccountAuditConfigurationResponse\",\n    \"DeleteAuditSuppressionResponse\": \"amzn:DeleteAuditSuppressionResponse\",\n    \"DeleteAuthorizerResponse\": \"amzn:DeleteAuthorizerResponse\",\n    \"DeleteBillingGroupResponse\": \"amzn:DeleteBillingGroupResponse\",\n    \"DeleteCACertificateResponse\": \"amzn:DeleteCACertificateResponse\",\n    \"DeleteCustomMetricResponse\"\
  : \"amzn:DeleteCustomMetricResponse\",\n    \"DeleteDimensionResponse\": \"amzn:DeleteDimensionResponse\",\n    \"DeleteDomainConfigurationResponse\": \"amzn:DeleteDomainConfigurationResponse\",\n    \"DeleteDynamicThingGroupResponse\": \"amzn:DeleteDynamicThingGroupResponse\",\n    \"DeleteMitigationActionResponse\": \"amzn:DeleteMitigationActionResponse\",\n    \"DeleteOTAUpdateResponse\": \"amzn:DeleteOTAUpdateResponse\",\n    \"DeleteProvisioningTemplateResponse\": \"amzn:DeleteProvisioningTemplateResponse\",\n    \"DeleteProvisioningTemplateVersionResponse\": \"amzn:DeleteProvisioningTemplateVersionResponse\",\n    \"DeleteRegistrationCodeResponse\": \"amzn:DeleteRegistrationCodeResponse\",\n    \"DeleteRoleAliasResponse\": \"amzn:DeleteRoleAliasResponse\",\n    \"DeleteScheduledAuditResponse\": \"amzn:DeleteScheduledAuditResponse\",\n    \"DeleteSecurityProfileResponse\": \"amzn:DeleteSecurityProfileResponse\",\n    \"DeleteStreamResponse\": \"amzn:DeleteStreamResponse\",\n    \"\
  DeleteThingGroupResponse\": \"amzn:DeleteThingGroupResponse\",\n    \"DeleteThingResponse\": \"amzn:DeleteThingResponse\",\n    \"DeleteThingTypeResponse\": \"amzn:DeleteThingTypeResponse\",\n    \"DeleteTopicRuleDestinationResponse\": \"amzn:DeleteTopicRuleDestinationResponse\",\n    \"DeprecateThingTypeResponse\": \"amzn:DeprecateThingTypeResponse\",\n    \"DescribeAccountAuditConfigurationResponse\": \"amzn:DescribeAccountAuditConfigurationResponse\",\n    \"DescribeAuditFindingResponse\": \"amzn:DescribeAuditFindingResponse\",\n    \"DescribeAuditMitigationActionsTaskResponse\": \"amzn:DescribeAuditMitigationActionsTaskResponse\",\n    \"DescribeAuditSuppressionResponse\": \"amzn:DescribeAuditSuppressionResponse\",\n    \"DescribeAuditTaskResponse\": \"amzn:DescribeAuditTaskResponse\",\n    \"DescribeAuthorizerResponse\": \"amzn:DescribeAuthorizerResponse\",\n    \"DescribeBillingGroupResponse\": \"amzn:DescribeBillingGroupResponse\",\n    \"DescribeCACertificateResponse\": \"amzn:DescribeCACertificateResponse\"\
  ,\n    \"DescribeCertificateResponse\": \"amzn:DescribeCertificateResponse\",\n    \"DescribeCustomMetricResponse\": \"amzn:DescribeCustomMetricResponse\",\n    \"DescribeDefaultAuthorizerResponse\": \"amzn:DescribeDefaultAuthorizerResponse\",\n    \"DescribeDetectMitigationActionsTaskResponse\": \"amzn:DescribeDetectMitigationActionsTaskResponse\",\n    \"DescribeDimensionResponse\": \"amzn:DescribeDimensionResponse\",\n    \"DescribeDomainConfigurationResponse\": \"amzn:DescribeDomainConfigurationResponse\",\n    \"DescribeEndpointResponse\": \"amzn:DescribeEndpointResponse\",\n    \"DescribeEventConfigurationsResponse\": \"amzn:DescribeEventConfigurationsResponse\",\n    \"DescribeFleetMetricResponse\": \"amzn:DescribeFleetMetricResponse\",\n    \"DescribeIndexResponse\": \"amzn:DescribeIndexResponse\",\n    \"DescribeJobExecutionResponse\": \"amzn:DescribeJobExecutionResponse\",\n    \"DescribeJobResponse\": \"amzn:DescribeJobResponse\",\n    \"DescribeJobTemplateResponse\": \"amzn:DescribeJobTemplateResponse\"\
  ,\n    \"DescribeManagedJobTemplateResponse\": \"amzn:DescribeManagedJobTemplateResponse\",\n    \"DescribeMitigationActionResponse\": \"amzn:DescribeMitigationActionResponse\",\n    \"DescribeProvisioningTemplateResponse\": \"amzn:DescribeProvisioningTemplateResponse\",\n    \"DescribeProvisioningTemplateVersionResponse\": \"amzn:DescribeProvisioningTemplateVersionResponse\",\n    \"DescribeRoleAliasResponse\": \"amzn:DescribeRoleAliasResponse\",\n    \"DescribeScheduledAuditResponse\": \"amzn:DescribeScheduledAuditResponse\",\n    \"DescribeSecurityProfileResponse\": \"amzn:DescribeSecurityProfileResponse\",\n    \"DescribeStreamResponse\": \"amzn:DescribeStreamResponse\",\n    \"DescribeThingGroupResponse\": \"amzn:DescribeThingGroupResponse\",\n    \"DescribeThingRegistrationTaskResponse\": \"amzn:DescribeThingRegistrationTaskResponse\",\n    \"DescribeThingResponse\": \"amzn:DescribeThingResponse\",\n    \"Key\": {\n      \"@id\": \"amzn:Key\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"Value\": {\n      \"@id\": \"amzn:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"abortConfig\": {\n      \"@id\": \"amzn:abortConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"amzn:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionArn\": {\n      \"@id\": \"amzn:actionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionId\": {\n      \"@id\": \"amzn:actionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionIdentifiers\": {\n      \"@id\": \"amzn:actionIdentifiers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionName\": {\n      \"@id\": \"amzn:actionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionParams\": {\n      \"@id\": \"amzn:actionParams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionType\": {\n      \"@id\": \"amzn:actionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionsDefinition\": {\n      \"@id\": \"amzn:actionsDefinition\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"actionsExecutions\": {\n      \"@id\": \"amzn:actionsExecutions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeViolations\": {\n      \"@id\": \"amzn:activeViolations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalMetricsToRetain\": {\n      \"@id\": \"amzn:additionalMetricsToRetain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalMetricsToRetainV2\": {\n      \"@id\": \"amzn:additionalMetricsToRetainV2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregationField\": {\n      \"@id\": \"amzn:aggregationField\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregationType\": {\n      \"@id\": \"amzn:aggregationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertTargetArn\": {\n      \"@id\": \"amzn:alertTargetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertTargets\": {\n      \"@id\": \"amzn:alertTargets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"amzn:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auditCheckConfigurations\": {\n      \"@id\": \"amzn:auditCheckConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auditCheckToActionsMapping\": {\n      \"@id\": \"amzn:auditCheckToActionsMapping\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auditDetails\": {\n      \"@id\": \"amzn:auditDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auditNotificationTargetConfigurations\": {\n      \"@id\": \"amzn:auditNotificationTargetConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizerArn\": {\n      \"@id\": \"amzn:authorizerArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizerConfig\": {\n      \"@id\": \"amzn:authorizerConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizerDescription\": {\n      \"@id\": \"amzn:authorizerDescription\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"authorizerName\": {\n      \"@id\": \"amzn:authorizerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorizers\": {\n      \"@id\": \"amzn:authorizers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsIotJobArn\": {\n      \"@id\": \"amzn:awsIotJobArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsIotJobId\": {\n      \"@id\": \"amzn:awsIotJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseRatePerMinute\": {\n      \"@id\": \"amzn:baseRatePerMinute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"behaviors\": {\n      \"@id\": \"amzn:behaviors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingGroupArn\": {\n      \"@id\": \"amzn:billingGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingGroupId\": {\n      \"@id\": \"amzn:billingGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingGroupMetadata\": {\n      \"@id\": \"amzn:billingGroupMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingGroupName\"\
  : {\n      \"@id\": \"amzn:billingGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingGroupProperties\": {\n      \"@id\": \"amzn:billingGroupProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingGroups\": {\n      \"@id\": \"amzn:billingGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buckets\": {\n      \"@id\": \"amzn:buckets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardinality\": {\n      \"@id\": \"amzn:cardinality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateArn\": {\n      \"@id\": \"amzn:certificateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateDescription\": {\n      \"@id\": \"amzn:certificateDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateId\": {\n      \"@id\": \"amzn:certificateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificatePem\": {\n      \"@id\": \"amzn:certificatePem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificates\": {\n     \
  \ \"@id\": \"amzn:certificates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkName\": {\n      \"@id\": \"amzn:checkName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudwatchAlarm\": {\n      \"@id\": \"amzn:cloudwatchAlarm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudwatchLogs\": {\n      \"@id\": \"amzn:cloudwatchLogs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudwatchMetric\": {\n      \"@id\": \"amzn:cloudwatchMetric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeSigning\": {\n      \"@id\": \"amzn:codeSigning\",\n      \"@type\": \"xsd:string\"\n    },\n    \"confirmationUrl\": {\n      \"@id\": \"amzn:confirmationUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"amzn:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"amzn:creationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"criteria\": {\n      \"@id\": \"amzn:criteria\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"dayOfMonth\": {\n      \"@id\": \"amzn:dayOfMonth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dayOfWeek\": {\n      \"@id\": \"amzn:dayOfWeek\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultClientId\": {\n      \"@id\": \"amzn:defaultClientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultLogLevel\": {\n      \"@id\": \"amzn:defaultLogLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultVersionId\": {\n      \"@id\": \"amzn:defaultVersionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"destinationSummaries\": {\n      \"@id\": \"amzn:destinationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensionNames\": {\n      \"@id\": \"amzn:dimensionNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disableAllLogs\": {\n      \"@id\": \"amzn:disableAllLogs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"amzn:displayName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"document\": {\n      \"@id\": \"amzn:document\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentParameters\": {\n      \"@id\": \"amzn:documentParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentSource\": {\n      \"@id\": \"amzn:documentSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainConfigurationArn\": {\n      \"@id\": \"amzn:domainConfigurationArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainConfigurationName\": {\n      \"@id\": \"amzn:domainConfigurationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainConfigurationStatus\": {\n      \"@id\": \"amzn:domainConfigurationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainConfigurations\": {\n      \"@id\": \"amzn:domainConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainName\": {\n      \"@id\": \"amzn:domainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainType\": {\n    \
  \  \"@id\": \"amzn:domainType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"durationInMinutes\": {\n      \"@id\": \"amzn:durationInMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamoDB\": {\n      \"@id\": \"amzn:dynamoDB\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamoDBv2\": {\n      \"@id\": \"amzn:dynamoDBv2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectivePolicies\": {\n      \"@id\": \"amzn:effectivePolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elasticsearch\": {\n      \"@id\": \"amzn:elasticsearch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"amzn:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"amzn:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointAddress\": {\n      \"@id\": \"amzn:endpointAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environments\": {\n      \"@id\": \"amzn:environments\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"eventConfigurations\": {\n      \"@id\": \"amzn:eventConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"execution\": {\n      \"@id\": \"amzn:execution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionSummaries\": {\n      \"@id\": \"amzn:executionSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiration\": {\n      \"@id\": \"amzn:expiration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"amzn:expirationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureCount\": {\n      \"@id\": \"amzn:failureCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileId\": {\n      \"@id\": \"amzn:fileId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileLocation\": {\n      \"@id\": \"amzn:fileLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileName\": {\n      \"@id\": \"amzn:fileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileType\": {\n      \"@id\": \"amzn:fileType\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"fileVersion\": {\n      \"@id\": \"amzn:fileVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"finding\": {\n      \"@id\": \"amzn:finding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findings\": {\n      \"@id\": \"amzn:findings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firehose\": {\n      \"@id\": \"amzn:firehose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleetMetrics\": {\n      \"@id\": \"amzn:fleetMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frequency\": {\n      \"@id\": \"amzn:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generationId\": {\n      \"@id\": \"amzn:generationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http\": {\n      \"@id\": \"amzn:http\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incrementFactor\": {\n      \"@id\": \"amzn:incrementFactor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"indexName\": {\n      \"@id\": \"amzn:indexName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"indexNames\": {\n      \"@id\": \"amzn:indexNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"indexStatus\": {\n      \"@id\": \"amzn:indexStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputFileBucket\": {\n      \"@id\": \"amzn:inputFileBucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputFileKey\": {\n      \"@id\": \"amzn:inputFileKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotAnalytics\": {\n      \"@id\": \"amzn:iotAnalytics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotEvents\": {\n      \"@id\": \"amzn:iotEvents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotSiteWise\": {\n      \"@id\": \"amzn:iotSiteWise\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isDefaultVersion\": {\n      \"@id\": \"amzn:isDefaultVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerCertificateSerialNumber\": {\n      \"@id\": \"amzn:issuerCertificateSerialNumber\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"issuerCertificateSubject\": {\n      \"@id\": \"amzn:issuerCertificateSubject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuerId\": {\n      \"@id\": \"amzn:issuerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"job\": {\n      \"@id\": \"amzn:job\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobArn\": {\n      \"@id\": \"amzn:jobArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobExecutionsRetryConfig\": {\n      \"@id\": \"amzn:jobExecutionsRetryConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobExecutionsRolloutConfig\": {\n      \"@id\": \"amzn:jobExecutionsRolloutConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"amzn:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobTemplateArn\": {\n      \"@id\": \"amzn:jobTemplateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobTemplateId\": {\n      \"@id\": \"amzn:jobTemplateId\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"jobTemplates\": {\n      \"@id\": \"amzn:jobTemplates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobs\": {\n      \"@id\": \"amzn:jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kafka\": {\n      \"@id\": \"amzn:kafka\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyPair\": {\n      \"@id\": \"amzn:keyPair\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kinesis\": {\n      \"@id\": \"amzn:kinesis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambda\": {\n      \"@id\": \"amzn:lambda\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedDate\": {\n      \"@id\": \"amzn:lastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastStatusChangeDate\": {\n      \"@id\": \"amzn:lastStatusChangeDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"amzn:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logLevel\": {\n      \"@id\": \"amzn:logLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  maintenanceWindows\": {\n      \"@id\": \"amzn:maintenanceWindows\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managedJobTemplates\": {\n      \"@id\": \"amzn:managedJobTemplates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxBuckets\": {\n      \"@id\": \"amzn:maxBuckets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merge\": {\n      \"@id\": \"amzn:merge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amzn:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metric\": {\n      \"@id\": \"amzn:metric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricArn\": {\n      \"@id\": \"amzn:metricArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricDatumList\": {\n      \"@id\": \"amzn:metricDatumList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricDimension\": {\n      \"@id\": \"amzn:metricDimension\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricName\": {\n      \"@id\": \"amzn:metricName\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"metricNames\": {\n      \"@id\": \"amzn:metricNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricType\": {\n      \"@id\": \"amzn:metricType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nextMarker\": {\n      \"@id\": \"amzn:nextMarker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openSearch\": {\n      \"@id\": \"amzn:openSearch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"otaUpdateArn\": {\n      \"@id\": \"amzn:otaUpdateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"otaUpdateId\": {\n      \"@id\": \"amzn:otaUpdateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"otaUpdateInfo\": {\n      \"@id\": \"amzn:otaUpdateInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"otaUpdateStatus\": {\n      \"@id\": \"amzn:otaUpdateStatus\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"otaUpdates\": {\n      \"@id\": \"amzn:otaUpdates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outgoingCertificates\": {\n      \"@id\": \"amzn:outgoingCertificates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overrideDynamicGroups\": {\n      \"@id\": \"amzn:overrideDynamicGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentageProgress\": {\n      \"@id\": \"amzn:percentageProgress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentiles\": {\n      \"@id\": \"amzn:percentiles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"amzn:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policies\": {\n      \"@id\": \"amzn:policies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyArn\": {\n      \"@id\": \"amzn:policyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyDocument\": {\n      \"@id\": \"amzn:policyDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyName\": {\n      \"@id\": \"\
  amzn:policyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyVersionId\": {\n      \"@id\": \"amzn:policyVersionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyVersions\": {\n      \"@id\": \"amzn:policyVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preProvisioningHook\": {\n      \"@id\": \"amzn:preProvisioningHook\",\n      \"@type\": \"xsd:string\"\n    },\n    \"presignedUrlConfig\": {\n      \"@id\": \"amzn:presignedUrlConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principals\": {\n      \"@id\": \"amzn:principals\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioningRoleArn\": {\n      \"@id\": \"amzn:provisioningRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryString\": {\n      \"@id\": \"amzn:queryString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queryVersion\": {\n      \"@id\": \"amzn:queryVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rateIncreaseCriteria\": {\n      \"@id\": \"amzn:rateIncreaseCriteria\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationCode\": {\n      \"@id\": \"amzn:registrationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationConfig\": {\n      \"@id\": \"amzn:registrationConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedResources\": {\n      \"@id\": \"amzn:relatedResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportType\": {\n      \"@id\": \"amzn:reportType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"republish\": {\n      \"@id\": \"amzn:republish\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceIdentifier\": {\n      \"@id\": \"amzn:resourceIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceLinks\": {\n      \"@id\": \"amzn:resourceLinks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleAlias\": {\n      \"@id\": \"amzn:roleAlias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleAliasArn\": {\n      \"@id\": \"amzn:roleAliasArn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"roleAliasDescription\": {\n      \"@id\": \"amzn:roleAliasDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleAliases\": {\n      \"@id\": \"amzn:roleAliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"amzn:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArnForLogging\": {\n      \"@id\": \"amzn:roleArnForLogging\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rule\": {\n      \"@id\": \"amzn:rule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleArn\": {\n      \"@id\": \"amzn:ruleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"amzn:rules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3\": {\n      \"@id\": \"amzn:s3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Location\": {\n      \"@id\": \"amzn:s3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salesforce\": {\n      \"@id\": \"amzn:salesforce\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"scheduledAuditArn\": {\n      \"@id\": \"amzn:scheduledAuditArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledAuditName\": {\n      \"@id\": \"amzn:scheduledAuditName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledAudits\": {\n      \"@id\": \"amzn:scheduledAudits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroups\": {\n      \"@id\": \"amzn:securityGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityProfileArn\": {\n      \"@id\": \"amzn:securityProfileArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityProfileDescription\": {\n      \"@id\": \"amzn:securityProfileDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityProfileIdentifiers\": {\n      \"@id\": \"amzn:securityProfileIdentifiers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityProfileName\": {\n      \"@id\": \"amzn:securityProfileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityProfileTargetMappings\"\
  : {\n      \"@id\": \"amzn:securityProfileTargetMappings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityProfileTargets\": {\n      \"@id\": \"amzn:securityProfileTargets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serverCertificates\": {\n      \"@id\": \"amzn:serverCertificates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceType\": {\n      \"@id\": \"amzn:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sns\": {\n      \"@id\": \"amzn:sns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sqs\": {\n      \"@id\": \"amzn:sqs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amzn:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statistics\": {\n      \"@id\": \"amzn:statistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepFunctions\": {\n      \"@id\": \"amzn:stepFunctions\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"streamArn\": {\n      \"@id\": \"amzn:streamArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamId\": {\n      \"@id\": \"amzn:streamId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamInfo\": {\n      \"@id\": \"amzn:streamInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamVersion\": {\n      \"@id\": \"amzn:streamVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streams\": {\n      \"@id\": \"amzn:streams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stringValues\": {\n      \"@id\": \"amzn:stringValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"amzn:subnetIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"successCount\": {\n      \"@id\": \"amzn:successCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summaries\": {\n      \"@id\": \"amzn:summaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suppressAlerts\": {\n      \"@id\": \"amzn:suppressAlerts\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"suppressIndefinitely\": {\n      \"@id\": \"amzn:suppressIndefinitely\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suppressions\": {\n      \"@id\": \"amzn:suppressions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target\": {\n      \"@id\": \"amzn:target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetCheckNames\": {\n      \"@id\": \"amzn:targetCheckNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targets\": {\n      \"@id\": \"amzn:targets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"amzn:taskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskIds\": {\n      \"@id\": \"amzn:taskIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskStartTime\": {\n      \"@id\": \"amzn:taskStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskStatistics\": {\n      \"@id\": \"amzn:taskStatistics\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"taskStatus\": {\n      \"@id\": \"amzn:taskStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskSummary\": {\n      \"@id\": \"amzn:taskSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskType\": {\n      \"@id\": \"amzn:taskType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tasks\": {\n      \"@id\": \"amzn:tasks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateArn\": {\n      \"@id\": \"amzn:templateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateBody\": {\n      \"@id\": \"amzn:templateBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateName\": {\n      \"@id\": \"amzn:templateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateVersion\": {\n      \"@id\": \"amzn:templateVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templates\": {\n      \"@id\": \"amzn:templates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingArn\": {\n      \"@id\": \"amzn:thingArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"thingGroupArn\": {\n      \"@id\": \"amzn:thingGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingGroupId\": {\n      \"@id\": \"amzn:thingGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingGroupIndexingConfiguration\": {\n      \"@id\": \"amzn:thingGroupIndexingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingGroupMetadata\": {\n      \"@id\": \"amzn:thingGroupMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingGroupName\": {\n      \"@id\": \"amzn:thingGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingGroupNames\": {\n      \"@id\": \"amzn:thingGroupNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingGroupProperties\": {\n      \"@id\": \"amzn:thingGroupProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingGroups\": {\n      \"@id\": \"amzn:thingGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingId\": {\n      \"@id\": \"amzn:thingId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"thingIndexingConfiguration\": {\n      \"@id\": \"amzn:thingIndexingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingName\": {\n      \"@id\": \"amzn:thingName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingTypeArn\": {\n      \"@id\": \"amzn:thingTypeArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingTypeId\": {\n      \"@id\": \"amzn:thingTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingTypeMetadata\": {\n      \"@id\": \"amzn:thingTypeMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingTypeName\": {\n      \"@id\": \"amzn:thingTypeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingTypeProperties\": {\n      \"@id\": \"amzn:thingTypeProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingTypes\": {\n      \"@id\": \"amzn:thingTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"things\": {\n      \"@id\": \"amzn:things\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"timeoutConfig\": {\n      \"@id\": \"amzn:timeoutConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestream\": {\n      \"@id\": \"amzn:timestream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topicArn\": {\n      \"@id\": \"amzn:topicArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topicRuleDestination\": {\n      \"@id\": \"amzn:topicRuleDestination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"amzn:totalCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"amzn:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"amzn:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionId\": {\n      \"@id\": \"amzn:versionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versions\": {\n      \"@id\": \"amzn:versions\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"vpcId\": {\n      \"@id\": \"amzn:vpcId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-device-management/refs/heads/main/json-ld/amazon-iot-device-management-context.jsonld
tags:
- AWS
- Device Management
- Fleet Management
- IoT
- OTA Updates
- JSON-LD
- Linked Data
- Semantic Web
---

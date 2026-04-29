---
api_specs:
- filename: amazon-compute-optimizer-openapi.yml
  format: yaml
  label: Amazon Compute Optimizer API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-compute-optimizer/refs/heads/main/openapi/amazon-compute-optimizer-openapi.yml
class_count: 95
classes:
- InstanceRecommendation
- ECSServiceProjectedUtilizationMetric
- InferredWorkloadSaving
- GetEBSVolumeRecommendationsRequest
- JobFilter
- S3Destination
- LambdaFunctionMemoryRecommendationOption
- RecommendationSource
- ExportEC2InstanceRecommendationsResponse
- RecommendationSummary
- GetLambdaFunctionRecommendationsResponse
- AutoScalingGroupRecommendationOption
- EnrollmentFilter
- EBSFilter
- RecommendedOptionProjectedMetric
- ExportLambdaFunctionRecommendationsRequest
- GetECSServiceRecommendationProjectedMetricsResponse
- PutRecommendationPreferencesResponse
- AccountEnrollmentStatus
- VolumeRecommendationOption
- GetEnrollmentStatusesForOrganizationRequest
- ExportECSServiceRecommendationsRequest
- ContainerRecommendation
- GetEBSVolumeRecommendationsResponse
- SavingsOpportunity
- DescribeRecommendationExportJobsRequest
- UpdateEnrollmentStatusRequest
- ContainerConfiguration
- GetEnrollmentStatusRequest
- DescribeRecommendationExportJobsResponse
- ExportEBSVolumeRecommendationsRequest
- DeleteRecommendationPreferencesResponse
- LambdaFunctionUtilizationMetric
- GetAutoScalingGroupRecommendationsResponse
- ExportLambdaFunctionRecommendationsResponse
- MemorySizeConfiguration
- ExportAutoScalingGroupRecommendationsRequest
- GetEnrollmentStatusResponse
- Scope
- GetRecommendationSummariesRequest
- InstanceRecommendationOption
- AutoScalingGroupConfiguration
- ProjectedMetric
- GetRecommendationPreferencesRequest
- ECSServiceRecommendationFilter
- ECSServiceRecommendation
- GetEffectiveRecommendationPreferencesRequest
- ExportEC2InstanceRecommendationsRequest
- ExportDestination
- EstimatedMonthlySavings
- GetEC2InstanceRecommendationsResponse
- GetLambdaFunctionRecommendationsRequest
- RecommendationPreferencesDetail
- ECSServiceUtilizationMetric
- S3DestinationConfig
- GetEffectiveRecommendationPreferencesResponse
- AutoScalingGroupRecommendation
- EffectiveRecommendationPreferences
- RecommendationExportJob
- GetECSServiceRecommendationProjectedMetricsRequest
- GetAutoScalingGroupRecommendationsRequest
- ECSServiceRecommendationOption
- ReasonCodeSummary
- ServiceConfiguration
- UtilizationMetric
- RecommendationPreferences
- CurrentPerformanceRiskRatings
- VolumeRecommendation
- GetRecommendationSummariesResponse
- ExternalMetricStatus
- GetEC2InstanceRecommendationsRequest
- DeleteRecommendationPreferencesRequest
- LambdaFunctionRecommendation
- GetRecommendationPreferencesResponse
- GetECSServiceRecommendationsRequest
- Tag
- Filter
- GetECSServiceRecommendationsResponse
- ECSServiceRecommendedOptionProjectedMetric
- LambdaFunctionMemoryProjectedMetric
- EBSUtilizationMetric
- ExportEBSVolumeRecommendationsResponse
- ExternalMetricsPreference
- ECSServiceProjectedMetric
- LambdaFunctionRecommendationFilter
- PutRecommendationPreferencesRequest
- GetEC2RecommendationProjectedMetricsRequest
- GetEnrollmentStatusesForOrganizationResponse
- Summary
- UpdateEnrollmentStatusResponse
- GetEC2RecommendationProjectedMetricsResponse
- ExportAutoScalingGroupRecommendationsResponse
- VolumeConfiguration
- ExportECSServiceRecommendationsResponse
- name
context_file: json-ld/amazon-compute-optimizer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-compute-optimizer/refs/heads/main/json-ld/amazon-compute-optimizer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Compute Optimizer from Amazon Compute Optimizer.
layout: jsonld
name: Amazon Compute Optimizer Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: instanceArn
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: instanceName
  type: string
- container: ''
  name: currentInstanceType
  type: string
- container: ''
  name: finding
  type: string
- container: ''
  name: findingReasonCodes
  type: string
- container: ''
  name: utilizationMetrics
  type: string
- container: ''
  name: lookBackPeriodInDays
  type: string
- container: ''
  name: recommendationOptions
  type: string
- container: ''
  name: recommendationSources
  type: string
- container: ''
  name: lastRefreshTimestamp
  type: string
- container: ''
  name: currentPerformanceRisk
  type: string
- container: ''
  name: effectiveRecommendationPreferences
  type: string
- container: ''
  name: inferredWorkloadTypes
  type: string
- container: ''
  name: instanceState
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: externalMetricStatus
  type: string
- container: ''
  name: statistic
  type: string
- container: ''
  name: lowerBoundValue
  type: string
- container: ''
  name: upperBoundValue
  type: string
- container: ''
  name: estimatedMonthlySavings
  type: string
- container: ''
  name: volumeArns
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: accountIds
  type: string
- container: ''
  name: values
  type: string
- container: ''
  name: bucket
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: metadataKey
  type: string
- container: ''
  name: rank
  type: string
- container: ''
  name: memorySize
  type: string
- container: ''
  name: projectedUtilizationMetrics
  type: string
- container: ''
  name: savingsOpportunity
  type: string
- container: ''
  name: recommendationSourceArn
  type: string
- container: ''
  name: recommendationSourceType
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: s3Destination
  type: string
- container: ''
  name: summaries
  type: string
- container: ''
  name: recommendationResourceType
  type: string
- container: ''
  name: currentPerformanceRiskRatings
  type: string
- container: ''
  name: inferredWorkloadSavings
  type: string
- container: ''
  name: lambdaFunctionRecommendations
  type: string
- container: ''
  name: configuration
  type: string
- container: ''
  name: performanceRisk
  type: string
- container: ''
  name: migrationEffort
  type: string
- container: ''
  name: recommendedInstanceType
  type: string
- container: ''
  name: projectedMetrics
  type: string
- container: ''
  name: fieldsToExport
  type: string
- container: ''
  name: s3DestinationConfig
  type: string
- container: ''
  name: fileFormat
  type: string
- container: ''
  name: includeMemberAccounts
  type: string
- container: ''
  name: recommendedOptionProjectedMetrics
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: string
- container: ''
  name: lastUpdatedTimestamp
  type: string
- container: ''
  name: containerName
  type: string
- container: ''
  name: memorySizeConfiguration
  type: string
- container: ''
  name: cpu
  type: string
- container: ''
  name: volumeRecommendations
  type: string
- container: ''
  name: errors
  type: string
- container: ''
  name: savingsOpportunityPercentage
  type: string
- container: ''
  name: jobIds
  type: string
- container: ''
  name: recommendationExportJobs
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: autoScalingGroupRecommendations
  type: string
- container: ''
  name: memory
  type: string
- container: ''
  name: memoryReservation
  type: string
- container: ''
  name: recommendationPreferences
  type: string
- container: ''
  name: memberAccountsEnrolled
  type: string
- container: ''
  name: numberOfMemberAccountsOptedIn
  type: string
- container: ''
  name: instanceType
  type: string
- container: ''
  name: platformDifferences
  type: string
- container: ''
  name: desiredCapacity
  type: string
- container: ''
  name: minSize
  type: string
- container: ''
  name: maxSize
  type: string
- container: ''
  name: timestamps
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: serviceArn
  type: string
- container: ''
  name: currentServiceConfiguration
  type: string
- container: ''
  name: lookbackPeriodInDays
  type: string
- container: ''
  name: launchType
  type: string
- container: ''
  name: serviceRecommendationOptions
  type: string
- container: ''
  name: resourceArn
  type: string
- container: ''
  name: s3
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: instanceRecommendations
  type: string
- container: ''
  name: functionArns
  type: string
- container: ''
  name: enhancedInfrastructureMetrics
  type: string
- container: ''
  name: externalMetricsPreference
  type: string
- container: ''
  name: keyPrefix
  type: string
- container: ''
  name: autoScalingGroupArn
  type: string
- container: ''
  name: autoScalingGroupName
  type: string
- container: ''
  name: currentConfiguration
  type: string
- container: ''
  name: cpuVendorArchitectures
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: creationTimestamp
  type: string
- container: ''
  name: failureReason
  type: string
- container: ''
  name: stat
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: autoScalingGroupArns
  type: string
- container: ''
  name: containerRecommendations
  type: string
- container: ''
  name: containerConfigurations
  type: string
- container: ''
  name: autoScalingConfiguration
  type: string
- container: ''
  name: taskDefinitionArn
  type: string
- container: ''
  name: high
  type: string
- container: ''
  name: medium
  type: string
- container: ''
  name: low
  type: string
- container: ''
  name: veryLow
  type: string
- container: ''
  name: volumeArn
  type: string
- container: ''
  name: volumeRecommendationOptions
  type: string
- container: ''
  name: recommendationSummaries
  type: string
- container: ''
  name: statusCode
  type: string
- container: ''
  name: instanceArns
  type: string
- container: ''
  name: recommendationPreferenceNames
  type: string
- container: ''
  name: functionArn
  type: string
- container: ''
  name: functionVersion
  type: string
- container: ''
  name: currentMemorySize
  type: string
- container: ''
  name: numberOfInvocations
  type: string
- container: ''
  name: memorySizeRecommendationOptions
  type: string
- container: ''
  name: recommendationPreferencesDetails
  type: string
- container: ''
  name: serviceArns
  type: string
- container: ''
  name: ecsServiceRecommendations
  type: string
- container: ''
  name: recommendedCpuUnits
  type: string
- container: ''
  name: recommendedMemorySize
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: upperBoundValues
  type: string
- container: ''
  name: lowerBoundValues
  type: string
- container: ''
  name: accountEnrollmentStatuses
  type: string
- container: ''
  name: reasonCodeSummaries
  type: string
- container: ''
  name: volumeType
  type: string
- container: ''
  name: volumeSize
  type: string
- container: ''
  name: volumeBaselineIOPS
  type: string
- container: ''
  name: volumeBurstIOPS
  type: string
- container: ''
  name: volumeBaselineThroughput
  type: string
- container: ''
  name: volumeBurstThroughput
  type: string
- container: ''
  name: rootVolume
  type: string
property_count: 140
provider_name: Amazon Compute Optimizer
provider_slug: amazon-compute-optimizer
slug: amazon-compute-optimizer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InstanceRecommendation\": \"aws:InstanceRecommendation\",\n    \"ECSServiceProjectedUtilizationMetric\": \"aws:ECSServiceProjectedUtilizationMetric\",\n    \"InferredWorkloadSaving\": \"aws:InferredWorkloadSaving\",\n    \"GetEBSVolumeRecommendationsRequest\": \"aws:GetEBSVolumeRecommendationsRequest\",\n    \"JobFilter\": \"aws:JobFilter\",\n    \"S3Destination\": \"aws:S3Destination\",\n    \"LambdaFunctionMemoryRecommendationOption\": \"aws:LambdaFunctionMemoryRecommendationOption\",\n    \"RecommendationSource\": \"aws:RecommendationSource\",\n    \"ExportEC2InstanceRecommendationsResponse\": \"aws:ExportEC2InstanceRecommendationsResponse\",\n    \"RecommendationSummary\": \"aws:RecommendationSummary\",\n    \"GetLambdaFunctionRecommendationsResponse\"\
  : \"aws:GetLambdaFunctionRecommendationsResponse\",\n    \"AutoScalingGroupRecommendationOption\": \"aws:AutoScalingGroupRecommendationOption\",\n    \"EnrollmentFilter\": \"aws:EnrollmentFilter\",\n    \"EBSFilter\": \"aws:EBSFilter\",\n    \"RecommendedOptionProjectedMetric\": \"aws:RecommendedOptionProjectedMetric\",\n    \"ExportLambdaFunctionRecommendationsRequest\": \"aws:ExportLambdaFunctionRecommendationsRequest\",\n    \"GetECSServiceRecommendationProjectedMetricsResponse\": \"aws:GetECSServiceRecommendationProjectedMetricsResponse\",\n    \"PutRecommendationPreferencesResponse\": \"aws:PutRecommendationPreferencesResponse\",\n    \"AccountEnrollmentStatus\": \"aws:AccountEnrollmentStatus\",\n    \"VolumeRecommendationOption\": \"aws:VolumeRecommendationOption\",\n    \"GetEnrollmentStatusesForOrganizationRequest\": \"aws:GetEnrollmentStatusesForOrganizationRequest\",\n    \"ExportECSServiceRecommendationsRequest\": \"aws:ExportECSServiceRecommendationsRequest\",\n    \"ContainerRecommendation\"\
  : \"aws:ContainerRecommendation\",\n    \"GetEBSVolumeRecommendationsResponse\": \"aws:GetEBSVolumeRecommendationsResponse\",\n    \"SavingsOpportunity\": \"aws:SavingsOpportunity\",\n    \"DescribeRecommendationExportJobsRequest\": \"aws:DescribeRecommendationExportJobsRequest\",\n    \"UpdateEnrollmentStatusRequest\": \"aws:UpdateEnrollmentStatusRequest\",\n    \"ContainerConfiguration\": \"aws:ContainerConfiguration\",\n    \"GetEnrollmentStatusRequest\": \"aws:GetEnrollmentStatusRequest\",\n    \"DescribeRecommendationExportJobsResponse\": \"aws:DescribeRecommendationExportJobsResponse\",\n    \"ExportEBSVolumeRecommendationsRequest\": \"aws:ExportEBSVolumeRecommendationsRequest\",\n    \"DeleteRecommendationPreferencesResponse\": \"aws:DeleteRecommendationPreferencesResponse\",\n    \"LambdaFunctionUtilizationMetric\": \"aws:LambdaFunctionUtilizationMetric\",\n    \"GetAutoScalingGroupRecommendationsResponse\": \"aws:GetAutoScalingGroupRecommendationsResponse\",\n    \"ExportLambdaFunctionRecommendationsResponse\"\
  : \"aws:ExportLambdaFunctionRecommendationsResponse\",\n    \"MemorySizeConfiguration\": \"aws:MemorySizeConfiguration\",\n    \"ExportAutoScalingGroupRecommendationsRequest\": \"aws:ExportAutoScalingGroupRecommendationsRequest\",\n    \"GetEnrollmentStatusResponse\": \"aws:GetEnrollmentStatusResponse\",\n    \"Scope\": \"aws:Scope\",\n    \"GetRecommendationSummariesRequest\": \"aws:GetRecommendationSummariesRequest\",\n    \"InstanceRecommendationOption\": \"aws:InstanceRecommendationOption\",\n    \"AutoScalingGroupConfiguration\": \"aws:AutoScalingGroupConfiguration\",\n    \"ProjectedMetric\": \"aws:ProjectedMetric\",\n    \"GetRecommendationPreferencesRequest\": \"aws:GetRecommendationPreferencesRequest\",\n    \"ECSServiceRecommendationFilter\": \"aws:ECSServiceRecommendationFilter\",\n    \"ECSServiceRecommendation\": \"aws:ECSServiceRecommendation\",\n    \"GetEffectiveRecommendationPreferencesRequest\": \"aws:GetEffectiveRecommendationPreferencesRequest\",\n    \"ExportEC2InstanceRecommendationsRequest\"\
  : \"aws:ExportEC2InstanceRecommendationsRequest\",\n    \"ExportDestination\": \"aws:ExportDestination\",\n    \"EstimatedMonthlySavings\": \"aws:EstimatedMonthlySavings\",\n    \"GetEC2InstanceRecommendationsResponse\": \"aws:GetEC2InstanceRecommendationsResponse\",\n    \"GetLambdaFunctionRecommendationsRequest\": \"aws:GetLambdaFunctionRecommendationsRequest\",\n    \"RecommendationPreferencesDetail\": \"aws:RecommendationPreferencesDetail\",\n    \"ECSServiceUtilizationMetric\": \"aws:ECSServiceUtilizationMetric\",\n    \"S3DestinationConfig\": \"aws:S3DestinationConfig\",\n    \"GetEffectiveRecommendationPreferencesResponse\": \"aws:GetEffectiveRecommendationPreferencesResponse\",\n    \"AutoScalingGroupRecommendation\": \"aws:AutoScalingGroupRecommendation\",\n    \"EffectiveRecommendationPreferences\": \"aws:EffectiveRecommendationPreferences\",\n    \"RecommendationExportJob\": \"aws:RecommendationExportJob\",\n    \"GetECSServiceRecommendationProjectedMetricsRequest\": \"aws:GetECSServiceRecommendationProjectedMetricsRequest\"\
  ,\n    \"GetAutoScalingGroupRecommendationsRequest\": \"aws:GetAutoScalingGroupRecommendationsRequest\",\n    \"ECSServiceRecommendationOption\": \"aws:ECSServiceRecommendationOption\",\n    \"ReasonCodeSummary\": \"aws:ReasonCodeSummary\",\n    \"ServiceConfiguration\": \"aws:ServiceConfiguration\",\n    \"UtilizationMetric\": \"aws:UtilizationMetric\",\n    \"RecommendationPreferences\": \"aws:RecommendationPreferences\",\n    \"CurrentPerformanceRiskRatings\": \"aws:CurrentPerformanceRiskRatings\",\n    \"VolumeRecommendation\": \"aws:VolumeRecommendation\",\n    \"GetRecommendationSummariesResponse\": \"aws:GetRecommendationSummariesResponse\",\n    \"ExternalMetricStatus\": \"aws:ExternalMetricStatus\",\n    \"GetEC2InstanceRecommendationsRequest\": \"aws:GetEC2InstanceRecommendationsRequest\",\n    \"DeleteRecommendationPreferencesRequest\": \"aws:DeleteRecommendationPreferencesRequest\",\n    \"LambdaFunctionRecommendation\": \"aws:LambdaFunctionRecommendation\",\n    \"GetRecommendationPreferencesResponse\"\
  : \"aws:GetRecommendationPreferencesResponse\",\n    \"GetECSServiceRecommendationsRequest\": \"aws:GetECSServiceRecommendationsRequest\",\n    \"Tag\": \"aws:Tag\",\n    \"Filter\": \"aws:Filter\",\n    \"GetECSServiceRecommendationsResponse\": \"aws:GetECSServiceRecommendationsResponse\",\n    \"ECSServiceRecommendedOptionProjectedMetric\": \"aws:ECSServiceRecommendedOptionProjectedMetric\",\n    \"LambdaFunctionMemoryProjectedMetric\": \"aws:LambdaFunctionMemoryProjectedMetric\",\n    \"EBSUtilizationMetric\": \"aws:EBSUtilizationMetric\",\n    \"ExportEBSVolumeRecommendationsResponse\": \"aws:ExportEBSVolumeRecommendationsResponse\",\n    \"ExternalMetricsPreference\": \"aws:ExternalMetricsPreference\",\n    \"ECSServiceProjectedMetric\": \"aws:ECSServiceProjectedMetric\",\n    \"LambdaFunctionRecommendationFilter\": \"aws:LambdaFunctionRecommendationFilter\",\n    \"PutRecommendationPreferencesRequest\": \"aws:PutRecommendationPreferencesRequest\",\n    \"GetEC2RecommendationProjectedMetricsRequest\"\
  : \"aws:GetEC2RecommendationProjectedMetricsRequest\",\n    \"GetEnrollmentStatusesForOrganizationResponse\": \"aws:GetEnrollmentStatusesForOrganizationResponse\",\n    \"Summary\": \"aws:Summary\",\n    \"UpdateEnrollmentStatusResponse\": \"aws:UpdateEnrollmentStatusResponse\",\n    \"GetEC2RecommendationProjectedMetricsResponse\": \"aws:GetEC2RecommendationProjectedMetricsResponse\",\n    \"ExportAutoScalingGroupRecommendationsResponse\": \"aws:ExportAutoScalingGroupRecommendationsResponse\",\n    \"VolumeConfiguration\": \"aws:VolumeConfiguration\",\n    \"ExportECSServiceRecommendationsResponse\": \"aws:ExportECSServiceRecommendationsResponse\",\n    \"instanceArn\": {\n      \"@id\": \"aws:instanceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"aws:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceName\": {\n      \"@id\": \"aws:instanceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentInstanceType\": {\n    \
  \  \"@id\": \"aws:currentInstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"finding\": {\n      \"@id\": \"aws:finding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingReasonCodes\": {\n      \"@id\": \"aws:findingReasonCodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"utilizationMetrics\": {\n      \"@id\": \"aws:utilizationMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lookBackPeriodInDays\": {\n      \"@id\": \"aws:lookBackPeriodInDays\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationOptions\": {\n      \"@id\": \"aws:recommendationOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationSources\": {\n      \"@id\": \"aws:recommendationSources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastRefreshTimestamp\": {\n      \"@id\": \"aws:lastRefreshTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentPerformanceRisk\": {\n      \"@id\": \"aws:currentPerformanceRisk\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"effectiveRecommendationPreferences\": {\n      \"@id\": \"aws:effectiveRecommendationPreferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inferredWorkloadTypes\": {\n      \"@id\": \"aws:inferredWorkloadTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceState\": {\n      \"@id\": \"aws:instanceState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalMetricStatus\": {\n      \"@id\": \"aws:externalMetricStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"statistic\": {\n      \"@id\": \"aws:statistic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lowerBoundValue\": {\n      \"@id\": \"aws:lowerBoundValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upperBoundValue\": {\n      \"@id\": \"aws:upperBoundValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedMonthlySavings\": {\n      \"@id\": \"aws:estimatedMonthlySavings\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeArns\": {\n      \"@id\": \"aws:volumeArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"aws:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"aws:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"aws:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountIds\": {\n      \"@id\": \"aws:accountIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"aws:values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucket\": {\n      \"@id\": \"aws:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"aws:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadataKey\": {\n      \"@id\": \"aws:metadataKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rank\": {\n      \"@id\": \"aws:rank\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"memorySize\": {\n      \"@id\": \"aws:memorySize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectedUtilizationMetrics\": {\n      \"@id\": \"aws:projectedUtilizationMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"savingsOpportunity\": {\n      \"@id\": \"aws:savingsOpportunity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationSourceArn\": {\n      \"@id\": \"aws:recommendationSourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationSourceType\": {\n      \"@id\": \"aws:recommendationSourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"aws:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Destination\": {\n      \"@id\": \"aws:s3Destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summaries\": {\n      \"@id\": \"aws:summaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationResourceType\": {\n      \"@id\": \"aws:recommendationResourceType\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"currentPerformanceRiskRatings\": {\n      \"@id\": \"aws:currentPerformanceRiskRatings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inferredWorkloadSavings\": {\n      \"@id\": \"aws:inferredWorkloadSavings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionRecommendations\": {\n      \"@id\": \"aws:lambdaFunctionRecommendations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"aws:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"performanceRisk\": {\n      \"@id\": \"aws:performanceRisk\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrationEffort\": {\n      \"@id\": \"aws:migrationEffort\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendedInstanceType\": {\n      \"@id\": \"aws:recommendedInstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectedMetrics\": {\n      \"@id\": \"aws:projectedMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldsToExport\"\
  : {\n      \"@id\": \"aws:fieldsToExport\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3DestinationConfig\": {\n      \"@id\": \"aws:s3DestinationConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileFormat\": {\n      \"@id\": \"aws:fileFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeMemberAccounts\": {\n      \"@id\": \"aws:includeMemberAccounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendedOptionProjectedMetrics\": {\n      \"@id\": \"aws:recommendedOptionProjectedMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"aws:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedTimestamp\": {\n      \"@id\": \"aws:lastUpdatedTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerName\": {\n      \"@id\": \"aws:containerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  memorySizeConfiguration\": {\n      \"@id\": \"aws:memorySizeConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpu\": {\n      \"@id\": \"aws:cpu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeRecommendations\": {\n      \"@id\": \"aws:volumeRecommendations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"aws:errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"savingsOpportunityPercentage\": {\n      \"@id\": \"aws:savingsOpportunityPercentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobIds\": {\n      \"@id\": \"aws:jobIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationExportJobs\": {\n      \"@id\": \"aws:recommendationExportJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoScalingGroupRecommendations\": {\n      \"@id\": \"aws:autoScalingGroupRecommendations\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"memory\": {\n      \"@id\": \"aws:memory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memoryReservation\": {\n      \"@id\": \"aws:memoryReservation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationPreferences\": {\n      \"@id\": \"aws:recommendationPreferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memberAccountsEnrolled\": {\n      \"@id\": \"aws:memberAccountsEnrolled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfMemberAccountsOptedIn\": {\n      \"@id\": \"aws:numberOfMemberAccountsOptedIn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceType\": {\n      \"@id\": \"aws:instanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformDifferences\": {\n      \"@id\": \"aws:platformDifferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"desiredCapacity\": {\n      \"@id\": \"aws:desiredCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minSize\": {\n      \"@id\": \"aws:minSize\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"maxSize\": {\n      \"@id\": \"aws:maxSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamps\": {\n      \"@id\": \"aws:timestamps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"aws:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"aws:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceArn\": {\n      \"@id\": \"aws:serviceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentServiceConfiguration\": {\n      \"@id\": \"aws:currentServiceConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lookbackPeriodInDays\": {\n      \"@id\": \"aws:lookbackPeriodInDays\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchType\": {\n      \"@id\": \"aws:launchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceRecommendationOptions\": {\n      \"@id\": \"aws:serviceRecommendationOptions\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"resourceArn\": {\n      \"@id\": \"aws:resourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3\": {\n      \"@id\": \"aws:s3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"aws:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceRecommendations\": {\n      \"@id\": \"aws:instanceRecommendations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionArns\": {\n      \"@id\": \"aws:functionArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedInfrastructureMetrics\": {\n      \"@id\": \"aws:enhancedInfrastructureMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalMetricsPreference\": {\n      \"@id\": \"aws:externalMetricsPreference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyPrefix\": {\n      \"@id\": \"aws:keyPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoScalingGroupArn\": {\n      \"@id\": \"aws:autoScalingGroupArn\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"autoScalingGroupName\": {\n      \"@id\": \"aws:autoScalingGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentConfiguration\": {\n      \"@id\": \"aws:currentConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpuVendorArchitectures\": {\n      \"@id\": \"aws:cpuVendorArchitectures\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"aws:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTimestamp\": {\n      \"@id\": \"aws:creationTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureReason\": {\n      \"@id\": \"aws:failureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stat\": {\n      \"@id\": \"aws:stat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"aws:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"aws:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"\
  @id\": \"aws:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoScalingGroupArns\": {\n      \"@id\": \"aws:autoScalingGroupArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerRecommendations\": {\n      \"@id\": \"aws:containerRecommendations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerConfigurations\": {\n      \"@id\": \"aws:containerConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoScalingConfiguration\": {\n      \"@id\": \"aws:autoScalingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskDefinitionArn\": {\n      \"@id\": \"aws:taskDefinitionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"high\": {\n      \"@id\": \"aws:high\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medium\": {\n      \"@id\": \"aws:medium\",\n      \"@type\": \"xsd:string\"\n    },\n    \"low\": {\n      \"@id\": \"aws:low\",\n      \"@type\": \"xsd:string\"\n    },\n    \"veryLow\": {\n      \"@id\": \"aws:veryLow\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"volumeArn\": {\n      \"@id\": \"aws:volumeArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeRecommendationOptions\": {\n      \"@id\": \"aws:volumeRecommendationOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationSummaries\": {\n      \"@id\": \"aws:recommendationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"aws:statusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceArns\": {\n      \"@id\": \"aws:instanceArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationPreferenceNames\": {\n      \"@id\": \"aws:recommendationPreferenceNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionArn\": {\n      \"@id\": \"aws:functionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionVersion\": {\n      \"@id\": \"aws:functionVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentMemorySize\": {\n      \"@id\": \"\
  aws:currentMemorySize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfInvocations\": {\n      \"@id\": \"aws:numberOfInvocations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memorySizeRecommendationOptions\": {\n      \"@id\": \"aws:memorySizeRecommendationOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendationPreferencesDetails\": {\n      \"@id\": \"aws:recommendationPreferencesDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceArns\": {\n      \"@id\": \"aws:serviceArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecsServiceRecommendations\": {\n      \"@id\": \"aws:ecsServiceRecommendations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendedCpuUnits\": {\n      \"@id\": \"aws:recommendedCpuUnits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendedMemorySize\": {\n      \"@id\": \"aws:recommendedMemorySize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"aws:source\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"upperBoundValues\": {\n      \"@id\": \"aws:upperBoundValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lowerBoundValues\": {\n      \"@id\": \"aws:lowerBoundValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountEnrollmentStatuses\": {\n      \"@id\": \"aws:accountEnrollmentStatuses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reasonCodeSummaries\": {\n      \"@id\": \"aws:reasonCodeSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeType\": {\n      \"@id\": \"aws:volumeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeSize\": {\n      \"@id\": \"aws:volumeSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeBaselineIOPS\": {\n      \"@id\": \"aws:volumeBaselineIOPS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeBurstIOPS\": {\n      \"@id\": \"aws:volumeBurstIOPS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeBaselineThroughput\": {\n      \"@id\": \"aws:volumeBaselineThroughput\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeBurstThroughput\": {\n      \"@id\": \"aws:volumeBurstThroughput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rootVolume\": {\n      \"@id\": \"aws:rootVolume\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-compute-optimizer/refs/heads/main/json-ld/amazon-compute-optimizer-context.jsonld
tags:
- AWS
- Cost Optimization
- FinOps
- Machine Learning
- Resource Recommendations
- JSON-LD
- Linked Data
- Semantic Web
---

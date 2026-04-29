---
api_specs:
- filename: amazon-msk-openapi-original.yml
  format: yaml
  label: Amazon MSK API
  slug: msk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-msk/refs/heads/main/openapi/amazon-msk-openapi-original.yml
class_count: 139
classes:
- StorageInfo
- ListClustersRequest
- NodeInfo
- ClusterOperationStep
- UpdateBrokerCountResponse
- UpdateConfigurationRequest
- EncryptionAtRest
- ListClustersResponse
- Scram
- ConfigurationInfo
- DeleteClusterRequest
- DescribeClusterResponse
- RebootBrokerRequest
- KafkaVersionStatus
- UpdateBrokerStorageResponse
- BatchAssociateScramSecretRequest
- BrokerLogs
- UpdateClusterKafkaVersionRequest
- UpdateMonitoringResponse
- BrokerAZDistribution
- KafkaVersion
- ServerlessSasl
- Tls
- DescribeConfigurationRevisionRequest
- ConnectivityInfo
- GetCompatibleKafkaVersionsResponse
- StorageMode
- CreateClusterV2Request
- CompatibleKafkaVersion
- ClusterInfo
- ClientBroker
- Iam
- Unauthenticated
- ClusterState
- DescribeConfigurationRequest
- BatchDisassociateScramSecretRequest
- ListNodesRequest
- TagResourceRequest
- UpdateClusterConfigurationRequest
- LoggingInfo
- PublicAccess
- CloudWatchLogs
- Firehose
- NodeExporter
- CreateClusterResponse
- VpcConfig
- ServerlessRequest
- ListScramSecretsRequest
- UnauthorizedException
- BrokerNodeGroupInfo
- BrokerEBSVolumeInfo
- StateInfo
- ListScramSecretsResponse
- ListConfigurationRevisionsResponse
- ZookeeperNodeInfo
- DeleteConfigurationResponse
- ListConfigurationsRequest
- EBSStorageInfo
- BatchDisassociateScramSecretResponse
- UpdateStorageResponse
- ListClusterOperationsRequest
- MaxResults
- UpdateBrokerTypeRequest
- ServerlessClientAuthentication
- BatchAssociateScramSecretResponse
- PrometheusInfo
- ClusterOperationStepInfo
- UpdateClusterConfigurationResponse
- UpdateBrokerTypeResponse
- UpdateSecurityResponse
- ConfigurationState
- ListConfigurationRevisionsRequest
- UntagResourceRequest
- CreateConfigurationResponse
- DescribeClusterOperationRequest
- OpenMonitoringInfo
- CreateClusterRequest
- OpenMonitoring
- UpdateBrokerCountRequest
- ProvisionedThroughput
- Sasl
- Serverless
- UpdateMonitoringRequest
- DeleteClusterResponse
- ErrorInfo
- BrokerNodeInfo
- UpdateSecurityRequest
- UpdateConnectivityRequest
- GetCompatibleKafkaVersionsRequest
- JmxExporter
- DescribeClusterV2Response
- ListKafkaVersionsRequest
- ListClusterOperationsResponse
- DescribeConfigurationResponse
- ClusterOperationInfo
- UpdateClusterKafkaVersionResponse
- EncryptionInfo
- ListTagsForResourceRequest
- DescribeConfigurationRevisionResponse
- ListKafkaVersionsResponse
- UnprocessedScramSecret
- CreateClusterV2Response
- Cluster
- NodeExporterInfo
- GetBootstrapBrokersResponse
- EnhancedMonitoring
- ConfigurationRevision
- DescribeClusterOperationResponse
- S3
- JmxExporterInfo
- GetBootstrapBrokersRequest
- RebootBrokerResponse
- ClientAuthentication
- MutableClusterInfo
- ListConfigurationsResponse
- NodeType
- UpdateConnectivityResponse
- CreateConfigurationRequest
- UpdateBrokerStorageRequest
- DeleteConfigurationRequest
- ProvisionedRequest
- UpdateStorageRequest
- Configuration
- DescribeClusterRequest
- ListClustersV2Response
- Provisioned
- ListClustersV2Request
- ListNodesResponse
- UpdateConfigurationResponse
- Prometheus
- ClusterType
- DescribeClusterV2Request
- EncryptionInTransit
- ListTagsForResourceResponse
- BrokerSoftwareInfo
- description
- version
- creationTime
- name
context_file: json-ld/amazon-msk-msk-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-msk/refs/heads/main/json-ld/amazon-msk-msk-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Msk Msk Api from Amazon MSK.
layout: jsonld
name: Amazon Msk Msk Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ebsStorageInfo
  type: string
- container: ''
  name: addedToClusterTime
  type: string
- container: ''
  name: brokerNodeInfo
  type: string
- container: ''
  name: instanceType
  type: string
- container: ''
  name: nodeArn
  type: string
- container: ''
  name: nodeType
  type: string
- container: ''
  name: zookeeperNodeInfo
  type: string
- container: ''
  name: stepInfo
  type: string
- container: ''
  name: stepName
  type: string
- container: ''
  name: clusterArn
  type: string
- container: ''
  name: clusterOperationArn
  type: string
- container: ''
  name: serverProperties
  type: string
- container: ''
  name: dataVolumeKmsKeyId
  type: string
- container: ''
  name: clusterInfoList
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: enabled
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: clusterInfo
  type: string
- container: ''
  name: brokerIds
  type: string
- container: ''
  name: secretArnList
  type: string
- container: ''
  name: cloudWatchLogs
  type: string
- container: ''
  name: firehose
  type: string
- container: ''
  name: s3
  type: string
- container: ''
  name: configurationInfo
  type: string
- container: ''
  name: currentVersion
  type: string
- container: ''
  name: targetKafkaVersion
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: iam
  type: string
- container: ''
  name: certificateAuthorityArnList
  type: string
- container: ''
  name: publicAccess
  type: string
- container: ''
  name: compatibleKafkaVersions
  type: string
- container: ''
  name: clusterName
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: provisioned
  type: string
- container: ''
  name: serverless
  type: string
- container: ''
  name: sourceVersion
  type: string
- container: ''
  name: targetVersions
  type: string
- container: ''
  name: activeOperationArn
  type: string
- container: ''
  name: brokerNodeGroupInfo
  type: string
- container: ''
  name: clientAuthentication
  type: string
- container: ''
  name: currentBrokerSoftwareInfo
  type: string
- container: ''
  name: encryptionInfo
  type: string
- container: ''
  name: enhancedMonitoring
  type: string
- container: ''
  name: openMonitoring
  type: string
- container: ''
  name: loggingInfo
  type: string
- container: ''
  name: numberOfBrokerNodes
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: stateInfo
  type: string
- container: ''
  name: zookeeperConnectString
  type: string
- container: ''
  name: zookeeperConnectStringTls
  type: string
- container: ''
  name: storageMode
  type: string
- container: ''
  name: brokerLogs
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: logGroup
  type: string
- container: ''
  name: deliveryStream
  type: string
- container: ''
  name: enabledInBroker
  type: string
- container: ''
  name: subnetIds
  type: string
- container: ''
  name: securityGroupIds
  type: string
- container: ''
  name: vpcConfigs
  type: string
- container: ''
  name: brokerAzDistribution
  type: string
- container: ''
  name: clientSubnets
  type: string
- container: ''
  name: securityGroups
  type: string
- container: ''
  name: storageInfo
  type: string
- container: ''
  name: connectivityInfo
  type: string
- container: ''
  name: kafkaBrokerNodeId
  type: string
- container: ''
  name: provisionedThroughput
  type: string
- container: ''
  name: volumeSizeGb
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: revisions
  type: string
- container: ''
  name: attachedEniId
  type: string
- container: ''
  name: clientVpcIpAddress
  type: string
- container: ''
  name: endpoints
  type: string
- container: ''
  name: zookeeperId
  type: string
- container: ''
  name: zookeeperVersion
  type: string
- container: ''
  name: volumeSize
  type: string
- container: ''
  name: unprocessedScramSecrets
  type: string
- container: ''
  name: targetInstanceType
  type: string
- container: ''
  name: sasl
  type: string
- container: ''
  name: jmxExporter
  type: string
- container: ''
  name: nodeExporter
  type: string
- container: ''
  name: stepStatus
  type: string
- container: ''
  name: latestRevision
  type: string
- container: ''
  name: prometheus
  type: string
- container: ''
  name: kafkaVersion
  type: string
- container: ''
  name: targetNumberOfBrokerNodes
  type: string
- container: ''
  name: volumeThroughput
  type: string
- container: ''
  name: scram
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorString
  type: string
- container: ''
  name: brokerId
  type: string
- container: ''
  name: clientSubnet
  type: string
- container: ''
  name: clusterOperationInfoList
  type: string
- container: ''
  name: kafkaVersions
  type: string
- container: ''
  name: clientRequestId
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: errorInfo
  type: string
- container: ''
  name: operationArn
  type: string
- container: ''
  name: operationState
  type: string
- container: ''
  name: operationSteps
  type: string
- container: ''
  name: operationType
  type: string
- container: ''
  name: sourceClusterInfo
  type: string
- container: ''
  name: targetClusterInfo
  type: string
- container: ''
  name: encryptionAtRest
  type: string
- container: ''
  name: encryptionInTransit
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: secretArn
  type: string
- container: ''
  name: clusterType
  type: string
- container: ''
  name: bootstrapBrokerString
  type: string
- container: ''
  name: bootstrapBrokerStringTls
  type: string
- container: ''
  name: bootstrapBrokerStringSaslScram
  type: string
- container: ''
  name: bootstrapBrokerStringSaslIam
  type: string
- container: ''
  name: bootstrapBrokerStringPublicTls
  type: string
- container: ''
  name: bootstrapBrokerStringPublicSaslScram
  type: string
- container: ''
  name: bootstrapBrokerStringPublicSaslIam
  type: string
- container: ''
  name: clusterOperationInfo
  type: string
- container: ''
  name: bucket
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: tls
  type: string
- container: ''
  name: unauthenticated
  type: string
- container: ''
  name: brokerEbsVolumeInfo
  type: string
- container: ''
  name: configurations
  type: string
- container: ''
  name: targetBrokerEbsVolumeInfo
  type: string
- container: ''
  name: nodeInfoList
  type: string
- container: ''
  name: clientBroker
  type: string
- container: ''
  name: inCluster
  type: string
- container: ''
  name: configurationArn
  type: string
- container: ''
  name: configurationRevision
  type: string
property_count: 129
provider_name: Amazon MSK
provider_slug: amazon-msk
slug: amazon-msk-msk-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StorageInfo\": \"pan:StorageInfo\",\n    \"ListClustersRequest\": \"pan:ListClustersRequest\",\n    \"NodeInfo\": \"pan:NodeInfo\",\n    \"ClusterOperationStep\": \"pan:ClusterOperationStep\",\n    \"UpdateBrokerCountResponse\": \"pan:UpdateBrokerCountResponse\",\n    \"UpdateConfigurationRequest\": \"pan:UpdateConfigurationRequest\",\n    \"EncryptionAtRest\": \"pan:EncryptionAtRest\",\n    \"ListClustersResponse\": \"pan:ListClustersResponse\",\n    \"Scram\": \"pan:Scram\",\n    \"ConfigurationInfo\": \"pan:ConfigurationInfo\",\n    \"DeleteClusterRequest\": \"pan:DeleteClusterRequest\",\n    \"DescribeClusterResponse\": \"pan:DescribeClusterResponse\",\n    \"RebootBrokerRequest\": \"pan:RebootBrokerRequest\",\n    \"KafkaVersionStatus\"\
  : \"pan:KafkaVersionStatus\",\n    \"UpdateBrokerStorageResponse\": \"pan:UpdateBrokerStorageResponse\",\n    \"BatchAssociateScramSecretRequest\": \"pan:BatchAssociateScramSecretRequest\",\n    \"BrokerLogs\": \"pan:BrokerLogs\",\n    \"UpdateClusterKafkaVersionRequest\": \"pan:UpdateClusterKafkaVersionRequest\",\n    \"UpdateMonitoringResponse\": \"pan:UpdateMonitoringResponse\",\n    \"BrokerAZDistribution\": \"pan:BrokerAZDistribution\",\n    \"KafkaVersion\": \"pan:KafkaVersion\",\n    \"ServerlessSasl\": \"pan:ServerlessSasl\",\n    \"Tls\": \"pan:Tls\",\n    \"DescribeConfigurationRevisionRequest\": \"pan:DescribeConfigurationRevisionRequest\",\n    \"ConnectivityInfo\": \"pan:ConnectivityInfo\",\n    \"GetCompatibleKafkaVersionsResponse\": \"pan:GetCompatibleKafkaVersionsResponse\",\n    \"StorageMode\": \"pan:StorageMode\",\n    \"CreateClusterV2Request\": \"pan:CreateClusterV2Request\",\n    \"CompatibleKafkaVersion\": \"pan:CompatibleKafkaVersion\",\n    \"ClusterInfo\": \"\
  pan:ClusterInfo\",\n    \"ClientBroker\": \"pan:ClientBroker\",\n    \"Iam\": \"pan:Iam\",\n    \"Unauthenticated\": \"pan:Unauthenticated\",\n    \"ClusterState\": \"pan:ClusterState\",\n    \"DescribeConfigurationRequest\": \"pan:DescribeConfigurationRequest\",\n    \"BatchDisassociateScramSecretRequest\": \"pan:BatchDisassociateScramSecretRequest\",\n    \"ListNodesRequest\": \"pan:ListNodesRequest\",\n    \"TagResourceRequest\": \"pan:TagResourceRequest\",\n    \"UpdateClusterConfigurationRequest\": \"pan:UpdateClusterConfigurationRequest\",\n    \"LoggingInfo\": \"pan:LoggingInfo\",\n    \"PublicAccess\": \"pan:PublicAccess\",\n    \"CloudWatchLogs\": \"pan:CloudWatchLogs\",\n    \"Firehose\": \"pan:Firehose\",\n    \"NodeExporter\": \"pan:NodeExporter\",\n    \"CreateClusterResponse\": \"pan:CreateClusterResponse\",\n    \"VpcConfig\": \"pan:VpcConfig\",\n    \"ServerlessRequest\": \"pan:ServerlessRequest\",\n    \"ListScramSecretsRequest\": \"pan:ListScramSecretsRequest\",\n   \
  \ \"UnauthorizedException\": \"pan:UnauthorizedException\",\n    \"BrokerNodeGroupInfo\": \"pan:BrokerNodeGroupInfo\",\n    \"BrokerEBSVolumeInfo\": \"pan:BrokerEBSVolumeInfo\",\n    \"StateInfo\": \"pan:StateInfo\",\n    \"ListScramSecretsResponse\": \"pan:ListScramSecretsResponse\",\n    \"ListConfigurationRevisionsResponse\": \"pan:ListConfigurationRevisionsResponse\",\n    \"ZookeeperNodeInfo\": \"pan:ZookeeperNodeInfo\",\n    \"DeleteConfigurationResponse\": \"pan:DeleteConfigurationResponse\",\n    \"ListConfigurationsRequest\": \"pan:ListConfigurationsRequest\",\n    \"EBSStorageInfo\": \"pan:EBSStorageInfo\",\n    \"BatchDisassociateScramSecretResponse\": \"pan:BatchDisassociateScramSecretResponse\",\n    \"UpdateStorageResponse\": \"pan:UpdateStorageResponse\",\n    \"ListClusterOperationsRequest\": \"pan:ListClusterOperationsRequest\",\n    \"MaxResults\": \"pan:MaxResults\",\n    \"UpdateBrokerTypeRequest\": \"pan:UpdateBrokerTypeRequest\",\n    \"ServerlessClientAuthentication\"\
  : \"pan:ServerlessClientAuthentication\",\n    \"BatchAssociateScramSecretResponse\": \"pan:BatchAssociateScramSecretResponse\",\n    \"PrometheusInfo\": \"pan:PrometheusInfo\",\n    \"ClusterOperationStepInfo\": \"pan:ClusterOperationStepInfo\",\n    \"UpdateClusterConfigurationResponse\": \"pan:UpdateClusterConfigurationResponse\",\n    \"UpdateBrokerTypeResponse\": \"pan:UpdateBrokerTypeResponse\",\n    \"UpdateSecurityResponse\": \"pan:UpdateSecurityResponse\",\n    \"ConfigurationState\": \"pan:ConfigurationState\",\n    \"ListConfigurationRevisionsRequest\": \"pan:ListConfigurationRevisionsRequest\",\n    \"UntagResourceRequest\": \"pan:UntagResourceRequest\",\n    \"CreateConfigurationResponse\": \"pan:CreateConfigurationResponse\",\n    \"DescribeClusterOperationRequest\": \"pan:DescribeClusterOperationRequest\",\n    \"OpenMonitoringInfo\": \"pan:OpenMonitoringInfo\",\n    \"CreateClusterRequest\": \"pan:CreateClusterRequest\",\n    \"OpenMonitoring\": \"pan:OpenMonitoring\",\n\
  \    \"UpdateBrokerCountRequest\": \"pan:UpdateBrokerCountRequest\",\n    \"ProvisionedThroughput\": \"pan:ProvisionedThroughput\",\n    \"Sasl\": \"pan:Sasl\",\n    \"Serverless\": \"pan:Serverless\",\n    \"UpdateMonitoringRequest\": \"pan:UpdateMonitoringRequest\",\n    \"DeleteClusterResponse\": \"pan:DeleteClusterResponse\",\n    \"ErrorInfo\": \"pan:ErrorInfo\",\n    \"BrokerNodeInfo\": \"pan:BrokerNodeInfo\",\n    \"UpdateSecurityRequest\": \"pan:UpdateSecurityRequest\",\n    \"UpdateConnectivityRequest\": \"pan:UpdateConnectivityRequest\",\n    \"GetCompatibleKafkaVersionsRequest\": \"pan:GetCompatibleKafkaVersionsRequest\",\n    \"JmxExporter\": \"pan:JmxExporter\",\n    \"DescribeClusterV2Response\": \"pan:DescribeClusterV2Response\",\n    \"ListKafkaVersionsRequest\": \"pan:ListKafkaVersionsRequest\",\n    \"ListClusterOperationsResponse\": \"pan:ListClusterOperationsResponse\",\n    \"DescribeConfigurationResponse\": \"pan:DescribeConfigurationResponse\",\n    \"ClusterOperationInfo\"\
  : \"pan:ClusterOperationInfo\",\n    \"UpdateClusterKafkaVersionResponse\": \"pan:UpdateClusterKafkaVersionResponse\",\n    \"EncryptionInfo\": \"pan:EncryptionInfo\",\n    \"ListTagsForResourceRequest\": \"pan:ListTagsForResourceRequest\",\n    \"DescribeConfigurationRevisionResponse\": \"pan:DescribeConfigurationRevisionResponse\",\n    \"ListKafkaVersionsResponse\": \"pan:ListKafkaVersionsResponse\",\n    \"UnprocessedScramSecret\": \"pan:UnprocessedScramSecret\",\n    \"CreateClusterV2Response\": \"pan:CreateClusterV2Response\",\n    \"Cluster\": \"pan:Cluster\",\n    \"NodeExporterInfo\": \"pan:NodeExporterInfo\",\n    \"GetBootstrapBrokersResponse\": \"pan:GetBootstrapBrokersResponse\",\n    \"EnhancedMonitoring\": \"pan:EnhancedMonitoring\",\n    \"ConfigurationRevision\": \"pan:ConfigurationRevision\",\n    \"DescribeClusterOperationResponse\": \"pan:DescribeClusterOperationResponse\",\n    \"S3\": \"pan:S3\",\n    \"JmxExporterInfo\": \"pan:JmxExporterInfo\",\n    \"GetBootstrapBrokersRequest\"\
  : \"pan:GetBootstrapBrokersRequest\",\n    \"RebootBrokerResponse\": \"pan:RebootBrokerResponse\",\n    \"ClientAuthentication\": \"pan:ClientAuthentication\",\n    \"MutableClusterInfo\": \"pan:MutableClusterInfo\",\n    \"ListConfigurationsResponse\": \"pan:ListConfigurationsResponse\",\n    \"NodeType\": \"pan:NodeType\",\n    \"UpdateConnectivityResponse\": \"pan:UpdateConnectivityResponse\",\n    \"CreateConfigurationRequest\": \"pan:CreateConfigurationRequest\",\n    \"UpdateBrokerStorageRequest\": \"pan:UpdateBrokerStorageRequest\",\n    \"DeleteConfigurationRequest\": \"pan:DeleteConfigurationRequest\",\n    \"ProvisionedRequest\": \"pan:ProvisionedRequest\",\n    \"UpdateStorageRequest\": \"pan:UpdateStorageRequest\",\n    \"Configuration\": \"pan:Configuration\",\n    \"DescribeClusterRequest\": \"pan:DescribeClusterRequest\",\n    \"ListClustersV2Response\": \"pan:ListClustersV2Response\",\n    \"Provisioned\": \"pan:Provisioned\",\n    \"ListClustersV2Request\": \"pan:ListClustersV2Request\"\
  ,\n    \"ListNodesResponse\": \"pan:ListNodesResponse\",\n    \"UpdateConfigurationResponse\": \"pan:UpdateConfigurationResponse\",\n    \"Prometheus\": \"pan:Prometheus\",\n    \"ClusterType\": \"pan:ClusterType\",\n    \"DescribeClusterV2Request\": \"pan:DescribeClusterV2Request\",\n    \"EncryptionInTransit\": \"pan:EncryptionInTransit\",\n    \"ListTagsForResourceResponse\": \"pan:ListTagsForResourceResponse\",\n    \"BrokerSoftwareInfo\": \"pan:BrokerSoftwareInfo\",\n    \"ebsStorageInfo\": {\n      \"@id\": \"pan:ebs_storage_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addedToClusterTime\": {\n      \"@id\": \"pan:added_to_cluster_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerNodeInfo\": {\n      \"@id\": \"pan:broker_node_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceType\": {\n      \"@id\": \"pan:instance_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeArn\": {\n      \"@id\": \"pan:node_arn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"nodeType\": {\n      \"@id\": \"pan:node_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zookeeperNodeInfo\": {\n      \"@id\": \"pan:zookeeper_node_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepInfo\": {\n      \"@id\": \"pan:step_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepName\": {\n      \"@id\": \"pan:step_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterArn\": {\n      \"@id\": \"pan:cluster_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterOperationArn\": {\n      \"@id\": \"pan:cluster_operation_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"serverProperties\": {\n      \"@id\": \"pan:server_properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataVolumeKmsKeyId\": {\n      \"@id\": \"pan:data_volume_kms_key_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterInfoList\": {\n      \"@id\": \"pan:cluster_info_list\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"pan:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"pan:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterInfo\": {\n      \"@id\": \"pan:cluster_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerIds\": {\n      \"@id\": \"pan:broker_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretArnList\": {\n      \"@id\": \"pan:secret_arn_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudWatchLogs\": {\n      \"@id\": \"pan:cloud_watch_logs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firehose\": {\n      \"@id\": \"pan:firehose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3\": {\n      \"@id\": \"pan:s3\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"configurationInfo\": {\n      \"@id\": \"pan:configuration_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentVersion\": {\n      \"@id\": \"pan:current_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetKafkaVersion\": {\n      \"@id\": \"pan:target_kafka_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iam\": {\n      \"@id\": \"pan:iam\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateAuthorityArnList\": {\n      \"@id\": \"pan:certificate_authority_arn_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicAccess\": {\n      \"@id\": \"pan:public_access\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compatibleKafkaVersions\": {\n      \"@id\": \"pan:compatible_kafka_versions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterName\": {\n      \"@id\": \"pan:cluster_name\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioned\": {\n      \"@id\": \"pan:provisioned\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serverless\": {\n      \"@id\": \"pan:serverless\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceVersion\": {\n      \"@id\": \"pan:source_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetVersions\": {\n      \"@id\": \"pan:target_versions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeOperationArn\": {\n      \"@id\": \"pan:active_operation_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerNodeGroupInfo\": {\n      \"@id\": \"pan:broker_node_group_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientAuthentication\": {\n      \"@id\": \"pan:client_authentication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": \"schema:dateCreated\",\n    \"currentBrokerSoftwareInfo\": {\n      \"@id\": \"\
  pan:current_broker_software_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionInfo\": {\n      \"@id\": \"pan:encryption_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedMonitoring\": {\n      \"@id\": \"pan:enhanced_monitoring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openMonitoring\": {\n      \"@id\": \"pan:open_monitoring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loggingInfo\": {\n      \"@id\": \"pan:logging_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfBrokerNodes\": {\n      \"@id\": \"pan:number_of_broker_nodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"pan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateInfo\": {\n      \"@id\": \"pan:state_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zookeeperConnectString\": {\n      \"@id\": \"pan:zookeeper_connect_string\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zookeeperConnectStringTls\": {\n      \"@id\"\
  : \"pan:zookeeper_connect_string_tls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageMode\": {\n      \"@id\": \"pan:storage_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerLogs\": {\n      \"@id\": \"pan:broker_logs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logGroup\": {\n      \"@id\": \"pan:log_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryStream\": {\n      \"@id\": \"pan:delivery_stream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabledInBroker\": {\n      \"@id\": \"pan:enabled_in_broker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"pan:subnet_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroupIds\": {\n      \"@id\": \"pan:security_group_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcConfigs\": {\n      \"@id\": \"pan:vpc_configs\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"brokerAzDistribution\": {\n      \"@id\": \"pan:broker_az_distribution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSubnets\": {\n      \"@id\": \"pan:client_subnets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroups\": {\n      \"@id\": \"pan:security_groups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageInfo\": {\n      \"@id\": \"pan:storage_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectivityInfo\": {\n      \"@id\": \"pan:connectivity_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kafkaBrokerNodeId\": {\n      \"@id\": \"pan:kafka_broker_node_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisionedThroughput\": {\n      \"@id\": \"pan:provisioned_throughput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeSizeGb\": {\n      \"@id\": \"pan:volume_size_gb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"pan:code\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"message\": {\n      \"@id\": \"pan:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisions\": {\n      \"@id\": \"pan:revisions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachedEniId\": {\n      \"@id\": \"pan:attached_eni_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientVpcIpAddress\": {\n      \"@id\": \"pan:client_vpc_ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoints\": {\n      \"@id\": \"pan:endpoints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zookeeperId\": {\n      \"@id\": \"pan:zookeeper_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zookeeperVersion\": {\n      \"@id\": \"pan:zookeeper_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeSize\": {\n      \"@id\": \"pan:volume_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unprocessedScramSecrets\": {\n      \"@id\": \"pan:unprocessed_scram_secrets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetInstanceType\": {\n      \"\
  @id\": \"pan:target_instance_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sasl\": {\n      \"@id\": \"pan:sasl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jmxExporter\": {\n      \"@id\": \"pan:jmx_exporter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeExporter\": {\n      \"@id\": \"pan:node_exporter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepStatus\": {\n      \"@id\": \"pan:step_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestRevision\": {\n      \"@id\": \"pan:latest_revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"prometheus\": {\n      \"@id\": \"pan:prometheus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kafkaVersion\": {\n      \"@id\": \"pan:kafka_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetNumberOfBrokerNodes\": {\n      \"@id\": \"pan:target_number_of_broker_nodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeThroughput\": {\n      \"@id\":\
  \ \"pan:volume_throughput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scram\": {\n      \"@id\": \"pan:scram\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"pan:error_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorString\": {\n      \"@id\": \"pan:error_string\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerId\": {\n      \"@id\": \"pan:broker_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSubnet\": {\n      \"@id\": \"pan:client_subnet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterOperationInfoList\": {\n      \"@id\": \"pan:cluster_operation_info_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kafkaVersions\": {\n      \"@id\": \"pan:kafka_versions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientRequestId\": {\n      \"@id\": \"pan:client_request_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"pan:end_time\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"errorInfo\": {\n      \"@id\": \"pan:error_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationArn\": {\n      \"@id\": \"pan:operation_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationState\": {\n      \"@id\": \"pan:operation_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationSteps\": {\n      \"@id\": \"pan:operation_steps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationType\": {\n      \"@id\": \"pan:operation_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceClusterInfo\": {\n      \"@id\": \"pan:source_cluster_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetClusterInfo\": {\n      \"@id\": \"pan:target_cluster_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionAtRest\": {\n      \"@id\": \"pan:encryption_at_rest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionInTransit\": {\n      \"@id\": \"pan:encryption_in_transit\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"errorMessage\": {\n      \"@id\": \"pan:error_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretArn\": {\n      \"@id\": \"pan:secret_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterType\": {\n      \"@id\": \"pan:cluster_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bootstrapBrokerString\": {\n      \"@id\": \"pan:bootstrap_broker_string\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bootstrapBrokerStringTls\": {\n      \"@id\": \"pan:bootstrap_broker_string_tls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bootstrapBrokerStringSaslScram\": {\n      \"@id\": \"pan:bootstrap_broker_string_sasl_scram\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bootstrapBrokerStringSaslIam\": {\n      \"@id\": \"pan:bootstrap_broker_string_sasl_iam\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bootstrapBrokerStringPublicTls\": {\n      \"@id\": \"pan:bootstrap_broker_string_public_tls\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"bootstrapBrokerStringPublicSaslScram\": {\n      \"@id\": \"pan:bootstrap_broker_string_public_sasl_scram\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bootstrapBrokerStringPublicSaslIam\": {\n      \"@id\": \"pan:bootstrap_broker_string_public_sasl_iam\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterOperationInfo\": {\n      \"@id\": \"pan:cluster_operation_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucket\": {\n      \"@id\": \"pan:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"pan:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tls\": {\n      \"@id\": \"pan:tls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unauthenticated\": {\n      \"@id\": \"pan:unauthenticated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerEbsVolumeInfo\": {\n      \"@id\": \"pan:broker_ebs_volume_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurations\": {\n      \"@id\": \"pan:configurations\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"targetBrokerEbsVolumeInfo\": {\n      \"@id\": \"pan:target_broker_ebs_volume_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nodeInfoList\": {\n      \"@id\": \"pan:node_info_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientBroker\": {\n      \"@id\": \"pan:client_broker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inCluster\": {\n      \"@id\": \"pan:in_cluster\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationArn\": {\n      \"@id\": \"pan:configuration_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationRevision\": {\n      \"@id\": \"pan:configuration_revision\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-msk/refs/heads/main/json-ld/amazon-msk-msk-api-context.jsonld
tags:
- AWS
- Broadcasting
- Media Processing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: amazon-mq-openapi-original.yml
  format: yaml
  label: Amazon MQ API
  slug: mq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mq/refs/heads/main/openapi/amazon-mq-openapi-original.yml
class_count: 76
classes:
- RebootBrokerRequest
- CreateUserRequest
- CreateUserResponse
- EngineType
- BrokerSummary
- BrokerStorageType
- DescribeBrokerInstanceOptionsResponse
- UpdateConfigurationResponse
- Logs
- UpdateUserRequest
- BrokerEngineType
- BrokerInstance
- DescribeConfigurationRequest
- DescribeConfigurationRevisionResponse
- DayOfWeek
- ListUsersRequest
- DeleteUserRequest
- Configuration
- UpdateUserResponse
- ListConfigurationsResponse
- CreateConfigurationRequest
- DeploymentMode
- DeleteBrokerRequest
- DeleteBrokerResponse
- LogsSummary
- ListUsersResponse
- DescribeBrokerEngineTypesResponse
- ListTagsRequest
- DeleteTagsRequest
- PendingLogs
- DescribeConfigurationResponse
- SanitizationWarningReason
- ListConfigurationsRequest
- ListConfigurationRevisionsResponse
- CreateTagsRequest
- CreateBrokerRequest
- DescribeUserResponse
- DeleteUserResponse
- ListTagsResponse
- DescribeConfigurationRevisionRequest
- UnauthorizedException
- BrokerInstanceOption
- UpdateBrokerRequest
- UserSummary
- DescribeBrokerResponse
- UpdateBrokerResponse
- ListBrokersResponse
- User
- CreateConfigurationResponse
- UpdateConfigurationRequest
- AuthenticationStrategy
- ConfigurationRevision
- LdapServerMetadataOutput
- WeeklyStartTime
- LdapServerMetadataInput
- BrokerState
- RebootBrokerResponse
- Configurations
- DescribeBrokerEngineTypesRequest
- ConfigurationId
- DescribeBrokerInstanceOptionsRequest
- ListConfigurationRevisionsRequest
- MaxResults
- UserPendingChanges
- CreateBrokerResponse
- DescribeBrokerRequest
- ChangeType
- ActionRequired
- DescribeUserRequest
- ListBrokersRequest
- EncryptionOptions
- EngineVersion
- AvailabilityZone
- SanitizationWarning
- name
- description
context_file: json-ld/amazon-mq-mq-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-mq/refs/heads/main/json-ld/amazon-mq-mq-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Mq Mq Api from Amazon MQ.
layout: jsonld
name: Amazon Mq Mq Api Context
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
  name: consoleAccess
  type: string
- container: ''
  name: groups
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: brokerArn
  type: string
- container: ''
  name: brokerId
  type: string
- container: ''
  name: brokerName
  type: string
- container: ''
  name: brokerState
  type: string
- container: ''
  name: created
  type: string
- container: ''
  name: deploymentMode
  type: string
- container: ''
  name: engineType
  type: string
- container: ''
  name: hostInstanceType
  type: string
- container: ''
  name: brokerInstanceOptions
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: latestRevision
  type: string
- container: ''
  name: warnings
  type: string
- container: ''
  name: audit
  type: string
- container: ''
  name: general
  type: string
- container: ''
  name: engineVersions
  type: string
- container: ''
  name: consoleUrl
  type: string
- container: ''
  name: endpoints
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: configurationId
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: authenticationStrategy
  type: string
- container: ''
  name: engineVersion
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: configurations
  type: string
- container: ''
  name: auditLogGroup
  type: string
- container: ''
  name: generalLogGroup
  type: string
- container: ''
  name: pending
  type: string
- container: ''
  name: users
  type: string
- container: ''
  name: brokerEngineTypes
  type: string
- container: ''
  name: revisions
  type: string
- container: ''
  name: autoMinorVersionUpgrade
  type: string
- container: ''
  name: configuration
  type: string
- container: ''
  name: creatorRequestId
  type: string
- container: ''
  name: encryptionOptions
  type: string
- container: ''
  name: ldapServerMetadata
  type: string
- container: ''
  name: logs
  type: string
- container: ''
  name: maintenanceWindowStartTime
  type: string
- container: ''
  name: publiclyAccessible
  type: string
- container: ''
  name: securityGroups
  type: string
- container: ''
  name: storageType
  type: string
- container: ''
  name: subnetIds
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: availabilityZones
  type: string
- container: ''
  name: supportedDeploymentModes
  type: string
- container: ''
  name: supportedEngineVersions
  type: string
- container: ''
  name: pendingChange
  type: string
- container: ''
  name: actionsRequired
  type: string
- container: ''
  name: brokerInstances
  type: string
- container: ''
  name: pendingAuthenticationStrategy
  type: string
- container: ''
  name: pendingEngineVersion
  type: string
- container: ''
  name: pendingHostInstanceType
  type: string
- container: ''
  name: pendingLdapServerMetadata
  type: string
- container: ''
  name: pendingSecurityGroups
  type: string
- container: ''
  name: brokerSummaries
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: hosts
  type: string
- container: ''
  name: roleBase
  type: string
- container: ''
  name: roleName
  type: string
- container: ''
  name: roleSearchMatching
  type: string
- container: ''
  name: roleSearchSubtree
  type: string
- container: ''
  name: serviceAccountUsername
  type: string
- container: ''
  name: userBase
  type: string
- container: ''
  name: userRoleName
  type: string
- container: ''
  name: userSearchMatching
  type: string
- container: ''
  name: userSearchSubtree
  type: string
- container: ''
  name: dayOfWeek
  type: string
- container: ''
  name: timeOfDay
  type: string
- container: ''
  name: timeZone
  type: string
- container: ''
  name: serviceAccountPassword
  type: string
- container: ''
  name: current
  type: string
- container: ''
  name: history
  type: string
- container: ''
  name: actionRequiredCode
  type: string
- container: ''
  name: actionRequiredInfo
  type: string
- container: ''
  name: kmsKeyId
  type: string
- container: ''
  name: useAwsOwnedKey
  type: string
- container: ''
  name: attributeName
  type: string
- container: ''
  name: elementName
  type: string
- container: ''
  name: reason
  type: string
property_count: 84
provider_name: Amazon MQ
provider_slug: amazon-mq
slug: amazon-mq-mq-api-context
source_filename: amazon-mq-mq-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RebootBrokerRequest\": \"pan:RebootBrokerRequest\",\n    \"CreateUserRequest\": \"pan:CreateUserRequest\",\n    \"CreateUserResponse\": \"pan:CreateUserResponse\",\n    \"EngineType\": \"pan:EngineType\",\n    \"BrokerSummary\": \"pan:BrokerSummary\",\n    \"BrokerStorageType\": \"pan:BrokerStorageType\",\n    \"DescribeBrokerInstanceOptionsResponse\": \"pan:DescribeBrokerInstanceOptionsResponse\",\n    \"UpdateConfigurationResponse\": \"pan:UpdateConfigurationResponse\",\n    \"Logs\": \"pan:Logs\",\n    \"UpdateUserRequest\": \"pan:UpdateUserRequest\",\n    \"BrokerEngineType\": \"pan:BrokerEngineType\",\n    \"BrokerInstance\": \"pan:BrokerInstance\",\n    \"DescribeConfigurationRequest\": \"pan:DescribeConfigurationRequest\",\n    \"DescribeConfigurationRevisionResponse\"\
  : \"pan:DescribeConfigurationRevisionResponse\",\n    \"DayOfWeek\": \"pan:DayOfWeek\",\n    \"ListUsersRequest\": \"pan:ListUsersRequest\",\n    \"DeleteUserRequest\": \"pan:DeleteUserRequest\",\n    \"Configuration\": \"pan:Configuration\",\n    \"UpdateUserResponse\": \"pan:UpdateUserResponse\",\n    \"ListConfigurationsResponse\": \"pan:ListConfigurationsResponse\",\n    \"CreateConfigurationRequest\": \"pan:CreateConfigurationRequest\",\n    \"DeploymentMode\": \"pan:DeploymentMode\",\n    \"DeleteBrokerRequest\": \"pan:DeleteBrokerRequest\",\n    \"DeleteBrokerResponse\": \"pan:DeleteBrokerResponse\",\n    \"LogsSummary\": \"pan:LogsSummary\",\n    \"ListUsersResponse\": \"pan:ListUsersResponse\",\n    \"DescribeBrokerEngineTypesResponse\": \"pan:DescribeBrokerEngineTypesResponse\",\n    \"ListTagsRequest\": \"pan:ListTagsRequest\",\n    \"DeleteTagsRequest\": \"pan:DeleteTagsRequest\",\n    \"PendingLogs\": \"pan:PendingLogs\",\n    \"DescribeConfigurationResponse\": \"pan:DescribeConfigurationResponse\"\
  ,\n    \"SanitizationWarningReason\": \"pan:SanitizationWarningReason\",\n    \"ListConfigurationsRequest\": \"pan:ListConfigurationsRequest\",\n    \"ListConfigurationRevisionsResponse\": \"pan:ListConfigurationRevisionsResponse\",\n    \"CreateTagsRequest\": \"pan:CreateTagsRequest\",\n    \"CreateBrokerRequest\": \"pan:CreateBrokerRequest\",\n    \"DescribeUserResponse\": \"pan:DescribeUserResponse\",\n    \"DeleteUserResponse\": \"pan:DeleteUserResponse\",\n    \"ListTagsResponse\": \"pan:ListTagsResponse\",\n    \"DescribeConfigurationRevisionRequest\": \"pan:DescribeConfigurationRevisionRequest\",\n    \"UnauthorizedException\": \"pan:UnauthorizedException\",\n    \"BrokerInstanceOption\": \"pan:BrokerInstanceOption\",\n    \"UpdateBrokerRequest\": \"pan:UpdateBrokerRequest\",\n    \"UserSummary\": \"pan:UserSummary\",\n    \"DescribeBrokerResponse\": \"pan:DescribeBrokerResponse\",\n    \"UpdateBrokerResponse\": \"pan:UpdateBrokerResponse\",\n    \"ListBrokersResponse\": \"pan:ListBrokersResponse\"\
  ,\n    \"User\": \"pan:User\",\n    \"CreateConfigurationResponse\": \"pan:CreateConfigurationResponse\",\n    \"UpdateConfigurationRequest\": \"pan:UpdateConfigurationRequest\",\n    \"AuthenticationStrategy\": \"pan:AuthenticationStrategy\",\n    \"ConfigurationRevision\": \"pan:ConfigurationRevision\",\n    \"LdapServerMetadataOutput\": \"pan:LdapServerMetadataOutput\",\n    \"WeeklyStartTime\": \"pan:WeeklyStartTime\",\n    \"LdapServerMetadataInput\": \"pan:LdapServerMetadataInput\",\n    \"BrokerState\": \"pan:BrokerState\",\n    \"RebootBrokerResponse\": \"pan:RebootBrokerResponse\",\n    \"Configurations\": \"pan:Configurations\",\n    \"DescribeBrokerEngineTypesRequest\": \"pan:DescribeBrokerEngineTypesRequest\",\n    \"ConfigurationId\": \"pan:ConfigurationId\",\n    \"DescribeBrokerInstanceOptionsRequest\": \"pan:DescribeBrokerInstanceOptionsRequest\",\n    \"ListConfigurationRevisionsRequest\": \"pan:ListConfigurationRevisionsRequest\",\n    \"MaxResults\": \"pan:MaxResults\"\
  ,\n    \"UserPendingChanges\": \"pan:UserPendingChanges\",\n    \"CreateBrokerResponse\": \"pan:CreateBrokerResponse\",\n    \"DescribeBrokerRequest\": \"pan:DescribeBrokerRequest\",\n    \"ChangeType\": \"pan:ChangeType\",\n    \"ActionRequired\": \"pan:ActionRequired\",\n    \"DescribeUserRequest\": \"pan:DescribeUserRequest\",\n    \"ListBrokersRequest\": \"pan:ListBrokersRequest\",\n    \"EncryptionOptions\": \"pan:EncryptionOptions\",\n    \"EngineVersion\": \"pan:EngineVersion\",\n    \"AvailabilityZone\": \"pan:AvailabilityZone\",\n    \"SanitizationWarning\": \"pan:SanitizationWarning\",\n    \"consoleAccess\": {\n      \"@id\": \"pan:console_access\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groups\": {\n      \"@id\": \"pan:groups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"pan:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerArn\": {\n      \"@id\": \"pan:broker_arn\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"brokerId\": {\n      \"@id\": \"pan:broker_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerName\": {\n      \"@id\": \"pan:broker_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerState\": {\n      \"@id\": \"pan:broker_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"pan:created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentMode\": {\n      \"@id\": \"pan:deployment_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engineType\": {\n      \"@id\": \"pan:engine_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostInstanceType\": {\n      \"@id\": \"pan:host_instance_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerInstanceOptions\": {\n      \"@id\": \"pan:broker_instance_options\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"pan:max_results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:next_token\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"pan:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestRevision\": {\n      \"@id\": \"pan:latest_revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"warnings\": {\n      \"@id\": \"pan:warnings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"audit\": {\n      \"@id\": \"pan:audit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"general\": {\n      \"@id\": \"pan:general\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engineVersions\": {\n      \"@id\": \"pan:engine_versions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consoleUrl\": {\n      \"@id\": \"pan:console_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoints\": {\n      \"@id\": \"pan:endpoints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"pan:ip_address\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"configurationId\": {\n      \"@id\": \"pan:configuration_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"pan:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"authenticationStrategy\": {\n      \"@id\": \"pan:authentication_strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engineVersion\": {\n      \"@id\": \"pan:engine_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurations\": {\n      \"@id\": \"pan:configurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auditLogGroup\": {\n      \"@id\": \"pan:audit_log_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generalLogGroup\": {\n      \"@id\": \"pan:general_log_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pending\": {\n      \"@id\": \"pan:pending\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"users\": {\n      \"@id\": \"pan:users\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerEngineTypes\": {\n      \"@id\": \"pan:broker_engine_types\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisions\": {\n      \"@id\": \"pan:revisions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoMinorVersionUpgrade\": {\n      \"@id\": \"pan:auto_minor_version_upgrade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"pan:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creatorRequestId\": {\n      \"@id\": \"pan:creator_request_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionOptions\": {\n      \"@id\": \"pan:encryption_options\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ldapServerMetadata\": {\n      \"@id\": \"pan:ldap_server_metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logs\": {\n      \"@id\": \"pan:logs\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"maintenanceWindowStartTime\": {\n      \"@id\": \"pan:maintenance_window_start_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publiclyAccessible\": {\n      \"@id\": \"pan:publicly_accessible\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroups\": {\n      \"@id\": \"pan:security_groups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageType\": {\n      \"@id\": \"pan:storage_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"pan:subnet_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"pan:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availabilityZones\": {\n      \"@id\": \"pan:availability_zones\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedDeploymentModes\": {\n      \"@id\": \"pan:supported_deployment_modes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedEngineVersions\": {\n      \"@id\": \"pan:supported_engine_versions\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"pendingChange\": {\n      \"@id\": \"pan:pending_change\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionsRequired\": {\n      \"@id\": \"pan:actions_required\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brokerInstances\": {\n      \"@id\": \"pan:broker_instances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pendingAuthenticationStrategy\": {\n      \"@id\": \"pan:pending_authentication_strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pendingEngineVersion\": {\n      \"@id\": \"pan:pending_engine_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pendingHostInstanceType\": {\n      \"@id\": \"pan:pending_host_instance_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pendingLdapServerMetadata\": {\n      \"@id\": \"pan:pending_ldap_server_metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pendingSecurityGroups\": {\n      \"@id\": \"pan:pending_security_groups\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"brokerSummaries\": {\n      \"@id\": \"pan:broker_summaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"pan:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hosts\": {\n      \"@id\": \"pan:hosts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleBase\": {\n      \"@id\": \"pan:role_base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleName\": {\n      \"@id\": \"pan:role_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleSearchMatching\": {\n      \"@id\": \"pan:role_search_matching\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleSearchSubtree\": {\n      \"@id\": \"pan:role_search_subtree\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceAccountUsername\": {\n      \"@id\": \"pan:service_account_username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userBase\": {\n      \"@id\": \"pan:user_base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userRoleName\": {\n      \"@id\": \"\
  pan:user_role_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userSearchMatching\": {\n      \"@id\": \"pan:user_search_matching\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userSearchSubtree\": {\n      \"@id\": \"pan:user_search_subtree\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dayOfWeek\": {\n      \"@id\": \"pan:day_of_week\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeOfDay\": {\n      \"@id\": \"pan:time_of_day\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeZone\": {\n      \"@id\": \"pan:time_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceAccountPassword\": {\n      \"@id\": \"pan:service_account_password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"current\": {\n      \"@id\": \"pan:current\",\n      \"@type\": \"xsd:string\"\n    },\n    \"history\": {\n      \"@id\": \"pan:history\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionRequiredCode\": {\n      \"@id\": \"pan:action_required_code\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"actionRequiredInfo\": {\n      \"@id\": \"pan:action_required_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"pan:kms_key_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useAwsOwnedKey\": {\n      \"@id\": \"pan:use_aws_owned_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributeName\": {\n      \"@id\": \"pan:attribute_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elementName\": {\n      \"@id\": \"pan:element_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"pan:reason\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-mq/refs/heads/main/json-ld/amazon-mq-mq-api-context.jsonld
tags:
- AWS
- Broadcasting
- Media Processing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---

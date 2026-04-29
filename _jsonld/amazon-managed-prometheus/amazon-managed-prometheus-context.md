---
class_count: 48
classes:
- AlertManagerDefinitionDescription
- AlertManagerDefinitionStatus
- CreateAlertManagerDefinitionRequest
- CreateAlertManagerDefinitionResponse
- CreateLoggingConfigurationRequest
- CreateLoggingConfigurationResponse
- CreateRuleGroupsNamespaceRequest
- CreateRuleGroupsNamespaceResponse
- CreateWorkspaceRequest
- CreateWorkspaceResponse
- DeleteAlertManagerDefinitionRequest
- DeleteLoggingConfigurationRequest
- DeleteRuleGroupsNamespaceRequest
- DeleteWorkspaceRequest
- DescribeAlertManagerDefinitionRequest
- DescribeAlertManagerDefinitionResponse
- DescribeLoggingConfigurationRequest
- DescribeLoggingConfigurationResponse
- DescribeRuleGroupsNamespaceRequest
- DescribeRuleGroupsNamespaceResponse
- DescribeWorkspaceRequest
- DescribeWorkspaceResponse
- ListRuleGroupsNamespacesRequest
- ListRuleGroupsNamespacesResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ListWorkspacesRequest
- ListWorkspacesResponse
- LoggingConfigurationMetadata
- LoggingConfigurationStatus
- PutAlertManagerDefinitionRequest
- PutAlertManagerDefinitionResponse
- PutRuleGroupsNamespaceRequest
- PutRuleGroupsNamespaceResponse
- RuleGroupsNamespaceDescription
- RuleGroupsNamespaceStatus
- RuleGroupsNamespaceSummary
- TagMap
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
- UpdateLoggingConfigurationRequest
- UpdateLoggingConfigurationResponse
- UpdateWorkspaceAliasRequest
- WorkspaceDescription
- WorkspaceStatus
- WorkspaceSummary
context_file: json-ld/amazon-managed-prometheus-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-prometheus/refs/heads/main/json-ld/amazon-managed-prometheus-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Managed Prometheus from Amazon Managed Service for Prometheus.
layout: jsonld
name: Amazon Managed Prometheus Context
namespaces:
- prefix: amsp
  uri: https://amsp.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: alertManagerDefinition
  type: ''
- container: ''
  name: alias
  type: ''
- container: ''
  name: arn
  type: ''
- container: ''
  name: clientToken
  type: ''
- container: ''
  name: createdAt
  type: ''
- container: ''
  name: data
  type: ''
- container: ''
  name: logGroupArn
  type: ''
- container: ''
  name: loggingConfiguration
  type: ''
- container: ''
  name: modifiedAt
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: nextToken
  type: ''
- container: ''
  name: prometheusEndpoint
  type: ''
- container: ''
  name: ruleGroupsNamespace
  type: ''
- container: ''
  name: ruleGroupsNamespaces
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: statusCode
  type: ''
- container: ''
  name: statusReason
  type: ''
- container: ''
  name: tags
  type: ''
- container: ''
  name: workspace
  type: ''
- container: ''
  name: workspaceId
  type: ''
- container: ''
  name: workspaces
  type: ''
property_count: 21
provider_name: Amazon Managed Service for Prometheus
provider_slug: amazon-managed-prometheus
slug: amazon-managed-prometheus-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amsp\": \"https://amsp.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AlertManagerDefinitionDescription\": \"amsp:AlertManagerDefinitionDescription\",\n    \"AlertManagerDefinitionStatus\": \"amsp:AlertManagerDefinitionStatus\",\n    \"CreateAlertManagerDefinitionRequest\": \"amsp:CreateAlertManagerDefinitionRequest\",\n    \"CreateAlertManagerDefinitionResponse\": \"amsp:CreateAlertManagerDefinitionResponse\",\n    \"CreateLoggingConfigurationRequest\": \"amsp:CreateLoggingConfigurationRequest\",\n    \"CreateLoggingConfigurationResponse\": \"amsp:CreateLoggingConfigurationResponse\",\n    \"CreateRuleGroupsNamespaceRequest\": \"amsp:CreateRuleGroupsNamespaceRequest\",\n    \"CreateRuleGroupsNamespaceResponse\": \"amsp:CreateRuleGroupsNamespaceResponse\",\n    \"CreateWorkspaceRequest\": \"amsp:CreateWorkspaceRequest\",\n    \"CreateWorkspaceResponse\"\
  : \"amsp:CreateWorkspaceResponse\",\n    \"DeleteAlertManagerDefinitionRequest\": \"amsp:DeleteAlertManagerDefinitionRequest\",\n    \"DeleteLoggingConfigurationRequest\": \"amsp:DeleteLoggingConfigurationRequest\",\n    \"DeleteRuleGroupsNamespaceRequest\": \"amsp:DeleteRuleGroupsNamespaceRequest\",\n    \"DeleteWorkspaceRequest\": \"amsp:DeleteWorkspaceRequest\",\n    \"DescribeAlertManagerDefinitionRequest\": \"amsp:DescribeAlertManagerDefinitionRequest\",\n    \"DescribeAlertManagerDefinitionResponse\": \"amsp:DescribeAlertManagerDefinitionResponse\",\n    \"DescribeLoggingConfigurationRequest\": \"amsp:DescribeLoggingConfigurationRequest\",\n    \"DescribeLoggingConfigurationResponse\": \"amsp:DescribeLoggingConfigurationResponse\",\n    \"DescribeRuleGroupsNamespaceRequest\": \"amsp:DescribeRuleGroupsNamespaceRequest\",\n    \"DescribeRuleGroupsNamespaceResponse\": \"amsp:DescribeRuleGroupsNamespaceResponse\",\n    \"DescribeWorkspaceRequest\": \"amsp:DescribeWorkspaceRequest\",\n\
  \    \"DescribeWorkspaceResponse\": \"amsp:DescribeWorkspaceResponse\",\n    \"ListRuleGroupsNamespacesRequest\": \"amsp:ListRuleGroupsNamespacesRequest\",\n    \"ListRuleGroupsNamespacesResponse\": \"amsp:ListRuleGroupsNamespacesResponse\",\n    \"ListTagsForResourceRequest\": \"amsp:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amsp:ListTagsForResourceResponse\",\n    \"ListWorkspacesRequest\": \"amsp:ListWorkspacesRequest\",\n    \"ListWorkspacesResponse\": \"amsp:ListWorkspacesResponse\",\n    \"LoggingConfigurationMetadata\": \"amsp:LoggingConfigurationMetadata\",\n    \"LoggingConfigurationStatus\": \"amsp:LoggingConfigurationStatus\",\n    \"PutAlertManagerDefinitionRequest\": \"amsp:PutAlertManagerDefinitionRequest\",\n    \"PutAlertManagerDefinitionResponse\": \"amsp:PutAlertManagerDefinitionResponse\",\n    \"PutRuleGroupsNamespaceRequest\": \"amsp:PutRuleGroupsNamespaceRequest\",\n    \"PutRuleGroupsNamespaceResponse\": \"amsp:PutRuleGroupsNamespaceResponse\"\
  ,\n    \"RuleGroupsNamespaceDescription\": \"amsp:RuleGroupsNamespaceDescription\",\n    \"RuleGroupsNamespaceStatus\": \"amsp:RuleGroupsNamespaceStatus\",\n    \"RuleGroupsNamespaceSummary\": \"amsp:RuleGroupsNamespaceSummary\",\n    \"TagMap\": \"amsp:TagMap\",\n    \"TagResourceRequest\": \"amsp:TagResourceRequest\",\n    \"TagResourceResponse\": \"amsp:TagResourceResponse\",\n    \"UntagResourceRequest\": \"amsp:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amsp:UntagResourceResponse\",\n    \"UpdateLoggingConfigurationRequest\": \"amsp:UpdateLoggingConfigurationRequest\",\n    \"UpdateLoggingConfigurationResponse\": \"amsp:UpdateLoggingConfigurationResponse\",\n    \"UpdateWorkspaceAliasRequest\": \"amsp:UpdateWorkspaceAliasRequest\",\n    \"WorkspaceDescription\": \"amsp:WorkspaceDescription\",\n    \"WorkspaceStatus\": \"amsp:WorkspaceStatus\",\n    \"WorkspaceSummary\": \"amsp:WorkspaceSummary\",\n    \"alertManagerDefinition\": {\n      \"@id\": \"amsp:alertManagerDefinition\"\
  \n    },\n    \"alias\": {\n      \"@id\": \"amsp:alias\"\n    },\n    \"arn\": {\n      \"@id\": \"amsp:arn\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amsp:clientToken\"\n    },\n    \"createdAt\": {\n      \"@id\": \"amsp:createdAt\"\n    },\n    \"data\": {\n      \"@id\": \"amsp:data\"\n    },\n    \"logGroupArn\": {\n      \"@id\": \"amsp:logGroupArn\"\n    },\n    \"loggingConfiguration\": {\n      \"@id\": \"amsp:loggingConfiguration\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"amsp:modifiedAt\"\n    },\n    \"name\": {\n      \"@id\": \"amsp:name\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amsp:nextToken\"\n    },\n    \"prometheusEndpoint\": {\n      \"@id\": \"amsp:prometheusEndpoint\"\n    },\n    \"ruleGroupsNamespace\": {\n      \"@id\": \"amsp:ruleGroupsNamespace\"\n    },\n    \"ruleGroupsNamespaces\": {\n      \"@id\": \"amsp:ruleGroupsNamespaces\"\n    },\n    \"status\": {\n      \"@id\": \"amsp:status\"\n    },\n    \"statusCode\": {\n      \"@id\"\
  : \"amsp:statusCode\"\n    },\n    \"statusReason\": {\n      \"@id\": \"amsp:statusReason\"\n    },\n    \"tags\": {\n      \"@id\": \"amsp:tags\"\n    },\n    \"workspace\": {\n      \"@id\": \"amsp:workspace\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"amsp:workspaceId\"\n    },\n    \"workspaces\": {\n      \"@id\": \"amsp:workspaces\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-prometheus/refs/heads/main/json-ld/amazon-managed-prometheus-context.jsonld
tags:
- AWS
- Containers
- Monitoring
- Observability
- Prometheus
- JSON-LD
- Linked Data
- Semantic Web
---

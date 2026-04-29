---
api_specs:
- filename: amazon-managed-grafana-openapi-original.yaml
  format: yaml
  label: Amazon Managed Grafana API
  slug: amazon-managed-grafana-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-grafana/refs/heads/main/openapi/amazon-managed-grafana-openapi-original.yaml
class_count: 55
classes:
- AssertionAttributes
- AssociateLicenseRequest
- AssociateLicenseResponse
- AuthenticationDescription
- AuthenticationSummary
- AwsSsoAuthentication
- CreateWorkspaceApiKeyRequest
- CreateWorkspaceApiKeyResponse
- CreateWorkspaceRequest
- CreateWorkspaceResponse
- DeleteWorkspaceApiKeyRequest
- DeleteWorkspaceApiKeyResponse
- DeleteWorkspaceRequest
- DeleteWorkspaceResponse
- DescribeWorkspaceAuthenticationRequest
- DescribeWorkspaceAuthenticationResponse
- DescribeWorkspaceConfigurationRequest
- DescribeWorkspaceConfigurationResponse
- DescribeWorkspaceRequest
- DescribeWorkspaceResponse
- DisassociateLicenseRequest
- DisassociateLicenseResponse
- IdpMetadata
- ListPermissionsRequest
- ListPermissionsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ListVersionsRequest
- ListVersionsResponse
- ListWorkspacesRequest
- ListWorkspacesResponse
- NetworkAccessConfiguration
- PermissionEntry
- RoleValues
- SamlAuthentication
- SamlConfiguration
- TagMap
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
- UpdateError
- UpdateInstruction
- UpdatePermissionsRequest
- UpdatePermissionsResponse
- UpdateWorkspaceAuthenticationRequest
- UpdateWorkspaceAuthenticationResponse
- UpdateWorkspaceConfigurationRequest
- UpdateWorkspaceConfigurationResponse
- UpdateWorkspaceRequest
- UpdateWorkspaceResponse
- User
- VpcConfiguration
- WorkspaceDescription
- WorkspaceSummary
context_file: json-ld/amazon-managed-grafana-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-grafana/refs/heads/main/json-ld/amazon-managed-grafana-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Managed Grafana from Amazon Managed Grafana.
layout: jsonld
name: Amazon Managed Grafana Context
namespaces:
- prefix: amgr
  uri: https://amgr.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accountAccessType
  type: ''
- container: ''
  name: action
  type: ''
- container: ''
  name: admin
  type: ''
- container: ''
  name: allowedOrganizations
  type: ''
- container: ''
  name: assertionAttributes
  type: ''
- container: ''
  name: authentication
  type: ''
- container: ''
  name: authenticationProviders
  type: ''
- container: ''
  name: awsSso
  type: ''
- container: ''
  name: causedBy
  type: ''
- container: ''
  name: clientToken
  type: ''
- container: ''
  name: code
  type: ''
- container: ''
  name: configuration
  type: ''
- container: ''
  name: created
  type: ''
- container: ''
  name: dataSources
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: editor
  type: ''
- container: ''
  name: email
  type: ''
- container: ''
  name: endpoint
  type: ''
- container: ''
  name: errors
  type: ''
- container: ''
  name: freeTrialConsumed
  type: ''
- container: ''
  name: freeTrialExpiration
  type: ''
- container: ''
  name: grafanaVersion
  type: ''
- container: ''
  name: grafanaVersions
  type: ''
- container: ''
  name: groups
  type: ''
- container: ''
  name: id
  type: ''
- container: ''
  name: idpMetadata
  type: ''
- container: ''
  name: key
  type: ''
- container: ''
  name: keyName
  type: ''
- container: ''
  name: keyRole
  type: ''
- container: ''
  name: licenseExpiration
  type: ''
- container: ''
  name: licenseType
  type: ''
- container: ''
  name: login
  type: ''
- container: ''
  name: loginValidityDuration
  type: ''
- container: ''
  name: message
  type: ''
- container: ''
  name: modified
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: networkAccessControl
  type: ''
- container: ''
  name: nextToken
  type: ''
- container: ''
  name: notificationDestinations
  type: ''
- container: ''
  name: org
  type: ''
- container: ''
  name: organizationRoleName
  type: ''
- container: ''
  name: organizationalUnits
  type: ''
- container: ''
  name: permissionType
  type: ''
- container: ''
  name: permissions
  type: ''
- container: ''
  name: prefixListIds
  type: ''
- container: ''
  name: providers
  type: ''
- container: ''
  name: removeNetworkAccessConfiguration
  type: ''
- container: ''
  name: removeVpcConfiguration
  type: ''
- container: ''
  name: role
  type: ''
- container: ''
  name: roleValues
  type: ''
- container: ''
  name: saml
  type: ''
- container: ''
  name: samlConfiguration
  type: ''
- container: ''
  name: samlConfigurationStatus
  type: ''
- container: ''
  name: secondsToLive
  type: ''
- container: ''
  name: securityGroupIds
  type: ''
- container: ''
  name: ssoClientId
  type: ''
- container: ''
  name: stackSetName
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: subnetIds
  type: ''
- container: ''
  name: tags
  type: ''
- container: ''
  name: type
  type: ''
- container: ''
  name: updateInstructionBatch
  type: ''
- container: ''
  name: url
  type: ''
- container: ''
  name: user
  type: ''
- container: ''
  name: users
  type: ''
- container: ''
  name: vpcConfiguration
  type: ''
- container: ''
  name: vpceIds
  type: ''
- container: ''
  name: workspace
  type: ''
- container: ''
  name: workspaceDataSources
  type: ''
- container: ''
  name: workspaceDescription
  type: ''
- container: ''
  name: workspaceId
  type: ''
- container: ''
  name: workspaceName
  type: ''
- container: ''
  name: workspaceNotificationDestinations
  type: ''
- container: ''
  name: workspaceOrganizationalUnits
  type: ''
- container: ''
  name: workspaceRoleArn
  type: ''
- container: ''
  name: workspaces
  type: ''
- container: ''
  name: xml
  type: ''
property_count: 77
provider_name: Amazon Managed Grafana
provider_slug: amazon-managed-grafana
slug: amazon-managed-grafana-context
source_filename: amazon-managed-grafana-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amgr\": \"https://amgr.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssertionAttributes\": \"amgr:AssertionAttributes\",\n    \"AssociateLicenseRequest\": \"amgr:AssociateLicenseRequest\",\n    \"AssociateLicenseResponse\": \"amgr:AssociateLicenseResponse\",\n    \"AuthenticationDescription\": \"amgr:AuthenticationDescription\",\n    \"AuthenticationSummary\": \"amgr:AuthenticationSummary\",\n    \"AwsSsoAuthentication\": \"amgr:AwsSsoAuthentication\",\n    \"CreateWorkspaceApiKeyRequest\": \"amgr:CreateWorkspaceApiKeyRequest\",\n    \"CreateWorkspaceApiKeyResponse\": \"amgr:CreateWorkspaceApiKeyResponse\",\n    \"CreateWorkspaceRequest\": \"amgr:CreateWorkspaceRequest\",\n    \"CreateWorkspaceResponse\": \"amgr:CreateWorkspaceResponse\",\n    \"DeleteWorkspaceApiKeyRequest\": \"amgr:DeleteWorkspaceApiKeyRequest\",\n    \"DeleteWorkspaceApiKeyResponse\"\
  : \"amgr:DeleteWorkspaceApiKeyResponse\",\n    \"DeleteWorkspaceRequest\": \"amgr:DeleteWorkspaceRequest\",\n    \"DeleteWorkspaceResponse\": \"amgr:DeleteWorkspaceResponse\",\n    \"DescribeWorkspaceAuthenticationRequest\": \"amgr:DescribeWorkspaceAuthenticationRequest\",\n    \"DescribeWorkspaceAuthenticationResponse\": \"amgr:DescribeWorkspaceAuthenticationResponse\",\n    \"DescribeWorkspaceConfigurationRequest\": \"amgr:DescribeWorkspaceConfigurationRequest\",\n    \"DescribeWorkspaceConfigurationResponse\": \"amgr:DescribeWorkspaceConfigurationResponse\",\n    \"DescribeWorkspaceRequest\": \"amgr:DescribeWorkspaceRequest\",\n    \"DescribeWorkspaceResponse\": \"amgr:DescribeWorkspaceResponse\",\n    \"DisassociateLicenseRequest\": \"amgr:DisassociateLicenseRequest\",\n    \"DisassociateLicenseResponse\": \"amgr:DisassociateLicenseResponse\",\n    \"IdpMetadata\": \"amgr:IdpMetadata\",\n    \"ListPermissionsRequest\": \"amgr:ListPermissionsRequest\",\n    \"ListPermissionsResponse\"\
  : \"amgr:ListPermissionsResponse\",\n    \"ListTagsForResourceRequest\": \"amgr:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amgr:ListTagsForResourceResponse\",\n    \"ListVersionsRequest\": \"amgr:ListVersionsRequest\",\n    \"ListVersionsResponse\": \"amgr:ListVersionsResponse\",\n    \"ListWorkspacesRequest\": \"amgr:ListWorkspacesRequest\",\n    \"ListWorkspacesResponse\": \"amgr:ListWorkspacesResponse\",\n    \"NetworkAccessConfiguration\": \"amgr:NetworkAccessConfiguration\",\n    \"PermissionEntry\": \"amgr:PermissionEntry\",\n    \"RoleValues\": \"amgr:RoleValues\",\n    \"SamlAuthentication\": \"amgr:SamlAuthentication\",\n    \"SamlConfiguration\": \"amgr:SamlConfiguration\",\n    \"TagMap\": \"amgr:TagMap\",\n    \"TagResourceRequest\": \"amgr:TagResourceRequest\",\n    \"TagResourceResponse\": \"amgr:TagResourceResponse\",\n    \"UntagResourceRequest\": \"amgr:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amgr:UntagResourceResponse\",\n\
  \    \"UpdateError\": \"amgr:UpdateError\",\n    \"UpdateInstruction\": \"amgr:UpdateInstruction\",\n    \"UpdatePermissionsRequest\": \"amgr:UpdatePermissionsRequest\",\n    \"UpdatePermissionsResponse\": \"amgr:UpdatePermissionsResponse\",\n    \"UpdateWorkspaceAuthenticationRequest\": \"amgr:UpdateWorkspaceAuthenticationRequest\",\n    \"UpdateWorkspaceAuthenticationResponse\": \"amgr:UpdateWorkspaceAuthenticationResponse\",\n    \"UpdateWorkspaceConfigurationRequest\": \"amgr:UpdateWorkspaceConfigurationRequest\",\n    \"UpdateWorkspaceConfigurationResponse\": \"amgr:UpdateWorkspaceConfigurationResponse\",\n    \"UpdateWorkspaceRequest\": \"amgr:UpdateWorkspaceRequest\",\n    \"UpdateWorkspaceResponse\": \"amgr:UpdateWorkspaceResponse\",\n    \"User\": \"amgr:User\",\n    \"VpcConfiguration\": \"amgr:VpcConfiguration\",\n    \"WorkspaceDescription\": \"amgr:WorkspaceDescription\",\n    \"WorkspaceSummary\": \"amgr:WorkspaceSummary\",\n    \"accountAccessType\": {\n      \"@id\": \"\
  amgr:accountAccessType\"\n    },\n    \"action\": {\n      \"@id\": \"amgr:action\"\n    },\n    \"admin\": {\n      \"@id\": \"amgr:admin\"\n    },\n    \"allowedOrganizations\": {\n      \"@id\": \"amgr:allowedOrganizations\"\n    },\n    \"assertionAttributes\": {\n      \"@id\": \"amgr:assertionAttributes\"\n    },\n    \"authentication\": {\n      \"@id\": \"amgr:authentication\"\n    },\n    \"authenticationProviders\": {\n      \"@id\": \"amgr:authenticationProviders\"\n    },\n    \"awsSso\": {\n      \"@id\": \"amgr:awsSso\"\n    },\n    \"causedBy\": {\n      \"@id\": \"amgr:causedBy\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amgr:clientToken\"\n    },\n    \"code\": {\n      \"@id\": \"amgr:code\"\n    },\n    \"configuration\": {\n      \"@id\": \"amgr:configuration\"\n    },\n    \"created\": {\n      \"@id\": \"amgr:created\"\n    },\n    \"dataSources\": {\n      \"@id\": \"amgr:dataSources\"\n    },\n    \"description\": {\n      \"@id\": \"amgr:description\"\n\
  \    },\n    \"editor\": {\n      \"@id\": \"amgr:editor\"\n    },\n    \"email\": {\n      \"@id\": \"amgr:email\"\n    },\n    \"endpoint\": {\n      \"@id\": \"amgr:endpoint\"\n    },\n    \"errors\": {\n      \"@id\": \"amgr:errors\"\n    },\n    \"freeTrialConsumed\": {\n      \"@id\": \"amgr:freeTrialConsumed\"\n    },\n    \"freeTrialExpiration\": {\n      \"@id\": \"amgr:freeTrialExpiration\"\n    },\n    \"grafanaVersion\": {\n      \"@id\": \"amgr:grafanaVersion\"\n    },\n    \"grafanaVersions\": {\n      \"@id\": \"amgr:grafanaVersions\"\n    },\n    \"groups\": {\n      \"@id\": \"amgr:groups\"\n    },\n    \"id\": {\n      \"@id\": \"amgr:id\"\n    },\n    \"idpMetadata\": {\n      \"@id\": \"amgr:idpMetadata\"\n    },\n    \"key\": {\n      \"@id\": \"amgr:key\"\n    },\n    \"keyName\": {\n      \"@id\": \"amgr:keyName\"\n    },\n    \"keyRole\": {\n      \"@id\": \"amgr:keyRole\"\n    },\n    \"licenseExpiration\": {\n      \"@id\": \"amgr:licenseExpiration\"\n    },\n\
  \    \"licenseType\": {\n      \"@id\": \"amgr:licenseType\"\n    },\n    \"login\": {\n      \"@id\": \"amgr:login\"\n    },\n    \"loginValidityDuration\": {\n      \"@id\": \"amgr:loginValidityDuration\"\n    },\n    \"message\": {\n      \"@id\": \"amgr:message\"\n    },\n    \"modified\": {\n      \"@id\": \"amgr:modified\"\n    },\n    \"name\": {\n      \"@id\": \"amgr:name\"\n    },\n    \"networkAccessControl\": {\n      \"@id\": \"amgr:networkAccessControl\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amgr:nextToken\"\n    },\n    \"notificationDestinations\": {\n      \"@id\": \"amgr:notificationDestinations\"\n    },\n    \"org\": {\n      \"@id\": \"amgr:org\"\n    },\n    \"organizationRoleName\": {\n      \"@id\": \"amgr:organizationRoleName\"\n    },\n    \"organizationalUnits\": {\n      \"@id\": \"amgr:organizationalUnits\"\n    },\n    \"permissionType\": {\n      \"@id\": \"amgr:permissionType\"\n    },\n    \"permissions\": {\n      \"@id\": \"amgr:permissions\"\
  \n    },\n    \"prefixListIds\": {\n      \"@id\": \"amgr:prefixListIds\"\n    },\n    \"providers\": {\n      \"@id\": \"amgr:providers\"\n    },\n    \"removeNetworkAccessConfiguration\": {\n      \"@id\": \"amgr:removeNetworkAccessConfiguration\"\n    },\n    \"removeVpcConfiguration\": {\n      \"@id\": \"amgr:removeVpcConfiguration\"\n    },\n    \"role\": {\n      \"@id\": \"amgr:role\"\n    },\n    \"roleValues\": {\n      \"@id\": \"amgr:roleValues\"\n    },\n    \"saml\": {\n      \"@id\": \"amgr:saml\"\n    },\n    \"samlConfiguration\": {\n      \"@id\": \"amgr:samlConfiguration\"\n    },\n    \"samlConfigurationStatus\": {\n      \"@id\": \"amgr:samlConfigurationStatus\"\n    },\n    \"secondsToLive\": {\n      \"@id\": \"amgr:secondsToLive\"\n    },\n    \"securityGroupIds\": {\n      \"@id\": \"amgr:securityGroupIds\"\n    },\n    \"ssoClientId\": {\n      \"@id\": \"amgr:ssoClientId\"\n    },\n    \"stackSetName\": {\n      \"@id\": \"amgr:stackSetName\"\n    },\n    \"\
  status\": {\n      \"@id\": \"amgr:status\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"amgr:subnetIds\"\n    },\n    \"tags\": {\n      \"@id\": \"amgr:tags\"\n    },\n    \"type\": {\n      \"@id\": \"amgr:type\"\n    },\n    \"updateInstructionBatch\": {\n      \"@id\": \"amgr:updateInstructionBatch\"\n    },\n    \"url\": {\n      \"@id\": \"amgr:url\"\n    },\n    \"user\": {\n      \"@id\": \"amgr:user\"\n    },\n    \"users\": {\n      \"@id\": \"amgr:users\"\n    },\n    \"vpcConfiguration\": {\n      \"@id\": \"amgr:vpcConfiguration\"\n    },\n    \"vpceIds\": {\n      \"@id\": \"amgr:vpceIds\"\n    },\n    \"workspace\": {\n      \"@id\": \"amgr:workspace\"\n    },\n    \"workspaceDataSources\": {\n      \"@id\": \"amgr:workspaceDataSources\"\n    },\n    \"workspaceDescription\": {\n      \"@id\": \"amgr:workspaceDescription\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"amgr:workspaceId\"\n    },\n    \"workspaceName\": {\n      \"@id\": \"amgr:workspaceName\"\n  \
  \  },\n    \"workspaceNotificationDestinations\": {\n      \"@id\": \"amgr:workspaceNotificationDestinations\"\n    },\n    \"workspaceOrganizationalUnits\": {\n      \"@id\": \"amgr:workspaceOrganizationalUnits\"\n    },\n    \"workspaceRoleArn\": {\n      \"@id\": \"amgr:workspaceRoleArn\"\n    },\n    \"workspaces\": {\n      \"@id\": \"amgr:workspaces\"\n    },\n    \"xml\": {\n      \"@id\": \"amgr:xml\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-grafana/refs/heads/main/json-ld/amazon-managed-grafana-context.jsonld
tags:
- AWS
- Dashboards
- Monitoring
- Observability
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---

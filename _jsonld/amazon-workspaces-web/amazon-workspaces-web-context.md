---
api_specs:
- filename: amazon-workspaces-web-openapi-original.yaml
  format: yaml
  label: Amazon WorkSpaces Web API
  slug: amazon-workspaces-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/openapi/amazon-workspaces-web-openapi-original.yaml
class_count: 139
classes:
- AssociateBrowserSettingsResponse
- AssociateIpAccessSettingsResponse
- AssociateNetworkSettingsResponse
- AssociateTrustStoreResponse
- AssociateUserAccessLoggingSettingsResponse
- AssociateUserSettingsResponse
- CreateBrowserSettingsResponse
- Tag
- CreateIdentityProviderResponse
- CreateIpAccessSettingsResponse
- IpRule
- description
- CreateNetworkSettingsResponse
- CreatePortalResponse
- CreateTrustStoreResponse
- CreateUserAccessLoggingSettingsResponse
- CreateUserSettingsResponse
- DeleteBrowserSettingsResponse
- DeleteIdentityProviderResponse
- DeleteIpAccessSettingsResponse
- DeleteNetworkSettingsResponse
- DeletePortalResponse
- DeleteTrustStoreResponse
- DeleteUserAccessLoggingSettingsResponse
- DeleteUserSettingsResponse
- DisassociateBrowserSettingsResponse
- DisassociateIpAccessSettingsResponse
- DisassociateNetworkSettingsResponse
- DisassociateTrustStoreResponse
- DisassociateUserAccessLoggingSettingsResponse
- DisassociateUserSettingsResponse
- GetBrowserSettingsResponse
- GetIdentityProviderResponse
- GetIpAccessSettingsResponse
- GetNetworkSettingsResponse
- GetPortalResponse
- GetPortalServiceProviderMetadataResponse
- GetTrustStoreResponse
- GetTrustStoreCertificateResponse
- GetUserAccessLoggingSettingsResponse
- GetUserSettingsResponse
- ListBrowserSettingsResponse
- ListIdentityProvidersResponse
- ListIpAccessSettingsResponse
- ListNetworkSettingsResponse
- ListPortalsResponse
- ListTagsForResourceResponse
- ListTrustStoreCertificatesResponse
- ListTrustStoresResponse
- ListUserAccessLoggingSettingsResponse
- ListUserSettingsResponse
- TagResourceResponse
- UntagResourceResponse
- UpdateBrowserSettingsResponse
- UpdateIdentityProviderResponse
- UpdateIpAccessSettingsResponse
- UpdateNetworkSettingsResponse
- UpdatePortalResponse
- UpdateTrustStoreResponse
- UpdateUserAccessLoggingSettingsResponse
- UpdateUserSettingsResponse
- AssociateBrowserSettingsRequest
- AssociateIpAccessSettingsRequest
- AssociateNetworkSettingsRequest
- AssociateTrustStoreRequest
- AssociateUserAccessLoggingSettingsRequest
- AssociateUserSettingsRequest
- BrowserSettings
- BrowserSettingsSummary
- Certificate
- CertificateSummary
- EncryptionContextMap
- CreateBrowserSettingsRequest
- IdentityProviderDetails
- CreateIdentityProviderRequest
- CreateIpAccessSettingsRequest
- CreateNetworkSettingsRequest
- CreatePortalRequest
- CreateTrustStoreRequest
- CreateUserAccessLoggingSettingsRequest
- CreateUserSettingsRequest
- DeleteBrowserSettingsRequest
- DeleteIdentityProviderRequest
- DeleteIpAccessSettingsRequest
- DeleteNetworkSettingsRequest
- DeletePortalRequest
- DeleteTrustStoreRequest
- DeleteUserAccessLoggingSettingsRequest
- DeleteUserSettingsRequest
- DisassociateBrowserSettingsRequest
- DisassociateIpAccessSettingsRequest
- DisassociateNetworkSettingsRequest
- DisassociateTrustStoreRequest
- DisassociateUserAccessLoggingSettingsRequest
- DisassociateUserSettingsRequest
- GetBrowserSettingsRequest
- GetIdentityProviderRequest
- IdentityProvider
- GetIpAccessSettingsRequest
- IpAccessSettings
- GetNetworkSettingsRequest
- NetworkSettings
- GetPortalRequest
- Portal
- GetPortalServiceProviderMetadataRequest
- GetTrustStoreCertificateRequest
- GetTrustStoreRequest
- TrustStore
- GetUserAccessLoggingSettingsRequest
- UserAccessLoggingSettings
- GetUserSettingsRequest
- UserSettings
- IdentityProviderSummary
- IpAccessSettingsSummary
- ListBrowserSettingsRequest
- ListIdentityProvidersRequest
- ListIpAccessSettingsRequest
- ListNetworkSettingsRequest
- ListPortalsRequest
- ListTagsForResourceRequest
- ListTrustStoreCertificatesRequest
- ListTrustStoresRequest
- ListUserAccessLoggingSettingsRequest
- ListUserSettingsRequest
- NetworkSettingsSummary
- PortalSummary
- TagResourceRequest
- TrustStoreSummary
- UntagResourceRequest
- UpdateBrowserSettingsRequest
- UpdateIdentityProviderRequest
- UpdateIpAccessSettingsRequest
- UpdateNetworkSettingsRequest
- UpdatePortalRequest
- UpdateTrustStoreRequest
- UpdateUserAccessLoggingSettingsRequest
- UpdateUserSettingsRequest
- UserAccessLoggingSettingsSummary
- UserSettingsSummary
context_file: json-ld/amazon-workspaces-web-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/json-ld/amazon-workspaces-web-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Workspaces Web from Amazon WorkSpaces Web.
layout: jsonld
name: Amazon Workspaces Web Context
namespaces:
- prefix: amz
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: browserSettingsArn
  type: string
- container: ''
  name: portalArn
  type: string
- container: ''
  name: ipAccessSettingsArn
  type: string
- container: ''
  name: networkSettingsArn
  type: string
- container: ''
  name: trustStoreArn
  type: string
- container: ''
  name: userAccessLoggingSettingsArn
  type: string
- container: ''
  name: userSettingsArn
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: identityProviderArn
  type: string
- container: ''
  name: ipRange
  type: string
- container: ''
  name: portalEndpoint
  type: string
- container: ''
  name: browserSettings
  type: string
- container: ''
  name: identityProvider
  type: string
- container: ''
  name: ipAccessSettings
  type: string
- container: ''
  name: networkSettings
  type: string
- container: ''
  name: portal
  type: string
- container: ''
  name: serviceProviderSamlMetadata
  type: string
- container: ''
  name: trustStore
  type: string
- container: ''
  name: certificate
  type: string
- container: ''
  name: userAccessLoggingSettings
  type: string
- container: ''
  name: userSettings
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: identityProviders
  type: string
- container: ''
  name: portals
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: certificateList
  type: string
- container: ''
  name: trustStores
  type: string
- container: ''
  name: associatedPortalArns
  type: string
- container: ''
  name: browserPolicy
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: issuer
  type: string
- container: ''
  name: notValidAfter
  type: string
- container: ''
  name: notValidBefore
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: thumbprint
  type: string
- container: ''
  name: additionalEncryptionContext
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: customerManagedKey
  type: string
- container: ''
  name: identityProviderDetails
  type: string
- container: ''
  name: identityProviderName
  type: string
- container: ''
  name: identityProviderType
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: ipRules
  type: string
- container: ''
  name: securityGroupIds
  type: string
- container: ''
  name: subnetIds
  type: string
- container: ''
  name: vpcId
  type: string
- container: ''
  name: authenticationType
  type: string
- container: ''
  name: kinesisStreamArn
  type: string
- container: ''
  name: copyAllowed
  type: string
- container: ''
  name: disconnectTimeoutInMinutes
  type: string
- container: ''
  name: downloadAllowed
  type: string
- container: ''
  name: idleDisconnectTimeoutInMinutes
  type: string
- container: ''
  name: pasteAllowed
  type: string
- container: ''
  name: printAllowed
  type: string
- container: ''
  name: uploadAllowed
  type: string
- container: ''
  name: creationDate
  type: string
- container: ''
  name: browserType
  type: string
- container: ''
  name: portalStatus
  type: string
- container: ''
  name: rendererType
  type: string
- container: ''
  name: statusReason
  type: string
- container: ''
  name: certificatesToAdd
  type: string
- container: ''
  name: certificatesToDelete
  type: string
property_count: 63
provider_name: Amazon WorkSpaces Web
provider_slug: amazon-workspaces-web
slug: amazon-workspaces-web-context
source_filename: amazon-workspaces-web-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssociateBrowserSettingsResponse\": \"amz:AssociateBrowserSettingsResponse\",\n    \"browserSettingsArn\": {\n      \"@id\": \"amz:browserSettingsArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalArn\": {\n      \"@id\": \"amz:portalArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateIpAccessSettingsResponse\": \"amz:AssociateIpAccessSettingsResponse\",\n    \"ipAccessSettingsArn\": {\n      \"@id\": \"amz:ipAccessSettingsArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateNetworkSettingsResponse\": \"amz:AssociateNetworkSettingsResponse\",\n    \"networkSettingsArn\": {\n      \"@id\": \"amz:networkSettingsArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateTrustStoreResponse\": \"amz:AssociateTrustStoreResponse\"\
  ,\n    \"trustStoreArn\": {\n      \"@id\": \"amz:trustStoreArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateUserAccessLoggingSettingsResponse\": \"amz:AssociateUserAccessLoggingSettingsResponse\",\n    \"userAccessLoggingSettingsArn\": {\n      \"@id\": \"amz:userAccessLoggingSettingsArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateUserSettingsResponse\": \"amz:AssociateUserSettingsResponse\",\n    \"userSettingsArn\": {\n      \"@id\": \"amz:userSettingsArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateBrowserSettingsResponse\": \"amz:CreateBrowserSettingsResponse\",\n    \"Tag\": \"amz:Tag\",\n    \"Key\": {\n      \"@id\": \"amz:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"amz:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateIdentityProviderResponse\": \"amz:CreateIdentityProviderResponse\",\n    \"identityProviderArn\": {\n      \"@id\": \"amz:identityProviderArn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"CreateIpAccessSettingsResponse\": \"amz:CreateIpAccessSettingsResponse\",\n    \"IpRule\": \"amz:IpRule\",\n    \"description\": \"schema:description\",\n    \"ipRange\": {\n      \"@id\": \"amz:ipRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateNetworkSettingsResponse\": \"amz:CreateNetworkSettingsResponse\",\n    \"CreatePortalResponse\": \"amz:CreatePortalResponse\",\n    \"portalEndpoint\": {\n      \"@id\": \"amz:portalEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTrustStoreResponse\": \"amz:CreateTrustStoreResponse\",\n    \"CreateUserAccessLoggingSettingsResponse\": \"amz:CreateUserAccessLoggingSettingsResponse\",\n    \"CreateUserSettingsResponse\": \"amz:CreateUserSettingsResponse\",\n    \"DeleteBrowserSettingsResponse\": \"amz:DeleteBrowserSettingsResponse\",\n    \"DeleteIdentityProviderResponse\": \"amz:DeleteIdentityProviderResponse\",\n    \"DeleteIpAccessSettingsResponse\": \"amz:DeleteIpAccessSettingsResponse\",\n    \"\
  DeleteNetworkSettingsResponse\": \"amz:DeleteNetworkSettingsResponse\",\n    \"DeletePortalResponse\": \"amz:DeletePortalResponse\",\n    \"DeleteTrustStoreResponse\": \"amz:DeleteTrustStoreResponse\",\n    \"DeleteUserAccessLoggingSettingsResponse\": \"amz:DeleteUserAccessLoggingSettingsResponse\",\n    \"DeleteUserSettingsResponse\": \"amz:DeleteUserSettingsResponse\",\n    \"DisassociateBrowserSettingsResponse\": \"amz:DisassociateBrowserSettingsResponse\",\n    \"DisassociateIpAccessSettingsResponse\": \"amz:DisassociateIpAccessSettingsResponse\",\n    \"DisassociateNetworkSettingsResponse\": \"amz:DisassociateNetworkSettingsResponse\",\n    \"DisassociateTrustStoreResponse\": \"amz:DisassociateTrustStoreResponse\",\n    \"DisassociateUserAccessLoggingSettingsResponse\": \"amz:DisassociateUserAccessLoggingSettingsResponse\",\n    \"DisassociateUserSettingsResponse\": \"amz:DisassociateUserSettingsResponse\",\n    \"GetBrowserSettingsResponse\": \"amz:GetBrowserSettingsResponse\",\n\
  \    \"browserSettings\": {\n      \"@id\": \"amz:browserSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetIdentityProviderResponse\": \"amz:GetIdentityProviderResponse\",\n    \"identityProvider\": {\n      \"@id\": \"amz:identityProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetIpAccessSettingsResponse\": \"amz:GetIpAccessSettingsResponse\",\n    \"ipAccessSettings\": {\n      \"@id\": \"amz:ipAccessSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetNetworkSettingsResponse\": \"amz:GetNetworkSettingsResponse\",\n    \"networkSettings\": {\n      \"@id\": \"amz:networkSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetPortalResponse\": \"amz:GetPortalResponse\",\n    \"portal\": {\n      \"@id\": \"amz:portal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetPortalServiceProviderMetadataResponse\": \"amz:GetPortalServiceProviderMetadataResponse\",\n    \"serviceProviderSamlMetadata\": {\n      \"@id\": \"amz:serviceProviderSamlMetadata\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"GetTrustStoreResponse\": \"amz:GetTrustStoreResponse\",\n    \"trustStore\": {\n      \"@id\": \"amz:trustStore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetTrustStoreCertificateResponse\": \"amz:GetTrustStoreCertificateResponse\",\n    \"certificate\": {\n      \"@id\": \"amz:certificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetUserAccessLoggingSettingsResponse\": \"amz:GetUserAccessLoggingSettingsResponse\",\n    \"userAccessLoggingSettings\": {\n      \"@id\": \"amz:userAccessLoggingSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetUserSettingsResponse\": \"amz:GetUserSettingsResponse\",\n    \"userSettings\": {\n      \"@id\": \"amz:userSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListBrowserSettingsResponse\": \"amz:ListBrowserSettingsResponse\",\n    \"nextToken\": {\n      \"@id\": \"amz:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListIdentityProvidersResponse\":\
  \ \"amz:ListIdentityProvidersResponse\",\n    \"identityProviders\": {\n      \"@id\": \"amz:identityProviders\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListIpAccessSettingsResponse\": \"amz:ListIpAccessSettingsResponse\",\n    \"ListNetworkSettingsResponse\": \"amz:ListNetworkSettingsResponse\",\n    \"ListPortalsResponse\": \"amz:ListPortalsResponse\",\n    \"portals\": {\n      \"@id\": \"amz:portals\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceResponse\": \"amz:ListTagsForResourceResponse\",\n    \"tags\": {\n      \"@id\": \"amz:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTrustStoreCertificatesResponse\": \"amz:ListTrustStoreCertificatesResponse\",\n    \"certificateList\": {\n      \"@id\": \"amz:certificateList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTrustStoresResponse\": \"amz:ListTrustStoresResponse\",\n    \"trustStores\": {\n      \"@id\": \"amz:trustStores\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListUserAccessLoggingSettingsResponse\"\
  : \"amz:ListUserAccessLoggingSettingsResponse\",\n    \"ListUserSettingsResponse\": \"amz:ListUserSettingsResponse\",\n    \"TagResourceResponse\": \"amz:TagResourceResponse\",\n    \"UntagResourceResponse\": \"amz:UntagResourceResponse\",\n    \"UpdateBrowserSettingsResponse\": \"amz:UpdateBrowserSettingsResponse\",\n    \"UpdateIdentityProviderResponse\": \"amz:UpdateIdentityProviderResponse\",\n    \"UpdateIpAccessSettingsResponse\": \"amz:UpdateIpAccessSettingsResponse\",\n    \"UpdateNetworkSettingsResponse\": \"amz:UpdateNetworkSettingsResponse\",\n    \"UpdatePortalResponse\": \"amz:UpdatePortalResponse\",\n    \"UpdateTrustStoreResponse\": \"amz:UpdateTrustStoreResponse\",\n    \"UpdateUserAccessLoggingSettingsResponse\": \"amz:UpdateUserAccessLoggingSettingsResponse\",\n    \"UpdateUserSettingsResponse\": \"amz:UpdateUserSettingsResponse\",\n    \"AssociateBrowserSettingsRequest\": \"amz:AssociateBrowserSettingsRequest\",\n    \"AssociateIpAccessSettingsRequest\": \"amz:AssociateIpAccessSettingsRequest\"\
  ,\n    \"AssociateNetworkSettingsRequest\": \"amz:AssociateNetworkSettingsRequest\",\n    \"AssociateTrustStoreRequest\": \"amz:AssociateTrustStoreRequest\",\n    \"AssociateUserAccessLoggingSettingsRequest\": \"amz:AssociateUserAccessLoggingSettingsRequest\",\n    \"AssociateUserSettingsRequest\": \"amz:AssociateUserSettingsRequest\",\n    \"BrowserSettings\": \"amz:BrowserSettings\",\n    \"associatedPortalArns\": {\n      \"@id\": \"amz:associatedPortalArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"browserPolicy\": {\n      \"@id\": \"amz:browserPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BrowserSettingsSummary\": \"amz:BrowserSettingsSummary\",\n    \"Certificate\": \"amz:Certificate\",\n    \"body\": {\n      \"@id\": \"amz:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuer\": {\n      \"@id\": \"amz:issuer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notValidAfter\": {\n      \"@id\": \"amz:notValidAfter\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"notValidBefore\": {\n      \"@id\": \"amz:notValidBefore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"amz:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thumbprint\": {\n      \"@id\": \"amz:thumbprint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificateSummary\": \"amz:CertificateSummary\",\n    \"EncryptionContextMap\": \"amz:EncryptionContextMap\",\n    \"CreateBrowserSettingsRequest\": \"amz:CreateBrowserSettingsRequest\",\n    \"additionalEncryptionContext\": {\n      \"@id\": \"amz:additionalEncryptionContext\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amz:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerManagedKey\": {\n      \"@id\": \"amz:customerManagedKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityProviderDetails\": \"amz:IdentityProviderDetails\",\n    \"CreateIdentityProviderRequest\": \"amz:CreateIdentityProviderRequest\"\
  ,\n    \"identityProviderDetails\": {\n      \"@id\": \"amz:identityProviderDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityProviderName\": {\n      \"@id\": \"amz:identityProviderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityProviderType\": {\n      \"@id\": \"amz:identityProviderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateIpAccessSettingsRequest\": \"amz:CreateIpAccessSettingsRequest\",\n    \"displayName\": {\n      \"@id\": \"amz:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipRules\": {\n      \"@id\": \"amz:ipRules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateNetworkSettingsRequest\": \"amz:CreateNetworkSettingsRequest\",\n    \"securityGroupIds\": {\n      \"@id\": \"amz:securityGroupIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"amz:subnetIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcId\": {\n      \"@id\": \"amz:vpcId\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"CreatePortalRequest\": \"amz:CreatePortalRequest\",\n    \"authenticationType\": {\n      \"@id\": \"amz:authenticationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTrustStoreRequest\": \"amz:CreateTrustStoreRequest\",\n    \"CreateUserAccessLoggingSettingsRequest\": \"amz:CreateUserAccessLoggingSettingsRequest\",\n    \"kinesisStreamArn\": {\n      \"@id\": \"amz:kinesisStreamArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateUserSettingsRequest\": \"amz:CreateUserSettingsRequest\",\n    \"copyAllowed\": {\n      \"@id\": \"amz:copyAllowed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disconnectTimeoutInMinutes\": {\n      \"@id\": \"amz:disconnectTimeoutInMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadAllowed\": {\n      \"@id\": \"amz:downloadAllowed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idleDisconnectTimeoutInMinutes\": {\n      \"@id\": \"amz:idleDisconnectTimeoutInMinutes\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"pasteAllowed\": {\n      \"@id\": \"amz:pasteAllowed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"printAllowed\": {\n      \"@id\": \"amz:printAllowed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uploadAllowed\": {\n      \"@id\": \"amz:uploadAllowed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteBrowserSettingsRequest\": \"amz:DeleteBrowserSettingsRequest\",\n    \"DeleteIdentityProviderRequest\": \"amz:DeleteIdentityProviderRequest\",\n    \"DeleteIpAccessSettingsRequest\": \"amz:DeleteIpAccessSettingsRequest\",\n    \"DeleteNetworkSettingsRequest\": \"amz:DeleteNetworkSettingsRequest\",\n    \"DeletePortalRequest\": \"amz:DeletePortalRequest\",\n    \"DeleteTrustStoreRequest\": \"amz:DeleteTrustStoreRequest\",\n    \"DeleteUserAccessLoggingSettingsRequest\": \"amz:DeleteUserAccessLoggingSettingsRequest\",\n    \"DeleteUserSettingsRequest\": \"amz:DeleteUserSettingsRequest\",\n    \"DisassociateBrowserSettingsRequest\": \"amz:DisassociateBrowserSettingsRequest\"\
  ,\n    \"DisassociateIpAccessSettingsRequest\": \"amz:DisassociateIpAccessSettingsRequest\",\n    \"DisassociateNetworkSettingsRequest\": \"amz:DisassociateNetworkSettingsRequest\",\n    \"DisassociateTrustStoreRequest\": \"amz:DisassociateTrustStoreRequest\",\n    \"DisassociateUserAccessLoggingSettingsRequest\": \"amz:DisassociateUserAccessLoggingSettingsRequest\",\n    \"DisassociateUserSettingsRequest\": \"amz:DisassociateUserSettingsRequest\",\n    \"GetBrowserSettingsRequest\": \"amz:GetBrowserSettingsRequest\",\n    \"GetIdentityProviderRequest\": \"amz:GetIdentityProviderRequest\",\n    \"IdentityProvider\": \"amz:IdentityProvider\",\n    \"GetIpAccessSettingsRequest\": \"amz:GetIpAccessSettingsRequest\",\n    \"IpAccessSettings\": \"amz:IpAccessSettings\",\n    \"creationDate\": {\n      \"@id\": \"amz:creationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetNetworkSettingsRequest\": \"amz:GetNetworkSettingsRequest\",\n    \"NetworkSettings\": \"amz:NetworkSettings\"\
  ,\n    \"GetPortalRequest\": \"amz:GetPortalRequest\",\n    \"Portal\": \"amz:Portal\",\n    \"browserType\": {\n      \"@id\": \"amz:browserType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portalStatus\": {\n      \"@id\": \"amz:portalStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rendererType\": {\n      \"@id\": \"amz:rendererType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"amz:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetPortalServiceProviderMetadataRequest\": \"amz:GetPortalServiceProviderMetadataRequest\",\n    \"GetTrustStoreCertificateRequest\": \"amz:GetTrustStoreCertificateRequest\",\n    \"GetTrustStoreRequest\": \"amz:GetTrustStoreRequest\",\n    \"TrustStore\": \"amz:TrustStore\",\n    \"GetUserAccessLoggingSettingsRequest\": \"amz:GetUserAccessLoggingSettingsRequest\",\n    \"UserAccessLoggingSettings\": \"amz:UserAccessLoggingSettings\",\n    \"GetUserSettingsRequest\": \"amz:GetUserSettingsRequest\"\
  ,\n    \"UserSettings\": \"amz:UserSettings\",\n    \"IdentityProviderSummary\": \"amz:IdentityProviderSummary\",\n    \"IpAccessSettingsSummary\": \"amz:IpAccessSettingsSummary\",\n    \"ListBrowserSettingsRequest\": \"amz:ListBrowserSettingsRequest\",\n    \"ListIdentityProvidersRequest\": \"amz:ListIdentityProvidersRequest\",\n    \"ListIpAccessSettingsRequest\": \"amz:ListIpAccessSettingsRequest\",\n    \"ListNetworkSettingsRequest\": \"amz:ListNetworkSettingsRequest\",\n    \"ListPortalsRequest\": \"amz:ListPortalsRequest\",\n    \"ListTagsForResourceRequest\": \"amz:ListTagsForResourceRequest\",\n    \"ListTrustStoreCertificatesRequest\": \"amz:ListTrustStoreCertificatesRequest\",\n    \"ListTrustStoresRequest\": \"amz:ListTrustStoresRequest\",\n    \"ListUserAccessLoggingSettingsRequest\": \"amz:ListUserAccessLoggingSettingsRequest\",\n    \"ListUserSettingsRequest\": \"amz:ListUserSettingsRequest\",\n    \"NetworkSettingsSummary\": \"amz:NetworkSettingsSummary\",\n    \"PortalSummary\"\
  : \"amz:PortalSummary\",\n    \"TagResourceRequest\": \"amz:TagResourceRequest\",\n    \"TrustStoreSummary\": \"amz:TrustStoreSummary\",\n    \"UntagResourceRequest\": \"amz:UntagResourceRequest\",\n    \"UpdateBrowserSettingsRequest\": \"amz:UpdateBrowserSettingsRequest\",\n    \"UpdateIdentityProviderRequest\": \"amz:UpdateIdentityProviderRequest\",\n    \"UpdateIpAccessSettingsRequest\": \"amz:UpdateIpAccessSettingsRequest\",\n    \"UpdateNetworkSettingsRequest\": \"amz:UpdateNetworkSettingsRequest\",\n    \"UpdatePortalRequest\": \"amz:UpdatePortalRequest\",\n    \"UpdateTrustStoreRequest\": \"amz:UpdateTrustStoreRequest\",\n    \"certificatesToAdd\": {\n      \"@id\": \"amz:certificatesToAdd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificatesToDelete\": {\n      \"@id\": \"amz:certificatesToDelete\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateUserAccessLoggingSettingsRequest\": \"amz:UpdateUserAccessLoggingSettingsRequest\",\n    \"UpdateUserSettingsRequest\"\
  : \"amz:UpdateUserSettingsRequest\",\n    \"UserAccessLoggingSettingsSummary\": \"amz:UserAccessLoggingSettingsSummary\",\n    \"UserSettingsSummary\": \"amz:UserSettingsSummary\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/json-ld/amazon-workspaces-web-context.jsonld
tags:
- AWS
- End User Computing
- Secure Browser
- Virtual Desktop
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---

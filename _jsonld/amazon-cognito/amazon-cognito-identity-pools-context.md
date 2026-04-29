---
class_count: 50
classes:
- LookupDeveloperIdentityResponse
- DeleteIdentitiesInput
- UnlinkDeveloperIdentityInput
- GetIdResponse
- GetPrincipalTagAttributeMapInput
- GetIdentityPoolRolesInput
- UntagResourceResponse
- IdentityProviders
- RolesMap
- ListIdentityPoolsResponse
- ListTagsForResourceInput
- GetIdInput
- GetCredentialsForIdentityInput
- UnprocessedIdentityId
- MergeDeveloperIdentitiesResponse
- IdentityPoolShortDescription
- DeleteIdentitiesResponse
- LoginsMap
- SetIdentityPoolRolesInput
- GetOpenIdTokenForDeveloperIdentityInput
- RulesConfigurationType
- IdentityPool
- CognitoIdentityProvider
- GetCredentialsForIdentityResponse
- ListIdentitiesInput
- ListIdentityPoolsInput
- GetPrincipalTagAttributeMapResponse
- TagResourceResponse
- UntagResourceInput
- GetOpenIdTokenInput
- ListIdentitiesResponse
- MergeDeveloperIdentitiesInput
- TagResourceInput
- ListTagsForResourceResponse
- LookupDeveloperIdentityInput
- GetOpenIdTokenForDeveloperIdentityResponse
- RoleMapping
- GetOpenIdTokenResponse
- IdentityPoolTagsType
- GetIdentityPoolRolesResponse
- MappingRule
- DeleteIdentityPoolInput
- UnlinkIdentityInput
- SetPrincipalTagAttributeMapResponse
- DescribeIdentityPoolInput
- SetPrincipalTagAttributeMapInput
- RoleMappingMap
- CreateIdentityPoolInput
- DescribeIdentityInput
- IdentityDescription
context_file: json-ld/amazon-cognito-identity-pools-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/json-ld/amazon-cognito-identity-pools-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Cognito Identity Pools from Amazon Cognito.
layout: jsonld
name: Amazon Cognito Identity Pools Context
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
  name: PrincipalTags
  type: string
- container: ''
  name: Credentials
  type: string
- container: ''
  name: IdentityId
  type: string
- container: ''
  name: DeveloperUserIdentifierList
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: IdentityIdsToDelete
  type: string
- container: ''
  name: IdentityPoolId
  type: string
- container: ''
  name: DeveloperProviderName
  type: string
- container: ''
  name: DeveloperUserIdentifier
  type: string
- container: ''
  name: IdentityProviderName
  type: string
- container: ''
  name: IdentityPools
  type: string
- container: ''
  name: ResourceArn
  type: string
- container: ''
  name: AccountId
  type: string
- container: ''
  name: Logins
  type: string
- container: ''
  name: CustomRoleArn
  type: string
- container: ''
  name: ErrorCode
  type: string
- container: ''
  name: IdentityPoolName
  type: string
- container: ''
  name: UnprocessedIdentityIds
  type: string
- container: ''
  name: Roles
  type: string
- container: ''
  name: RoleMappings
  type: string
- container: ''
  name: TokenDuration
  type: string
- container: ''
  name: Rules
  type: string
- container: ''
  name: AllowUnauthenticatedIdentities
  type: string
- container: ''
  name: AllowClassicFlow
  type: string
- container: ''
  name: SupportedLoginProviders
  type: string
- container: ''
  name: OpenIdConnectProviderARNs
  type: string
- container: ''
  name: CognitoIdentityProviders
  type: string
- container: ''
  name: SamlProviderARNs
  type: string
- container: ''
  name: IdentityPoolTags
  type: string
- container: ''
  name: ProviderName
  type: string
- container: ''
  name: ClientId
  type: string
- container: ''
  name: ServerSideTokenCheck
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: HideDisabled
  type: string
- container: ''
  name: UseDefaults
  type: string
- container: ''
  name: TagKeys
  type: string
- container: ''
  name: Identities
  type: string
- container: ''
  name: SourceUserIdentifier
  type: string
- container: ''
  name: DestinationUserIdentifier
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Token
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: AmbiguousRoleResolution
  type: string
- container: ''
  name: RulesConfiguration
  type: string
- container: ''
  name: AccessKeyId
  type: string
- container: ''
  name: SecretKey
  type: string
- container: ''
  name: SessionToken
  type: string
- container: ''
  name: Expiration
  type: string
- container: ''
  name: Claim
  type: string
- container: ''
  name: MatchType
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: RoleARN
  type: string
- container: ''
  name: LoginsToRemove
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: LastModifiedDate
  type: string
property_count: 55
provider_name: Amazon Cognito
provider_slug: amazon-cognito
slug: amazon-cognito-identity-pools-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LookupDeveloperIdentityResponse\": \"aws:LookupDeveloperIdentityResponse\",\n    \"DeleteIdentitiesInput\": \"aws:DeleteIdentitiesInput\",\n    \"UnlinkDeveloperIdentityInput\": \"aws:UnlinkDeveloperIdentityInput\",\n    \"GetIdResponse\": \"aws:GetIdResponse\",\n    \"GetPrincipalTagAttributeMapInput\": \"aws:GetPrincipalTagAttributeMapInput\",\n    \"GetIdentityPoolRolesInput\": \"aws:GetIdentityPoolRolesInput\",\n    \"UntagResourceResponse\": \"aws:UntagResourceResponse\",\n    \"IdentityProviders\": \"aws:IdentityProviders\",\n    \"RolesMap\": \"aws:RolesMap\",\n    \"ListIdentityPoolsResponse\": \"aws:ListIdentityPoolsResponse\",\n    \"ListTagsForResourceInput\": \"aws:ListTagsForResourceInput\",\n    \"GetIdInput\": \"aws:GetIdInput\"\
  ,\n    \"GetCredentialsForIdentityInput\": \"aws:GetCredentialsForIdentityInput\",\n    \"UnprocessedIdentityId\": \"aws:UnprocessedIdentityId\",\n    \"MergeDeveloperIdentitiesResponse\": \"aws:MergeDeveloperIdentitiesResponse\",\n    \"IdentityPoolShortDescription\": \"aws:IdentityPoolShortDescription\",\n    \"DeleteIdentitiesResponse\": \"aws:DeleteIdentitiesResponse\",\n    \"LoginsMap\": \"aws:LoginsMap\",\n    \"SetIdentityPoolRolesInput\": \"aws:SetIdentityPoolRolesInput\",\n    \"GetOpenIdTokenForDeveloperIdentityInput\": \"aws:GetOpenIdTokenForDeveloperIdentityInput\",\n    \"RulesConfigurationType\": \"aws:RulesConfigurationType\",\n    \"IdentityPool\": \"aws:IdentityPool\",\n    \"CognitoIdentityProvider\": \"aws:CognitoIdentityProvider\",\n    \"PrincipalTags\": {\n      \"@id\": \"aws:PrincipalTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCredentialsForIdentityResponse\": \"aws:GetCredentialsForIdentityResponse\",\n    \"ListIdentitiesInput\": \"aws:ListIdentitiesInput\"\
  ,\n    \"ListIdentityPoolsInput\": \"aws:ListIdentityPoolsInput\",\n    \"GetPrincipalTagAttributeMapResponse\": \"aws:GetPrincipalTagAttributeMapResponse\",\n    \"TagResourceResponse\": \"aws:TagResourceResponse\",\n    \"UntagResourceInput\": \"aws:UntagResourceInput\",\n    \"GetOpenIdTokenInput\": \"aws:GetOpenIdTokenInput\",\n    \"ListIdentitiesResponse\": \"aws:ListIdentitiesResponse\",\n    \"MergeDeveloperIdentitiesInput\": \"aws:MergeDeveloperIdentitiesInput\",\n    \"TagResourceInput\": \"aws:TagResourceInput\",\n    \"ListTagsForResourceResponse\": \"aws:ListTagsForResourceResponse\",\n    \"LookupDeveloperIdentityInput\": \"aws:LookupDeveloperIdentityInput\",\n    \"GetOpenIdTokenForDeveloperIdentityResponse\": \"aws:GetOpenIdTokenForDeveloperIdentityResponse\",\n    \"RoleMapping\": \"aws:RoleMapping\",\n    \"GetOpenIdTokenResponse\": \"aws:GetOpenIdTokenResponse\",\n    \"IdentityPoolTagsType\": \"aws:IdentityPoolTagsType\",\n    \"Credentials\": {\n      \"@id\": \"aws:Credentials\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"GetIdentityPoolRolesResponse\": \"aws:GetIdentityPoolRolesResponse\",\n    \"MappingRule\": \"aws:MappingRule\",\n    \"DeleteIdentityPoolInput\": \"aws:DeleteIdentityPoolInput\",\n    \"UnlinkIdentityInput\": \"aws:UnlinkIdentityInput\",\n    \"SetPrincipalTagAttributeMapResponse\": \"aws:SetPrincipalTagAttributeMapResponse\",\n    \"DescribeIdentityPoolInput\": \"aws:DescribeIdentityPoolInput\",\n    \"SetPrincipalTagAttributeMapInput\": \"aws:SetPrincipalTagAttributeMapInput\",\n    \"RoleMappingMap\": \"aws:RoleMappingMap\",\n    \"CreateIdentityPoolInput\": \"aws:CreateIdentityPoolInput\",\n    \"DescribeIdentityInput\": \"aws:DescribeIdentityInput\",\n    \"IdentityDescription\": \"aws:IdentityDescription\",\n    \"IdentityId\": {\n      \"@id\": \"aws:IdentityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeveloperUserIdentifierList\": {\n      \"@id\": \"aws:DeveloperUserIdentifierList\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityIdsToDelete\": {\n      \"@id\": \"aws:IdentityIdsToDelete\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityPoolId\": {\n      \"@id\": \"aws:IdentityPoolId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeveloperProviderName\": {\n      \"@id\": \"aws:DeveloperProviderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeveloperUserIdentifier\": {\n      \"@id\": \"aws:DeveloperUserIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityProviderName\": {\n      \"@id\": \"aws:IdentityProviderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityPools\": {\n      \"@id\": \"aws:IdentityPools\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceArn\": {\n      \"@id\": \"aws:ResourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountId\": {\n      \"@id\": \"aws:AccountId\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"Logins\": {\n      \"@id\": \"aws:Logins\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomRoleArn\": {\n      \"@id\": \"aws:CustomRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorCode\": {\n      \"@id\": \"aws:ErrorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityPoolName\": {\n      \"@id\": \"aws:IdentityPoolName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UnprocessedIdentityIds\": {\n      \"@id\": \"aws:UnprocessedIdentityIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Roles\": {\n      \"@id\": \"aws:Roles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleMappings\": {\n      \"@id\": \"aws:RoleMappings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TokenDuration\": {\n      \"@id\": \"aws:TokenDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rules\": {\n      \"@id\": \"aws:Rules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowUnauthenticatedIdentities\": {\n      \"@id\": \"aws:AllowUnauthenticatedIdentities\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowClassicFlow\": {\n      \"@id\": \"aws:AllowClassicFlow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportedLoginProviders\": {\n      \"@id\": \"aws:SupportedLoginProviders\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OpenIdConnectProviderARNs\": {\n      \"@id\": \"aws:OpenIdConnectProviderARNs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CognitoIdentityProviders\": {\n      \"@id\": \"aws:CognitoIdentityProviders\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SamlProviderARNs\": {\n      \"@id\": \"aws:SamlProviderARNs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityPoolTags\": {\n      \"@id\": \"aws:IdentityPoolTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProviderName\": {\n      \"@id\": \"aws:ProviderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientId\": {\n      \"@id\": \"aws:ClientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServerSideTokenCheck\": {\n  \
  \    \"@id\": \"aws:ServerSideTokenCheck\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"aws:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HideDisabled\": {\n      \"@id\": \"aws:HideDisabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UseDefaults\": {\n      \"@id\": \"aws:UseDefaults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagKeys\": {\n      \"@id\": \"aws:TagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Identities\": {\n      \"@id\": \"aws:Identities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceUserIdentifier\": {\n      \"@id\": \"aws:SourceUserIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DestinationUserIdentifier\": {\n      \"@id\": \"aws:DestinationUserIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"aws:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Token\": {\n      \"@id\": \"aws:Token\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Type\": {\n      \"@id\": \"aws:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AmbiguousRoleResolution\": {\n      \"@id\": \"aws:AmbiguousRoleResolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RulesConfiguration\": {\n      \"@id\": \"aws:RulesConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccessKeyId\": {\n      \"@id\": \"aws:AccessKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecretKey\": {\n      \"@id\": \"aws:SecretKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SessionToken\": {\n      \"@id\": \"aws:SessionToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Expiration\": {\n      \"@id\": \"aws:Expiration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Claim\": {\n      \"@id\": \"aws:Claim\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MatchType\": {\n      \"@id\": \"aws:MatchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"aws:Value\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"RoleARN\": {\n      \"@id\": \"aws:RoleARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoginsToRemove\": {\n      \"@id\": \"aws:LoginsToRemove\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"aws:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"aws:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-cognito/refs/heads/main/json-ld/amazon-cognito-identity-pools-context.jsonld
tags:
- Authentication
- AWS
- Identity
- OAuth
- User Management
- JSON-LD
- Linked Data
- Semantic Web
---

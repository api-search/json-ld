---
class_count: 1
classes:
- id
context_file: json-ld/active-directory-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/active-directory/refs/heads/main/json-ld/active-directory-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Active Directory from Microsoft Active Directory.
layout: jsonld
name: Active Directory Context
namespaces:
- prefix: ad
  uri: https://learn.microsoft.com/en-us/graph/api/resources/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: User
  type: reference
- container: ''
  name: Group
  type: reference
- container: ''
  name: Application
  type: reference
- container: ''
  name: ServicePrincipal
  type: reference
- container: ''
  name: Device
  type: reference
- container: ''
  name: DirectoryRole
  type: reference
- container: ''
  name: AdministrativeUnit
  type: reference
- container: ''
  name: ConditionalAccessPolicy
  type: reference
- container: ''
  name: AppRoleAssignment
  type: reference
- container: ''
  name: PasswordProfile
  type: reference
- container: ''
  name: appId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: userPrincipalName
  type: string
- container: ''
  name: mail
  type: string
- container: ''
  name: givenName
  type: string
- container: ''
  name: surname
  type: string
- container: ''
  name: jobTitle
  type: string
- container: ''
  name: department
  type: string
- container: ''
  name: officeLocation
  type: string
- container: ''
  name: mobilePhone
  type: string
- container: set
  name: businessPhones
  type: ''
- container: ''
  name: accountEnabled
  type: boolean
- container: ''
  name: usageLocation
  type: string
- container: ''
  name: preferredLanguage
  type: string
- container: ''
  name: createdDateTime
  type: dateTime
- container: ''
  name: lastPasswordChangeDateTime
  type: dateTime
- container: ''
  name: passwordPolicies
  type: string
- container: ''
  name: userType
  type: string
- container: ''
  name: onPremisesSyncEnabled
  type: boolean
- container: ''
  name: onPremisesDistinguishedName
  type: string
- container: ''
  name: externalUserState
  type: string
- container: set
  name: assignedLicenses
  type: ''
- container: ''
  name: mailNickname
  type: string
- container: ''
  name: mailEnabled
  type: boolean
- container: ''
  name: securityEnabled
  type: boolean
- container: set
  name: groupTypes
  type: ''
- container: ''
  name: visibility
  type: string
- container: ''
  name: membershipRule
  type: string
- container: ''
  name: membershipRuleProcessingState
  type: string
- container: ''
  name: renewedDateTime
  type: dateTime
- container: ''
  name: expirationDateTime
  type: dateTime
- container: ''
  name: preferredDataLocation
  type: string
- container: set
  name: resourceProvisioningOptions
  type: ''
- container: ''
  name: signInAudience
  type: string
- container: set
  name: identifierUris
  type: ''
- container: ''
  name: web
  type: ''
- container: set
  name: redirectUris
  type: ''
- container: ''
  name: logoutUrl
  type: anyURI
- container: set
  name: requiredResourceAccess
  type: ''
- container: set
  name: keyCredentials
  type: ''
- container: set
  name: passwordCredentials
  type: ''
- container: ''
  name: deletedDateTime
  type: dateTime
- container: ''
  name: servicePrincipalType
  type: string
- container: set
  name: appRoles
  type: ''
- container: set
  name: oauth2PermissionScopes
  type: ''
- container: ''
  name: homepage
  type: anyURI
- container: ''
  name: loginUrl
  type: anyURI
- container: set
  name: replyUrls
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: appRoleId
  type: string
- container: ''
  name: principalId
  type: string
- container: ''
  name: principalDisplayName
  type: string
- container: ''
  name: principalType
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceDisplayName
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: forceChangePasswordNextSignIn
  type: boolean
- container: ''
  name: forceChangePasswordNextSignInWithMfa
  type: boolean
property_count: 69
provider_name: Microsoft Active Directory
provider_slug: active-directory
slug: active-directory-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ad\": \"https://learn.microsoft.com/en-us/graph/api/resources/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"User\": {\n      \"@id\": \"ad:user\",\n      \"@type\": \"@id\"\n    },\n    \"Group\": {\n      \"@id\": \"ad:group\",\n      \"@type\": \"@id\"\n    },\n    \"Application\": {\n      \"@id\": \"ad:application\",\n      \"@type\": \"@id\"\n    },\n    \"ServicePrincipal\": {\n      \"@id\": \"ad:serviceprincipal\",\n      \"@type\": \"@id\"\n    },\n    \"Device\": {\n      \"@id\": \"ad:device\",\n      \"@type\": \"@id\"\n    },\n    \"DirectoryRole\": {\n      \"@id\": \"ad:directoryrole\",\n      \"@type\": \"@id\"\n    },\n    \"AdministrativeUnit\": {\n      \"@id\": \"ad:administrativeunit\",\n      \"@type\": \"@id\"\n    },\n    \"ConditionalAccessPolicy\": {\n      \"@id\": \"ad:conditionalaccesspolicy\",\n      \"@type\": \"@id\"\n    },\n   \
  \ \"AppRoleAssignment\": {\n      \"@id\": \"ad:approleassignment\",\n      \"@type\": \"@id\"\n    },\n    \"PasswordProfile\": {\n      \"@id\": \"ad:passwordprofile\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"appId\": { \"@id\": \"ad:appId\", \"@type\": \"xsd:string\" },\n    \"displayName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"userPrincipalName\": { \"@id\": \"ad:userPrincipalName\", \"@type\": \"xsd:string\" },\n    \"mail\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n    \"givenName\": { \"@id\": \"schema:givenName\", \"@type\": \"xsd:string\" },\n    \"surname\": { \"@id\": \"schema:familyName\", \"@type\": \"xsd:string\" },\n    \"jobTitle\": { \"@id\": \"schema:jobTitle\", \"@type\": \"xsd:string\" },\n    \"department\": { \"@id\": \"schema:department\", \"@type\": \"xsd:string\" },\n    \"officeLocation\": { \"@id\": \"schema:workLocation\"\
  , \"@type\": \"xsd:string\" },\n    \"mobilePhone\": { \"@id\": \"schema:telephone\", \"@type\": \"xsd:string\" },\n    \"businessPhones\": { \"@id\": \"schema:telephone\", \"@container\": \"@set\" },\n    \"accountEnabled\": { \"@id\": \"ad:accountEnabled\", \"@type\": \"xsd:boolean\" },\n    \"usageLocation\": { \"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\" },\n    \"preferredLanguage\": { \"@id\": \"schema:inLanguage\", \"@type\": \"xsd:string\" },\n    \"createdDateTime\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"lastPasswordChangeDateTime\": { \"@id\": \"ad:lastPasswordChangeDateTime\", \"@type\": \"xsd:dateTime\" },\n    \"passwordPolicies\": { \"@id\": \"ad:passwordPolicies\", \"@type\": \"xsd:string\" },\n    \"userType\": { \"@id\": \"ad:userType\", \"@type\": \"xsd:string\" },\n    \"onPremisesSyncEnabled\": { \"@id\": \"ad:onPremisesSyncEnabled\", \"@type\": \"xsd:boolean\" },\n    \"onPremisesDistinguishedName\": { \"@id\": \"\
  ad:onPremisesDistinguishedName\", \"@type\": \"xsd:string\" },\n    \"externalUserState\": { \"@id\": \"ad:externalUserState\", \"@type\": \"xsd:string\" },\n    \"assignedLicenses\": { \"@id\": \"ad:assignedLicenses\", \"@container\": \"@set\" },\n\n    \"mailNickname\": { \"@id\": \"ad:mailNickname\", \"@type\": \"xsd:string\" },\n    \"mailEnabled\": { \"@id\": \"ad:mailEnabled\", \"@type\": \"xsd:boolean\" },\n    \"securityEnabled\": { \"@id\": \"ad:securityEnabled\", \"@type\": \"xsd:boolean\" },\n    \"groupTypes\": { \"@id\": \"ad:groupTypes\", \"@container\": \"@set\" },\n    \"visibility\": { \"@id\": \"ad:visibility\", \"@type\": \"xsd:string\" },\n    \"membershipRule\": { \"@id\": \"ad:membershipRule\", \"@type\": \"xsd:string\" },\n    \"membershipRuleProcessingState\": { \"@id\": \"ad:membershipRuleProcessingState\", \"@type\": \"xsd:string\" },\n    \"renewedDateTime\": { \"@id\": \"ad:renewedDateTime\", \"@type\": \"xsd:dateTime\" },\n    \"expirationDateTime\": { \"@id\"\
  : \"ad:expirationDateTime\", \"@type\": \"xsd:dateTime\" },\n    \"preferredDataLocation\": { \"@id\": \"ad:preferredDataLocation\", \"@type\": \"xsd:string\" },\n    \"resourceProvisioningOptions\": { \"@id\": \"ad:resourceProvisioningOptions\", \"@container\": \"@set\" },\n\n    \"signInAudience\": { \"@id\": \"ad:signInAudience\", \"@type\": \"xsd:string\" },\n    \"identifierUris\": { \"@id\": \"ad:identifierUris\", \"@container\": \"@set\" },\n    \"web\": { \"@id\": \"ad:web\" },\n    \"redirectUris\": { \"@id\": \"ad:redirectUris\", \"@container\": \"@set\" },\n    \"logoutUrl\": { \"@id\": \"ad:logoutUrl\", \"@type\": \"xsd:anyURI\" },\n    \"requiredResourceAccess\": { \"@id\": \"ad:requiredResourceAccess\", \"@container\": \"@set\" },\n    \"keyCredentials\": { \"@id\": \"ad:keyCredentials\", \"@container\": \"@set\" },\n    \"passwordCredentials\": { \"@id\": \"ad:passwordCredentials\", \"@container\": \"@set\" },\n    \"deletedDateTime\": { \"@id\": \"ad:deletedDateTime\",\
  \ \"@type\": \"xsd:dateTime\" },\n\n    \"servicePrincipalType\": { \"@id\": \"ad:servicePrincipalType\", \"@type\": \"xsd:string\" },\n    \"appRoles\": { \"@id\": \"ad:appRoles\", \"@container\": \"@set\" },\n    \"oauth2PermissionScopes\": { \"@id\": \"ad:oauth2PermissionScopes\", \"@container\": \"@set\" },\n    \"homepage\": { \"@id\": \"schema:url\", \"@type\": \"xsd:anyURI\" },\n    \"loginUrl\": { \"@id\": \"ad:loginUrl\", \"@type\": \"xsd:anyURI\" },\n    \"replyUrls\": { \"@id\": \"ad:replyUrls\", \"@container\": \"@set\" },\n    \"tags\": { \"@id\": \"schema:keywords\", \"@container\": \"@set\" },\n\n    \"appRoleId\": { \"@id\": \"ad:appRoleId\", \"@type\": \"xsd:string\" },\n    \"principalId\": { \"@id\": \"ad:principalId\", \"@type\": \"xsd:string\" },\n    \"principalDisplayName\": { \"@id\": \"ad:principalDisplayName\", \"@type\": \"xsd:string\" },\n    \"principalType\": { \"@id\": \"ad:principalType\", \"@type\": \"xsd:string\" },\n    \"resourceId\": { \"@id\": \"ad:resourceId\"\
  , \"@type\": \"xsd:string\" },\n    \"resourceDisplayName\": { \"@id\": \"ad:resourceDisplayName\", \"@type\": \"xsd:string\" },\n\n    \"password\": { \"@id\": \"ad:password\", \"@type\": \"xsd:string\" },\n    \"forceChangePasswordNextSignIn\": { \"@id\": \"ad:forceChangePasswordNextSignIn\", \"@type\": \"xsd:boolean\" },\n    \"forceChangePasswordNextSignInWithMfa\": { \"@id\": \"ad:forceChangePasswordNextSignInWithMfa\", \"@type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/active-directory/refs/heads/main/json-ld/active-directory-context.jsonld
tags:
- Active Directory
- Authentication
- Authorization
- Directory Services
- Identity Management
- Microsoft Entra
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---

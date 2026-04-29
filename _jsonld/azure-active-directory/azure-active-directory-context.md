---
api_specs:
- filename: microsoft-graph-identity-api.yml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-active-directory/refs/heads/main/openapi/microsoft-graph-identity-api.yml
- filename: microsoft-graph-identity-api.yml
  format: yaml
  label: Microsoft Graph Identity and Access API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure-active-directory/refs/heads/main/openapi/microsoft-graph-identity-api.yml
class_count: 1
classes:
- scim
context_file: json-ld/azure-active-directory-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-active-directory/refs/heads/main/json-ld/azure-active-directory-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Active Directory from Azure Active Directory.
layout: jsonld
name: Azure Active Directory Context
namespaces:
- prefix: msgraph
  uri: https://graph.microsoft.com/v1.0/$metadata#
- prefix: schema
  uri: https://schema.org/
- prefix: entra
  uri: https://learn.microsoft.com/en-us/graph/api/resources/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: ServicePrincipal
  type: ''
- container: ''
  name: DirectoryObject
  type: ''
- container: ''
  name: AppRoleAssignment
  type: ''
property_count: 6
provider_name: Azure Active Directory
provider_slug: azure-active-directory
slug: azure-active-directory-context
source_filename: azure-active-directory-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://graph.microsoft.com/v1.0/$metadata#\",\n    \"msgraph\": \"https://graph.microsoft.com/v1.0/$metadata#\",\n    \"schema\": \"https://schema.org/\",\n    \"entra\": \"https://learn.microsoft.com/en-us/graph/api/resources/\",\n    \"scim\": \"urn:ietf:params:scim:schemas:core:2.0:\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"User\": {\n      \"@id\": \"msgraph:users\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"msgraph:users/id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"givenName\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"surname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userPrincipalName\": {\n          \"@id\": \"msgraph:users/userPrincipalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobTitle\": {\n          \"@id\": \"schema:jobTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"org:unitOf\",\n          \"@type\": \"xsd:string\"\n        },\n        \"officeLocation\": {\n          \"@id\": \"schema:workLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"businessPhones\": {\n          \"@id\": \"schema:telephone\",\n          \"@container\": \"@set\"\n        },\n        \"mobilePhone\": {\n          \"@id\": \"vcard:hasTelephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\"\
  : {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postalCode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"streetAddress\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"companyName\": {\n          \"@id\": \"schema:worksFor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"employeeId\": {\n          \"@id\": \"msgraph:users/employeeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"employeeType\": {\n          \"@id\": \"msgraph:users/employeeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountEnabled\": {\n          \"\
  @id\": \"msgraph:users/accountEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"usageLocation\": {\n          \"@id\": \"msgraph:users/usageLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"preferredLanguage\": {\n          \"@id\": \"schema:knowsLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userType\": {\n          \"@id\": \"msgraph:users/userType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mailNickname\": {\n          \"@id\": \"msgraph:users/mailNickname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"otherMails\": {\n          \"@id\": \"msgraph:users/otherMails\",\n          \"@container\": \"@set\"\n        },\n        \"proxyAddresses\": {\n          \"@id\": \"msgraph:users/proxyAddresses\",\n          \"@container\": \"@set\"\n        },\n        \"onPremisesSyncEnabled\"\
  : {\n          \"@id\": \"msgraph:users/onPremisesSyncEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"memberOf\": {\n          \"@id\": \"org:memberOf\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"msgraph:groups\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"msgraph:groups/id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mailEnabled\": {\n          \"@id\": \"msgraph:groups/mailEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"mailNickname\": {\n          \"@id\": \"msgraph:groups/mailNickname\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"securityEnabled\": {\n          \"@id\": \"msgraph:groups/securityEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"groupTypes\": {\n          \"@id\": \"msgraph:groups/groupTypes\",\n          \"@container\": \"@set\"\n        },\n        \"visibility\": {\n          \"@id\": \"msgraph:groups/visibility\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"renewedDateTime\": {\n          \"@id\": \"msgraph:groups/renewedDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"classification\": {\n          \"@id\": \"msgraph:groups/classification\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isAssignableToRole\": {\n          \"@id\": \"msgraph:groups/isAssignableToRole\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"members\"\
  : {\n          \"@id\": \"org:hasMember\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"owners\": {\n          \"@id\": \"msgraph:groups/owners\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"membershipRule\": {\n          \"@id\": \"msgraph:groups/membershipRule\",\n          \"@type\": \"xsd:string\"\n        },\n        \"onPremisesSyncEnabled\": {\n          \"@id\": \"msgraph:groups/onPremisesSyncEnabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Application\": {\n      \"@id\": \"msgraph:applications\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"msgraph:applications/id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appId\": {\n          \"@id\": \"msgraph:applications/appId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"identifierUris\": {\n          \"@id\": \"msgraph:applications/identifierUris\",\n          \"@container\": \"@set\",\n          \"@type\": \"@id\"\n        },\n        \"signInAudience\": {\n          \"@id\": \"msgraph:applications/signInAudience\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publisherDomain\": {\n          \"@id\": \"msgraph:applications/publisherDomain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"web\": {\n          \"@id\": \"msgraph:applications/web\",\n          \"@context\": {\n            \"homePageUrl\": {\n              \"@id\": \"schema:url\",\n              \"@type\": \"@id\"\n            },\n            \"redirectUris\": {\n              \"@id\": \"msgraph:applications/web/redirectUris\"\
  ,\n              \"@container\": \"@set\",\n              \"@type\": \"@id\"\n            },\n            \"logoutUrl\": {\n              \"@id\": \"msgraph:applications/web/logoutUrl\",\n              \"@type\": \"@id\"\n            }\n          }\n        },\n        \"spa\": {\n          \"@id\": \"msgraph:applications/spa\",\n          \"@context\": {\n            \"redirectUris\": {\n              \"@id\": \"msgraph:applications/spa/redirectUris\",\n              \"@container\": \"@set\",\n              \"@type\": \"@id\"\n            }\n          }\n        },\n        \"requiredResourceAccess\": {\n          \"@id\": \"msgraph:applications/requiredResourceAccess\",\n          \"@container\": \"@set\"\n        },\n        \"appRoles\": {\n          \"@id\": \"msgraph:applications/appRoles\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ServicePrincipal\"\
  : {\n      \"@id\": \"msgraph:servicePrincipals\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"msgraph:servicePrincipals/id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appId\": {\n          \"@id\": \"msgraph:servicePrincipals/appId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appDisplayName\": {\n          \"@id\": \"msgraph:servicePrincipals/appDisplayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountEnabled\": {\n          \"@id\": \"msgraph:servicePrincipals/accountEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"appOwnerOrganizationId\": {\n          \"@id\": \"msgraph:servicePrincipals/appOwnerOrganizationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appRoleAssignmentRequired\": {\n          \"@id\": \"msgraph:servicePrincipals/appRoleAssignmentRequired\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"servicePrincipalType\": {\n          \"@id\": \"msgraph:servicePrincipals/servicePrincipalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"servicePrincipalNames\": {\n          \"@id\": \"msgraph:servicePrincipals/servicePrincipalNames\",\n          \"@container\": \"@set\"\n        },\n        \"homepage\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"loginUrl\": {\n          \"@id\": \"msgraph:servicePrincipals/loginUrl\",\n          \"@type\": \"@id\"\n        },\n        \"logoutUrl\": {\n          \"@id\": \"msgraph:servicePrincipals/logoutUrl\",\n          \"@type\": \"@id\"\n        },\n        \"replyUrls\": {\n          \"@id\": \"msgraph:servicePrincipals/replyUrls\",\n          \"@container\": \"@set\",\n          \"@type\": \"@id\"\n        },\n        \"signInAudience\": {\n          \"@id\": \"msgraph:servicePrincipals/signInAudience\",\n       \
  \   \"@type\": \"xsd:string\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"notificationEmailAddresses\": {\n          \"@id\": \"msgraph:servicePrincipals/notificationEmailAddresses\",\n          \"@container\": \"@set\"\n        },\n        \"oauth2PermissionScopes\": {\n          \"@id\": \"msgraph:servicePrincipals/oauth2PermissionScopes\",\n          \"@container\": \"@set\"\n        },\n        \"appRoles\": {\n          \"@id\": \"msgraph:servicePrincipals/appRoles\",\n          \"@container\": \"@set\"\n        },\n        \"appRoleAssignments\": {\n          \"@id\": \"msgraph:servicePrincipals/appRoleAssignments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"DirectoryObject\": {\n      \"@id\": \"msgraph:directoryObjects\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"msgraph:directoryObjects/id\",\n          \"@type\": \"xsd:string\"\n      \
  \  },\n        \"deletedDateTime\": {\n          \"@id\": \"msgraph:directoryObjects/deletedDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AppRoleAssignment\": {\n      \"@id\": \"msgraph:appRoleAssignments\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"msgraph:appRoleAssignments/id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appRoleId\": {\n          \"@id\": \"msgraph:appRoleAssignments/appRoleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"principalId\": {\n          \"@id\": \"msgraph:appRoleAssignments/principalId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"principalDisplayName\": {\n          \"@id\": \"msgraph:appRoleAssignments/principalDisplayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"principalType\": {\n          \"@id\": \"msgraph:appRoleAssignments/principalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resourceId\"\
  : {\n          \"@id\": \"msgraph:appRoleAssignments/resourceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resourceDisplayName\": {\n          \"@id\": \"msgraph:appRoleAssignments/resourceDisplayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-active-directory/refs/heads/main/json-ld/azure-active-directory-context.jsonld
tags:
- Authentication
- Authorization
- Identity
- Microsoft
- Microsoft Entra
- OAuth
- OpenID Connect
- SAML
- SCIM
- Single Sign-On
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---

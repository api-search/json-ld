---
class_count: 0
classes: []
context_file: json-ld/microsoft-entra-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-entra/refs/heads/main/json-ld/microsoft-entra-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Entra from Microsoft Entra.
layout: jsonld
name: Microsoft Entra Context
namespaces:
- prefix: entra
  uri: https://graph.microsoft.com/v1.0/
- prefix: graph
  uri: https://graph.microsoft.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
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
  name: AppRoleAssignment
  type: ''
property_count: 5
provider_name: Microsoft Entra
provider_slug: microsoft-entra
slug: microsoft-entra-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"entra\": \"https://graph.microsoft.com/v1.0/\",\n    \"graph\": \"https://graph.microsoft.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n\n    \"User\": {\n      \"@id\": \"graph:User\",\n      \"@context\": {\n        \"id\": \"graph:id\",\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"givenName\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"surname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userPrincipalName\"\
  : {\n          \"@id\": \"graph:userPrincipalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobTitle\": {\n          \"@id\": \"schema:jobTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"graph:department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"companyName\": {\n          \"@id\": \"schema:worksFor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"officeLocation\": {\n          \"@id\": \"schema:workLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mobilePhone\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"businessPhones\": {\n          \"@id\": \"graph:businessPhones\",\n          \"@container\": \"@set\"\n        },\n        \"streetAddress\": {\n          \"@id\": \"vcard:street-address\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"vcard:locality\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"vcard:region\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postalCode\": {\n          \"@id\": \"vcard:postal-code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"vcard:country-name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userType\": \"graph:userType\",\n        \"accountEnabled\": \"graph:accountEnabled\",\n        \"employeeId\": {\n          \"@id\": \"graph:employeeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"employeeType\": \"graph:employeeType\",\n        \"employeeHireDate\": {\n          \"@id\": \"graph:employeeHireDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"preferredLanguage\": {\n          \"@id\": \"schema:knowsLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usageLocation\": \"graph:usageLocation\",\n        \"createdDateTime\"\
  : {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastSignInDateTime\": {\n          \"@id\": \"graph:lastSignInDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"onPremisesSyncEnabled\": \"graph:onPremisesSyncEnabled\",\n        \"proxyAddresses\": {\n          \"@id\": \"graph:proxyAddresses\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"graph:Group\",\n      \"@context\": {\n        \"id\": \"graph:id\",\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mailEnabled\": \"graph:mailEnabled\",\n        \"mailNickname\": \"graph:mailNickname\",\n      \
  \  \"securityEnabled\": \"graph:securityEnabled\",\n        \"groupTypes\": {\n          \"@id\": \"graph:groupTypes\",\n          \"@container\": \"@set\"\n        },\n        \"visibility\": \"graph:visibility\",\n        \"membershipRule\": \"graph:membershipRule\",\n        \"isAssignableToRole\": \"graph:isAssignableToRole\",\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"members\": {\n          \"@id\": \"graph:members\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"owners\": {\n          \"@id\": \"graph:owners\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Application\": {\n      \"@id\": \"graph:Application\",\n      \"@context\": {\n        \"id\": \"graph:id\",\n        \"appId\": {\n          \"@id\": \"graph:appId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\"\
  : {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signInAudience\": \"graph:signInAudience\",\n        \"identifierUris\": {\n          \"@id\": \"graph:identifierUris\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"publisherDomain\": {\n          \"@id\": \"graph:publisherDomain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"requiredResourceAccess\": {\n          \"@id\": \"graph:requiredResourceAccess\",\n          \"@container\": \"@set\"\n        },\n        \"appRoles\": {\n          \"@id\": \"graph:appRoles\",\n          \"@container\": \"@set\"\n   \
  \     },\n        \"keyCredentials\": {\n          \"@id\": \"graph:keyCredentials\",\n          \"@container\": \"@set\"\n        },\n        \"passwordCredentials\": {\n          \"@id\": \"graph:passwordCredentials\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ServicePrincipal\": {\n      \"@id\": \"graph:ServicePrincipal\",\n      \"@context\": {\n        \"id\": \"graph:id\",\n        \"appId\": {\n          \"@id\": \"graph:appId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"servicePrincipalType\": \"graph:servicePrincipalType\",\n        \"appDisplayName\": {\n          \"@id\": \"graph:appDisplayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountEnabled\": \"graph:accountEnabled\"\
  ,\n        \"homepage\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"loginUrl\": {\n          \"@id\": \"graph:loginUrl\",\n          \"@type\": \"@id\"\n        },\n        \"logoutUrl\": {\n          \"@id\": \"graph:logoutUrl\",\n          \"@type\": \"@id\"\n        },\n        \"replyUrls\": {\n          \"@id\": \"graph:replyUrls\",\n          \"@container\": \"@set\"\n        },\n        \"servicePrincipalNames\": {\n          \"@id\": \"graph:servicePrincipalNames\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"appRoleAssignmentRequired\": \"graph:appRoleAssignmentRequired\",\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AppRoleAssignment\": {\n      \"@id\": \"graph:AppRoleAssignment\",\n      \"@context\":\
  \ {\n        \"id\": \"graph:id\",\n        \"appRoleId\": {\n          \"@id\": \"graph:appRoleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"principalId\": {\n          \"@id\": \"graph:principalId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"principalType\": \"graph:principalType\",\n        \"principalDisplayName\": {\n          \"@id\": \"graph:principalDisplayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resourceId\": {\n          \"@id\": \"graph:resourceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resourceDisplayName\": {\n          \"@id\": \"graph:resourceDisplayName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDateTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-entra/refs/heads/main/json-ld/microsoft-entra-context.jsonld
tags:
- Access Management
- Authentication
- Azure AD
- Entra
- Identity
- Identity Governance
- Microsoft
- Network Security
- Security
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: admin-sdk-directory-api.yml
  format: yaml
  label: Admin SDK Directory API
  slug: admin-directory
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-workspace/refs/heads/main/openapi/admin-sdk-directory-api.yml
class_count: 0
classes: []
context_file: json-ld/google-workspace-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-workspace/refs/heads/main/json-ld/google-workspace-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Workspace from Google Workspace.
layout: jsonld
name: Google Workspace Context
namespaces:
- prefix: gws
  uri: https://developers.google.com/admin-sdk/directory/reference/rest/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: OrgUnit
  type: ''
property_count: 3
provider_name: Google Workspace
provider_slug: google-workspace
slug: google-workspace-context
source_filename: google-workspace-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"gws\": \"https://developers.google.com/admin-sdk/directory/reference/rest/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"User\": {\n      \"@id\": \"gws:users#User\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryEmail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"@id\",\n          \"@context\": {\n            \"givenName\": {\n              \"@id\": \"schema:givenName\",\n              \"@type\": \"xsd:string\"\n            },\n      \
  \      \"familyName\": {\n              \"@id\": \"schema:familyName\",\n              \"@type\": \"xsd:string\"\n            },\n            \"fullName\": {\n              \"@id\": \"foaf:name\",\n              \"@type\": \"xsd:string\"\n            },\n            \"displayName\": {\n              \"@id\": \"schema:alternateName\",\n              \"@type\": \"xsd:string\"\n            }\n          }\n        },\n        \"isAdmin\": {\n          \"@id\": \"gws:users#isAdmin\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isDelegatedAdmin\": {\n          \"@id\": \"gws:users#isDelegatedAdmin\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"lastLoginTime\": {\n          \"@id\": \"schema:lastReviewed\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"suspended\": {\n          \"@id\": \"gws:users#suspended\",\n          \"\
  @type\": \"xsd:boolean\"\n        },\n        \"archived\": {\n          \"@id\": \"gws:users#archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"orgUnitPath\": {\n          \"@id\": \"org:unitOf\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customerId\": {\n          \"@id\": \"gws:users#customerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recoveryEmail\": {\n          \"@id\": \"gws:users#recoveryEmail\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recoveryPhone\": {\n          \"@id\": \"gws:users#recoveryPhone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"thumbnailPhotoUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"includeInGlobalAddressList\": {\n          \"@id\": \"gws:users#includeInGlobalAddressList\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isEnrolledIn2Sv\": {\n          \"@id\": \"gws:users#isEnrolledIn2Sv\",\n\
  \          \"@type\": \"xsd:boolean\"\n        },\n        \"isEnforcedIn2Sv\": {\n          \"@id\": \"gws:users#isEnforcedIn2Sv\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"emails\": {\n          \"@id\": \"schema:contactPoint\",\n          \"@container\": \"@set\",\n          \"@context\": {\n            \"address\": {\n              \"@id\": \"schema:email\",\n              \"@type\": \"xsd:string\"\n            },\n            \"type\": {\n              \"@id\": \"schema:contactType\",\n              \"@type\": \"xsd:string\"\n            },\n            \"primary\": {\n              \"@id\": \"gws:users#primary\",\n              \"@type\": \"xsd:boolean\"\n            }\n          }\n        },\n        \"phones\": {\n          \"@id\": \"schema:telephone\",\n          \"@container\": \"@set\",\n          \"@context\": {\n            \"value\": {\n              \"@id\": \"schema:telephone\",\n              \"@type\": \"xsd:string\"\n            },\n           \
  \ \"type\": {\n              \"@id\": \"schema:contactType\",\n              \"@type\": \"xsd:string\"\n            },\n            \"primary\": {\n              \"@id\": \"gws:users#primary\",\n              \"@type\": \"xsd:boolean\"\n            }\n          }\n        },\n        \"addresses\": {\n          \"@id\": \"schema:address\",\n          \"@container\": \"@set\",\n          \"@context\": {\n            \"streetAddress\": {\n              \"@id\": \"schema:streetAddress\",\n              \"@type\": \"xsd:string\"\n            },\n            \"locality\": {\n              \"@id\": \"schema:addressLocality\",\n              \"@type\": \"xsd:string\"\n            },\n            \"region\": {\n              \"@id\": \"schema:addressRegion\",\n              \"@type\": \"xsd:string\"\n            },\n            \"postalCode\": {\n              \"@id\": \"schema:postalCode\",\n              \"@type\": \"xsd:string\"\n            },\n            \"country\": {\n              \"\
  @id\": \"schema:addressCountry\",\n              \"@type\": \"xsd:string\"\n            },\n            \"countryCode\": {\n              \"@id\": \"vcard:country-name\",\n              \"@type\": \"xsd:string\"\n            },\n            \"formatted\": {\n              \"@id\": \"vcard:label\",\n              \"@type\": \"xsd:string\"\n            },\n            \"type\": {\n              \"@id\": \"schema:contactType\",\n              \"@type\": \"xsd:string\"\n            },\n            \"primary\": {\n              \"@id\": \"gws:users#primary\",\n              \"@type\": \"xsd:boolean\"\n            }\n          }\n        },\n        \"organizations\": {\n          \"@id\": \"schema:worksFor\",\n          \"@container\": \"@set\",\n          \"@context\": {\n            \"name\": {\n              \"@id\": \"schema:name\",\n              \"@type\": \"xsd:string\"\n            },\n            \"title\": {\n              \"@id\": \"schema:jobTitle\",\n              \"@type\": \"\
  xsd:string\"\n            },\n            \"department\": {\n              \"@id\": \"schema:department\",\n              \"@type\": \"xsd:string\"\n            },\n            \"description\": {\n              \"@id\": \"schema:description\",\n              \"@type\": \"xsd:string\"\n            },\n            \"location\": {\n              \"@id\": \"schema:location\",\n              \"@type\": \"xsd:string\"\n            },\n            \"domain\": {\n              \"@id\": \"schema:url\",\n              \"@type\": \"xsd:string\"\n            },\n            \"primary\": {\n              \"@id\": \"gws:users#primary\",\n              \"@type\": \"xsd:boolean\"\n            }\n          }\n        },\n        \"languages\": {\n          \"@id\": \"schema:knowsLanguage\",\n          \"@container\": \"@set\",\n          \"@context\": {\n            \"languageCode\": {\n              \"@id\": \"schema:inLanguage\",\n              \"@type\": \"xsd:string\"\n            }\n          }\n\
  \        },\n        \"gender\": {\n          \"@id\": \"schema:gender\",\n          \"@context\": {\n            \"type\": {\n              \"@id\": \"schema:GenderType\",\n              \"@type\": \"xsd:string\"\n            }\n          }\n        },\n        \"websites\": {\n          \"@id\": \"schema:url\",\n          \"@container\": \"@set\",\n          \"@context\": {\n            \"value\": {\n              \"@id\": \"schema:url\",\n              \"@type\": \"@id\"\n            },\n            \"type\": {\n              \"@id\": \"schema:additionalType\",\n              \"@type\": \"xsd:string\"\n            },\n            \"primary\": {\n              \"@id\": \"gws:users#primary\",\n              \"@type\": \"xsd:boolean\"\n            }\n          }\n        },\n        \"locations\": {\n          \"@id\": \"schema:workLocation\",\n          \"@container\": \"@set\",\n          \"@context\": {\n            \"area\": {\n              \"@id\": \"schema:description\",\n     \
  \         \"@type\": \"xsd:string\"\n            },\n            \"buildingId\": {\n              \"@id\": \"gws:users#buildingId\",\n              \"@type\": \"xsd:string\"\n            },\n            \"floorName\": {\n              \"@id\": \"gws:users#floorName\",\n              \"@type\": \"xsd:string\"\n            },\n            \"floorSection\": {\n              \"@id\": \"gws:users#floorSection\",\n              \"@type\": \"xsd:string\"\n            },\n            \"deskCode\": {\n              \"@id\": \"gws:users#deskCode\",\n              \"@type\": \"xsd:string\"\n            }\n          }\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"gws:groups#Group\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"adminCreated\": {\n          \"@id\": \"gws:groups#adminCreated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"directMembersCount\": {\n          \"@id\": \"schema:memberCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"aliases\": {\n          \"@id\": \"schema:alternateName\",\n          \"@container\": \"@set\"\n        },\n        \"nonEditableAliases\": {\n          \"@id\": \"gws:groups#nonEditableAliases\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"OrgUnit\": {\n      \"@id\": \"gws:orgunits#OrgUnit\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"orgUnitPath\": {\n          \"@id\": \"gws:orgunits#orgUnitPath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orgUnitId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentOrgUnitPath\": {\n          \"@id\": \"org:subOrganizationOf\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentOrgUnitId\": {\n          \"@id\": \"gws:orgunits#parentOrgUnitId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-workspace/refs/heads/main/json-ld/google-workspace-context.jsonld
tags:
- Calendar
- Collaboration
- Email
- Productivity
- Storage
- Video Conferencing
- JSON-LD
- Linked Data
- Semantic Web
---

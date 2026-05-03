---
api_specs:
- filename: zitadel-management-openapi.yml
  format: yaml
  label: Zitadel Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/openapi/zitadel-management-openapi.yml
class_count: 6
classes:
- User
- HumanUser
- MachineUser
- Organization
- Project
- Application
context_file: json-ld/zitadel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/json-ld/zitadel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zitadel from Zitadel.
layout: jsonld
name: Zitadel Context
namespaces:
- prefix: zitadel
  uri: https://zitadel.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: userName
  type: string
- container: ''
  name: state
  type: string
- container: list
  name: loginNames
  type: ''
- container: ''
  name: preferredLoginName
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: primaryDomain
  type: string
- container: ''
  name: appType
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: preferredLanguage
  type: string
- container: ''
  name: gender
  type: string
property_count: 15
provider_name: Zitadel
provider_slug: zitadel
slug: zitadel-context
source_filename: zitadel-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zitadel\": \"https://zitadel.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"User\": \"zitadel:User\",\n    \"HumanUser\": \"zitadel:HumanUser\",\n    \"MachineUser\": \"zitadel:MachineUser\",\n    \"Organization\": \"zitadel:Organization\",\n    \"Project\": \"zitadel:Project\",\n    \"Application\": \"zitadel:Application\",\n    \"id\": {\"@id\": \"zitadel:id\", \"@type\": \"xsd:string\"},\n    \"userName\": {\"@id\": \"zitadel:userName\", \"@type\": \"xsd:string\"},\n    \"state\": {\"@id\": \"zitadel:state\", \"@type\": \"xsd:string\"},\n    \"loginNames\": {\"@id\": \"zitadel:loginNames\", \"@container\": \"@list\"},\n    \"preferredLoginName\": {\"@id\": \"zitadel:preferredLoginName\", \"@type\": \"xsd:string\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"primaryDomain\": {\"@id\": \"zitadel:primaryDomain\", \"@type\"\
  : \"xsd:string\"},\n    \"appType\": {\"@id\": \"zitadel:appType\", \"@type\": \"xsd:string\"},\n    \"firstName\": {\"@id\": \"schema:givenName\", \"@type\": \"xsd:string\"},\n    \"lastName\": {\"@id\": \"schema:familyName\", \"@type\": \"xsd:string\"},\n    \"displayName\": {\"@id\": \"zitadel:displayName\", \"@type\": \"xsd:string\"},\n    \"email\": {\"@id\": \"schema:email\", \"@type\": \"xsd:string\"},\n    \"phone\": {\"@id\": \"schema:telephone\", \"@type\": \"xsd:string\"},\n    \"preferredLanguage\": {\"@id\": \"zitadel:preferredLanguage\", \"@type\": \"xsd:string\"},\n    \"gender\": {\"@id\": \"schema:gender\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/json-ld/zitadel-context.jsonld
tags:
- Authentication
- Authorization
- Identity Management
- Open Source
- OAuth 2.0
- OIDC
- JSON-LD
- Linked Data
- Semantic Web
---

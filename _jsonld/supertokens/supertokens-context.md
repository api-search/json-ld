---
api_specs:
- filename: supertokens-core-driver-interface-openapi.yml
  format: yaml
  label: SuperTokens Core Driver Interface
  slug: core-driver-interface
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/openapi/supertokens-core-driver-interface-openapi.yml
class_count: 7
classes:
- Session
- User
- Tenant
- Role
- SoftwareApplication
- codeRepository
- programmingLanguage
context_file: json-ld/supertokens-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/json-ld/supertokens-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Supertokens from SuperTokens.
layout: jsonld
name: Supertokens Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
properties:
- container: ''
  name: handle
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: timeJoined
  type: long
- container: ''
  name: tenantId
  type: string
- container: ''
  name: recipeUserId
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: permissions
  type: string
- container: ''
  name: expiry
  type: long
- container: ''
  name: isVerified
  type: boolean
property_count: 11
provider_name: SuperTokens
provider_slug: supertokens
slug: supertokens-context
source_filename: supertokens-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://supertokens.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n    \"Session\": \"supertokens:Session\",\n    \"User\": \"schema:Person\",\n    \"Tenant\": \"supertokens:Tenant\",\n    \"Role\": \"supertokens:Role\",\n    \"handle\": {\n      \"@id\": \"supertokens:sessionHandle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeJoined\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:long\"\n    },\n    \"tenantId\": {\n      \"@id\": \"supertokens:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  recipeUserId\": {\n      \"@id\": \"supertokens:recipeUserId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"schema:roleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permissions\": {\n      \"@id\": \"schema:permissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiry\": {\n      \"@id\": \"supertokens:tokenExpiry\",\n      \"@type\": \"xsd:long\"\n    },\n    \"isVerified\": {\n      \"@id\": \"schema:isVerified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"codeRepository\": \"schema:codeRepository\",\n    \"programmingLanguage\": \"schema:programmingLanguage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/json-ld/supertokens-context.jsonld
tags:
- Authentication
- Open Source
- Session Management
- Social Login
- Passwordless
- Identity
- Authorization
- Multi-Tenancy
- Node.js
- Self-Hosted
- JSON-LD
- Linked Data
- Semantic Web
---

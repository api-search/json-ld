---
api_specs:
- filename: stytch-consumer-openapi.yml
  format: yaml
  label: Stytch Consumer Authentication API
  slug: stytch-consumer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/openapi/stytch-consumer-openapi.yml
- filename: stytch-b2b-openapi.yml
  format: yaml
  label: Stytch B2B Authentication API
  slug: stytch-b2b-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/openapi/stytch-b2b-openapi.yml
class_count: 6
classes:
- name
- description
- email
- identifier
- Person
- Organization
context_file: json-ld/stytch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/json-ld/stytch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stytch from Stytch.
layout: jsonld
name: Stytch Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: stytch
  uri: https://stytch.com/vocab#
properties:
- container: ''
  name: User
  type: schema:Person
- container: ''
  name: Member
  type: schema:Person
- container: ''
  name: B2BOrganization
  type: schema:Organization
- container: ''
  name: Session
  type: ''
- container: ''
  name: AuthenticationFactor
  type: ''
- container: ''
  name: MagicLink
  type: ''
- container: ''
  name: OTP
  type: ''
- container: ''
  name: SSOConnection
  type: ''
- container: ''
  name: userId
  type: schema:identifier
- container: ''
  name: memberId
  type: schema:identifier
- container: ''
  name: organizationId
  type: schema:identifier
- container: ''
  name: sessionToken
  type: ''
- container: ''
  name: sessionJwt
  type: ''
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: expiresAt
  type: schema:DateTime
- container: ''
  name: verifiedEmail
  type: schema:email
- container: ''
  name: passwordless
  type: schema:Boolean
property_count: 17
provider_name: Stytch
provider_slug: stytch
slug: stytch-context
source_filename: stytch-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"stytch\": \"https://stytch.com/vocab#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"identifier\": \"schema:identifier\",\n    \"Person\": \"schema:Person\",\n    \"Organization\": \"schema:Organization\",\n    \"User\": {\n      \"@id\": \"stytch:User\",\n      \"@type\": \"schema:Person\"\n    },\n    \"Member\": {\n      \"@id\": \"stytch:Member\",\n      \"@type\": \"schema:Person\"\n    },\n    \"B2BOrganization\": {\n      \"@id\": \"stytch:Organization\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"Session\": {\n      \"@id\": \"stytch:Session\"\n    },\n    \"AuthenticationFactor\": {\n      \"@id\": \"stytch:AuthenticationFactor\"\n    },\n    \"MagicLink\": {\n      \"@id\": \"stytch:MagicLink\"\n    },\n    \"OTP\": {\n      \"@id\": \"stytch:OTP\"\n    },\n    \"SSOConnection\": {\n\
  \      \"@id\": \"stytch:SSOConnection\"\n    },\n    \"userId\": {\n      \"@id\": \"stytch:userId\",\n      \"@type\": \"schema:identifier\"\n    },\n    \"memberId\": {\n      \"@id\": \"stytch:memberId\",\n      \"@type\": \"schema:identifier\"\n    },\n    \"organizationId\": {\n      \"@id\": \"stytch:organizationId\",\n      \"@type\": \"schema:identifier\"\n    },\n    \"sessionToken\": {\n      \"@id\": \"stytch:sessionToken\"\n    },\n    \"sessionJwt\": {\n      \"@id\": \"stytch:sessionJwt\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"stytch:expiresAt\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"verifiedEmail\": {\n      \"@id\": \"stytch:verifiedEmail\",\n      \"@type\": \"schema:email\"\n    },\n    \"passwordless\": {\n      \"@id\": \"stytch:passwordless\",\n      \"@type\": \"schema:Boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stytch/refs/heads/main/json-ld/stytch-context.jsonld
tags:
- Authentication
- Identity
- Passwordless
- Security
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: oauth-token-endpoint.yml
  format: yaml
  label: OAuth 2.0 Authorization Server API
  slug: oauth-2-authorization-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/openapi/oauth-token-endpoint.yml
class_count: 4
classes:
- name
- description
- url
- identifier
context_file: json-ld/oauth-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/json-ld/oauth-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oauth from OAuth.
layout: jsonld
name: Oauth Context
namespaces:
- prefix: oauth
  uri: https://www.w3.org/ns/oauth#
- prefix: schema
  uri: https://schema.org/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: AuthorizationServer
  type: reference
- container: ''
  name: ResourceServer
  type: reference
- container: ''
  name: Client
  type: reference
- container: ''
  name: AccessToken
  type: reference
- container: ''
  name: RefreshToken
  type: reference
- container: ''
  name: AuthorizationCode
  type: reference
- container: ''
  name: Grant
  type: reference
- container: ''
  name: Scope
  type: reference
- container: ''
  name: accessToken
  type: string
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: scope
  type: string
- container: ''
  name: grantType
  type: string
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: redirectUri
  type: reference
- container: ''
  name: authorizationEndpoint
  type: reference
- container: ''
  name: tokenEndpoint
  type: reference
- container: ''
  name: revocationEndpoint
  type: reference
- container: ''
  name: responseType
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: codeChallenge
  type: string
- container: ''
  name: codeChallengeMethod
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: errorDescription
  type: string
- container: ''
  name: errorUri
  type: reference
- container: ''
  name: issued
  type: date
property_count: 28
provider_name: OAuth
provider_slug: oauth
slug: oauth-context
source_filename: oauth-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oauth\": \"https://www.w3.org/ns/oauth#\",\n    \"schema\": \"https://schema.org/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"AuthorizationServer\": {\n      \"@id\": \"oauth:AuthorizationServer\",\n      \"@type\": \"@id\"\n    },\n    \"ResourceServer\": {\n      \"@id\": \"oauth:ResourceServer\",\n      \"@type\": \"@id\"\n    },\n    \"Client\": {\n      \"@id\": \"oauth:Client\",\n      \"@type\": \"@id\"\n    },\n    \"AccessToken\": {\n      \"@id\": \"oauth:AccessToken\",\n      \"@type\": \"@id\"\n    },\n    \"RefreshToken\": {\n      \"@id\": \"oauth:RefreshToken\",\n      \"@type\": \"@id\"\n    },\n    \"AuthorizationCode\": {\n      \"@id\": \"oauth:AuthorizationCode\",\n      \"@type\": \"@id\"\n    },\n    \"Grant\": {\n      \"@id\": \"oauth:Grant\",\n      \"@type\": \"@id\"\n    },\n    \"Scope\"\
  : {\n      \"@id\": \"oauth:Scope\",\n      \"@type\": \"@id\"\n    },\n    \"accessToken\": {\n      \"@id\": \"oauth:accessToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refreshToken\": {\n      \"@id\": \"oauth:refreshToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"oauth:tokenType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"oauth:expiresIn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scope\": {\n      \"@id\": \"oauth:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grantType\": {\n      \"@id\": \"oauth:grantType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"oauth:clientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"sec:clientSecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectUri\": {\n      \"@id\": \"oauth:redirectUri\",\n      \"@type\": \"@id\"\n    },\n    \"authorizationEndpoint\"\
  : {\n      \"@id\": \"oauth:authorizationEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"tokenEndpoint\": {\n      \"@id\": \"oauth:tokenEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"revocationEndpoint\": {\n      \"@id\": \"oauth:revocationEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"responseType\": {\n      \"@id\": \"oauth:responseType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"oauth:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeChallenge\": {\n      \"@id\": \"oauth:codeChallenge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeChallengeMethod\": {\n      \"@id\": \"oauth:codeChallengeMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"oauth:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorDescription\": {\n      \"@id\": \"oauth:errorDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorUri\": {\n      \"@id\": \"oauth:errorUri\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"dcterms:identifier\",\n    \"issued\": {\n      \"@id\": \"dcterms:issued\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oauth/refs/heads/main/json-ld/oauth-context.jsonld
tags:
- Access Control
- Authorization
- OAuth
- Security
- Tokens
- JSON-LD
- Linked Data
- Semantic Web
---

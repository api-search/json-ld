---
api_specs:
- filename: spring-security-oauth2-openapi.yml
  format: yaml
  label: Spring Security OAuth2 API
  slug: spring-security-oauth2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-security/refs/heads/main/openapi/spring-security-oauth2-openapi.yml
- filename: spring-authorization-server-openapi.yml
  format: yaml
  label: Spring Authorization Server API
  slug: spring-authorization-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-security/refs/heads/main/openapi/spring-authorization-server-openapi.yml
class_count: 5
classes:
- name
- description
- url
- Person
- email
context_file: json-ld/spring-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spring-security/refs/heads/main/json-ld/spring-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spring Security from Spring Security.
layout: jsonld
name: Spring Security Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: oauth
  uri: https://www.iana.org/assignments/oauth-parameters/vocab/
- prefix: springsec
  uri: https://spring.io/projects/spring-security/vocab/
properties:
- container: ''
  name: OAuthToken
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
  name: OidcToken
  type: reference
- container: ''
  name: access_token
  type: ''
- container: ''
  name: token_type
  type: ''
- container: ''
  name: expires_in
  type: ''
- container: ''
  name: refresh_token
  type: ''
- container: ''
  name: scope
  type: ''
- container: ''
  name: id_token
  type: ''
- container: ''
  name: sub
  type: ''
- container: ''
  name: iss
  type: ''
- container: ''
  name: aud
  type: ''
- container: ''
  name: exp
  type: ''
- container: ''
  name: iat
  type: ''
- container: ''
  name: jti
  type: ''
- container: ''
  name: client_id
  type: ''
- container: ''
  name: redirect_uri
  type: ''
- container: ''
  name: grant_type
  type: ''
- container: ''
  name: response_type
  type: ''
- container: ''
  name: code_challenge
  type: ''
- container: ''
  name: code_verifier
  type: ''
property_count: 23
provider_name: Spring Security
provider_slug: spring-security
slug: spring-security-context
source_filename: spring-security-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"oauth\": \"https://www.iana.org/assignments/oauth-parameters/vocab/\",\n    \"springsec\": \"https://spring.io/projects/spring-security/vocab/\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n\n    \"Person\": \"schema:Person\",\n    \"email\": \"schema:email\",\n\n    \"OAuthToken\": {\n      \"@id\": \"oauth:Token\",\n      \"@type\": \"@id\"\n    },\n    \"AccessToken\": {\n      \"@id\": \"oauth:AccessToken\",\n      \"@type\": \"@id\"\n    },\n    \"RefreshToken\": {\n      \"@id\": \"oauth:RefreshToken\",\n      \"@type\": \"@id\"\n    },\n    \"AuthorizationCode\": {\n      \"@id\": \"oauth:AuthorizationCode\",\n      \"@type\": \"@id\"\n    },\n    \"OidcToken\": {\n      \"@id\": \"springsec:OidcToken\",\n      \"@type\": \"@id\"\n    },\n\n    \"access_token\": {\
  \ \"@id\": \"oauth:access_token\" },\n    \"token_type\": { \"@id\": \"oauth:token_type\" },\n    \"expires_in\": { \"@id\": \"oauth:expires_in\" },\n    \"refresh_token\": { \"@id\": \"oauth:refresh_token\" },\n    \"scope\": { \"@id\": \"oauth:scope\" },\n    \"id_token\": { \"@id\": \"springsec:id_token\" },\n\n    \"sub\": { \"@id\": \"springsec:subject\" },\n    \"iss\": { \"@id\": \"springsec:issuer\" },\n    \"aud\": { \"@id\": \"springsec:audience\" },\n    \"exp\": { \"@id\": \"springsec:expirationTime\" },\n    \"iat\": { \"@id\": \"springsec:issuedAt\" },\n    \"jti\": { \"@id\": \"springsec:jwtId\" },\n\n    \"client_id\": { \"@id\": \"oauth:client_id\" },\n    \"redirect_uri\": { \"@id\": \"oauth:redirect_uri\" },\n    \"grant_type\": { \"@id\": \"oauth:grant_type\" },\n    \"response_type\": { \"@id\": \"oauth:response_type\" },\n    \"code_challenge\": { \"@id\": \"oauth:code_challenge\" },\n    \"code_verifier\": { \"@id\": \"oauth:code_verifier\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spring-security/refs/heads/main/json-ld/spring-security-context.jsonld
tags:
- Authentication
- Authorization
- Java
- JWT
- OAuth2
- OpenID Connect
- SAML
- Security
- Spring Framework
- JSON-LD
- Linked Data
- Semantic Web
---

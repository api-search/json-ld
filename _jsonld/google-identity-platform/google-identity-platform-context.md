---
api_specs:
- filename: identity-toolkit-openapi.yml
  format: yaml
  label: Identity Toolkit API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/openapi/identity-toolkit-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-identity-platform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/json-ld/google-identity-platform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Identity Platform from Google Identity Platform.
layout: jsonld
name: Google Identity Platform Context
namespaces:
- prefix: idp
  uri: https://cloud.google.com/identity-platform/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Tenant
  type: ''
- container: ''
  name: ProviderConfig
  type: ''
property_count: 3
provider_name: Google Identity Platform
provider_slug: google-identity-platform
slug: google-identity-platform-context
source_filename: google-identity-platform-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"idp\": \"https://cloud.google.com/identity-platform/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"User\": {\n      \"@id\": \"idp:User\",\n      \"@context\": {\n        \"localId\": \"idp:localId\",\n        \"email\": \"schema:email\",\n        \"displayName\": \"schema:name\",\n        \"photoUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"phoneNumber\": \"schema:telephone\",\n        \"emailVerified\": \"idp:emailVerified\",\n        \"disabled\": \"idp:disabled\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastLoginAt\": {\n          \"@id\": \"idp:lastLoginAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Tenant\": {\n      \"@id\": \"idp:Tenant\"\
  ,\n      \"@context\": {\n        \"tenantId\": \"idp:tenantId\",\n        \"displayName\": \"schema:name\",\n        \"allowPasswordSignup\": \"idp:allowPasswordSignup\",\n        \"enableEmailLinkSignin\": \"idp:enableEmailLinkSignin\",\n        \"enableAnonymousUser\": \"idp:enableAnonymousUser\"\n      }\n    },\n\n    \"ProviderConfig\": {\n      \"@id\": \"idp:ProviderConfig\",\n      \"@context\": {\n        \"providerId\": \"idp:providerId\",\n        \"displayName\": \"schema:name\",\n        \"enabled\": \"idp:enabled\",\n        \"clientId\": \"idp:clientId\",\n        \"issuer\": {\n          \"@id\": \"idp:issuer\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-identity-platform/refs/heads/main/json-ld/google-identity-platform-context.jsonld
tags:
- Authentication
- Google Cloud
- Identity
- Multi-Tenancy
- OAuth
- OpenID Connect
- SAML
- JSON-LD
- Linked Data
- Semantic Web
---

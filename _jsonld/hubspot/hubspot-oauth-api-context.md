---
class_count: 4
classes:
- AccessTokenMetadata
- RefreshTokenMetadata
- TokenRequest
- TokenResponse
context_file: json-ld/hubspot-oauth-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-oauth-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Oauth Api from HubSpot.
layout: jsonld
name: Hubspot Oauth Api Context
namespaces:
- prefix: hubspot
  uri: https://developers.hubspot.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: token
  type: string
- container: ''
  name: appId
  type: integer
- container: ''
  name: hubId
  type: integer
- container: ''
  name: userId
  type: integer
- container: ''
  name: user
  type: string
- container: ''
  name: hubDomain
  type: string
- container: set
  name: scopes
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: expiresIn
  type: integer
- container: ''
  name: clientId
  type: string
- container: ''
  name: grantType
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: redirectUri
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: refreshToken
  type: string
- container: ''
  name: accessToken
  type: string
- container: ''
  name: idToken
  type: string
property_count: 17
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-oauth-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessTokenMetadata\": \"hubspot:AccessTokenMetadata\",\n    \"token\": {\n      \"@id\": \"hubspot:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appId\": {\n      \"@id\": \"hubspot:app_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hubId\": {\n      \"@id\": \"hubspot:hub_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"userId\": {\n      \"@id\": \"hubspot:user_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"user\": {\n      \"@id\": \"hubspot:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hubDomain\": {\n      \"@id\": \"hubspot:hub_domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scopes\": {\n      \"@id\": \"hubspot:scopes\",\n      \"@container\": \"@set\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"hubspot:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"hubspot:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"RefreshTokenMetadata\": \"hubspot:RefreshTokenMetadata\",\n    \"clientId\": {\n      \"@id\": \"hubspot:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TokenRequest\": \"hubspot:TokenRequest\",\n    \"grantType\": {\n      \"@id\": \"hubspot:grant_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"hubspot:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectUri\": {\n      \"@id\": \"hubspot:redirect_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"hubspot:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refreshToken\": {\n      \"@id\": \"hubspot:refresh_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TokenResponse\"\
  : \"hubspot:TokenResponse\",\n    \"accessToken\": {\n      \"@id\": \"hubspot:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idToken\": {\n      \"@id\": \"hubspot:id_token\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-oauth-api-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---

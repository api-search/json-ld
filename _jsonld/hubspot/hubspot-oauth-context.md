---
class_count: 0
classes: []
context_file: json-ld/hubspot-oauth-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-oauth-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Oauth from HubSpot.
layout: jsonld
name: Hubspot Oauth Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: AccessTokenMetadata
  type: ''
- container: ''
  name: RefreshTokenMetadata
  type: ''
- container: ''
  name: TokenRequest
  type: ''
- container: ''
  name: TokenResponse
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 6
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-oauth-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"AccessTokenMetadata\": {\n      \"@id\": \"ns:AccessTokenMetadata\",\n      \"@context\": {\n        \"token\": {\n          \"@id\": \"ns:token\",\n          \"@type\": \"xsd:string\"\n        },\n        \"app_id\": {\n          \"@id\": \"ns:app_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"hub_id\": {\n          \"@id\": \"ns:hub_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"user_id\": {\n          \"@id\": \"ns:user_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"user\": {\n          \"@id\": \"ns:user\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hub_domain\": {\n          \"@id\": \"ns:hub_domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scopes\": \"ns:scopes\",\n        \"token_type\": {\n          \"@id\": \"ns:token_type\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"expires_in\": {\n          \"@id\": \"ns:expires_in\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"RefreshTokenMetadata\": {\n      \"@id\": \"ns:RefreshTokenMetadata\",\n      \"@context\": {\n        \"token\": {\n          \"@id\": \"ns:token\",\n          \"@type\": \"xsd:string\"\n        },\n        \"client_id\": {\n          \"@id\": \"ns:client_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hub_id\": {\n          \"@id\": \"ns:hub_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"user_id\": {\n          \"@id\": \"ns:user_id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"user\": {\n          \"@id\": \"ns:user\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scopes\": \"ns:scopes\"\n      }\n    },\n    \"TokenRequest\": {\n      \"@id\": \"ns:TokenRequest\",\n      \"@context\": {\n        \"grant_type\": {\n          \"\
  @id\": \"ns:grant_type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"client_id\": {\n          \"@id\": \"ns:client_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"client_secret\": {\n          \"@id\": \"ns:client_secret\",\n          \"@type\": \"xsd:string\"\n        },\n        \"redirect_uri\": {\n          \"@id\": \"ns:redirect_uri\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"refresh_token\": {\n          \"@id\": \"ns:refresh_token\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"TokenResponse\": {\n      \"@id\": \"ns:TokenResponse\",\n      \"@context\": {\n        \"access_token\": {\n          \"@id\": \"ns:access_token\",\n          \"@type\": \"xsd:string\"\n        },\n        \"token_type\": {\n          \"@id\": \"ns:token_type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  expires_in\": {\n          \"@id\": \"ns:expires_in\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"refresh_token\": {\n          \"@id\": \"ns:refresh_token\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id_token\": {\n          \"@id\": \"ns:id_token\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n\
  \    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-oauth-context.jsonld
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

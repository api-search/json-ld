---
api_specs:
- filename: strapi-rest-api-openapi.yml
  format: yaml
  label: Strapi REST API
  slug: strapi-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-rest-api-openapi.yml
- filename: strapi-admin-panel-api-openapi.yml
  format: yaml
  label: Strapi Admin Panel API
  slug: strapi-admin-panel-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-admin-panel-api-openapi.yml
- filename: strapi-users-and-permissions-api-openapi.yml
  format: yaml
  label: Strapi Users and Permissions API
  slug: strapi-users-permissions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/openapi/strapi-users-and-permissions-api-openapi.yml
- filename: strapi-webhooks-asyncapi.yml
  format: yaml
  label: Strapi Webhooks
  slug: strapi-webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/asyncapi/strapi-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/strapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/json-ld/strapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Strapi from Strapi.
layout: jsonld
name: Strapi Context
namespaces:
- prefix: strapi
  uri: https://strapi.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ContentEntry
  type: ''
- container: ''
  name: ContentType
  type: ''
- container: ''
  name: MediaFile
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: AdminUser
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: ApiToken
  type: ''
property_count: 8
provider_name: Strapi
provider_slug: strapi
slug: strapi-context
source_filename: strapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"strapi\": \"https://strapi.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ContentEntry\": {\n      \"@id\": \"strapi:ContentEntry\",\n      \"@context\": {\n        \"documentId\": \"strapi:documentId\",\n        \"locale\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"localizations\": {\n          \"@id\": \"strapi:localizations\",\n          \"@container\": \"@set\"\n        }\n      }\n  \
  \  },\n\n    \"ContentType\": {\n      \"@id\": \"strapi:ContentType\",\n      \"@context\": {\n        \"uid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"singularName\": \"strapi:singularName\",\n        \"pluralName\": \"strapi:pluralName\",\n        \"kind\": \"strapi:kind\",\n        \"attributes\": {\n          \"@id\": \"strapi:attributes\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"MediaFile\": {\n      \"@id\": \"strapi:MediaFile\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alternativeText\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"caption\": {\n          \"@id\": \"schema:caption\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"width\": {\n          \"@id\": \"schema:width\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"height\": {\n          \"@id\": \"schema:height\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"mime\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:float\"\n        },\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"strapi:User\",\n      \"@context\": {\n        \"username\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"confirmed\": {\n          \"@id\": \"strapi:confirmed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"blocked\": {\n          \"@id\": \"strapi:blocked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"provider\": {\n          \"@id\": \"strapi:authProvider\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\": {\n          \"@id\": \"strapi:role\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AdminUser\": {\n      \"@id\": \"strapi:AdminUser\",\n      \"@context\": {\n        \"firstname\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"lastname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isActive\": {\n          \"@id\": \"strapi:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"roles\": {\n          \"@id\": \"strapi:roles\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"strapi:Role\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"type\": {\n          \"@id\": \"strapi:roleType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"permissions\": {\n          \"@id\": \"strapi:permissions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"strapi:Webhook\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"strapi:webhookUrl\",\n          \"@type\": \"@id\"\n        },\n        \"events\": {\n          \"@id\": \"strapi:webhookEvents\",\n          \"@container\": \"@set\"\n        },\n        \"isEnabled\": {\n          \"@id\": \"strapi:isEnabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ApiToken\": {\n      \"@id\": \"strapi:ApiToken\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n    \
  \    \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"strapi:tokenType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastUsedAt\": {\n          \"@id\": \"strapi:lastUsedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"strapi:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/strapi/refs/heads/main/json-ld/strapi-context.jsonld
tags:
- CMS
- Content Management
- Headless CMS
- Node.js
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---

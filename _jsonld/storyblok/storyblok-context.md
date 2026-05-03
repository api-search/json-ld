---
api_specs:
- filename: storyblok-content-delivery-api-v2-openapi.yml
  format: yaml
  label: Storyblok Content Delivery API
  slug: storyblok-content-delivery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-content-delivery-api-v2-openapi.yml
- filename: storyblok-management-api-openapi.yml
  format: yaml
  label: Storyblok Management API
  slug: storyblok-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-management-api-openapi.yml
- filename: storyblok-image-service-openapi.yml
  format: yaml
  label: Storyblok Image Service
  slug: storyblok-image-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-image-service-openapi.yml
- filename: storyblok-webhooks-asyncapi.yml
  format: yaml
  label: Storyblok Webhooks
  slug: storyblok-webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/asyncapi/storyblok-webhooks-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/storyblok-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/json-ld/storyblok-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Storyblok from Storyblok.
layout: jsonld
name: Storyblok Context
namespaces:
- prefix: storyblok
  uri: https://www.storyblok.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
properties:
- container: ''
  name: Story
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: Component
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Datasource
  type: ''
- container: ''
  name: DatasourceEntry
  type: ''
- container: ''
  name: WebhookEndpoint
  type: ''
- container: ''
  name: Collaborator
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: Link
  type: ''
property_count: 10
provider_name: Storyblok
provider_slug: storyblok
slug: storyblok-context
source_filename: storyblok-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"storyblok\": \"https://www.storyblok.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n\n    \"Story\": {\n      \"@id\": \"storyblok:Story\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"uuid\": {\n          \"@id\": \"storyblok:uuid\",\n          \"@type\": \"@id\"\n        },\n        \"name\": \"schema:name\",\n        \"slug\": \"storyblok:slug\",\n        \"fullSlug\": \"storyblok:fullSlug\",\n        \"content\": \"schema:mainContentOfPage\",\n        \"isStartpage\": \"storyblok:isStartpage\",\n        \"isFolder\": \"storyblok:isFolder\",\n        \"parentId\": \"storyblok:parentId\",\n        \"groupId\": {\n          \"@id\": \"storyblok:groupId\",\n          \"@type\": \"@id\"\n        },\n        \"published\": \"schema:isAccessibleForFree\"\
  ,\n        \"publishedAt\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"firstPublishedAt\": {\n          \"@id\": \"storyblok:firstPublishedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tagList\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"position\": \"schema:position\",\n        \"alternates\": {\n          \"@id\": \"schema:workTranslation\",\n          \"@container\": \"@set\"\n        },\n        \"translatedSlugs\": {\n          \"@id\": \"storyblok:translatedSlugs\",\n          \"@container\": \"@set\"\n        },\n        \"path\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n\
  \        },\n        \"metaData\": \"storyblok:metaData\"\n      }\n    },\n\n    \"Space\": {\n      \"@id\": \"storyblok:Space\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"domain\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"plan\": \"storyblok:plan\",\n        \"planLevel\": \"storyblok:planLevel\",\n        \"defaultLang\": \"storyblok:defaultLang\",\n        \"languages\": {\n          \"@id\": \"schema:availableLanguage\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"storiesCount\": \"storyblok:storiesCount\",\n        \"assetsCount\": \"storyblok:assetsCount\",\n        \"collaboratorsCount\": \"storyblok:collaboratorsCount\"\n      }\n    },\n\n    \"Component\": {\n      \"@id\": \"storyblok:Component\",\n      \"@context\": {\n    \
  \    \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"displayName\": \"storyblok:displayName\",\n        \"isRoot\": \"storyblok:isRoot\",\n        \"isNestable\": \"storyblok:isNestable\",\n        \"schema\": \"storyblok:schema\",\n        \"componentGroupUuid\": {\n          \"@id\": \"storyblok:componentGroupUuid\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"storyblok:Asset\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"filename\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"contentType\": \"schema:encodingFormat\",\n        \"contentLength\": \"schema:contentSize\",\n        \"alt\": \"\
  schema:description\",\n        \"title\": \"schema:name\",\n        \"copyright\": \"dcterms:rights\",\n        \"focus\": \"storyblok:focus\",\n        \"isPrivate\": \"storyblok:isPrivate\",\n        \"assetFolderId\": \"storyblok:assetFolderId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Datasource\": {\n      \"@id\": \"storyblok:Datasource\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"slug\": \"storyblok:slug\",\n        \"dimensions\": {\n          \"@id\": \"storyblok:dimensions\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DatasourceEntry\": {\n      \"@id\": \"storyblok:DatasourceEntry\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"value\": \"schema:value\",\n        \"dimensionValue\": \"storyblok:dimensionValue\"\n      }\n    },\n\n    \"WebhookEndpoint\": {\n      \"@id\": \"storyblok:WebhookEndpoint\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"actions\": {\n          \"@id\": \"storyblok:actions\",\n          \"@container\": \"@set\"\n        },\n        \"description\": \"schema:description\",\n        \"activated\": \"schema:isAccessibleForFree\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n \
  \         \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Collaborator\": {\n      \"@id\": \"storyblok:Collaborator\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"userId\": \"storyblok:userId\",\n        \"role\": \"schema:roleName\",\n        \"invited\": \"storyblok:invited\",\n        \"user\": \"schema:Person\"\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"storyblok:Tag\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"taggingsCount\": \"storyblok:taggingsCount\"\n      }\n    },\n\n    \"Link\": {\n      \"@id\": \"storyblok:Link\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"uuid\": {\n          \"@id\": \"storyblok:uuid\",\n          \"@type\": \"@id\"\n        },\n        \"name\": \"schema:name\",\n        \"slug\": \"storyblok:slug\",\n        \"isFolder\": \"storyblok:isFolder\",\n        \"isStartpage\": \"storyblok:isStartpage\"\
  ,\n        \"parentId\": \"storyblok:parentId\",\n        \"published\": \"schema:isAccessibleForFree\",\n        \"position\": \"schema:position\",\n        \"realPath\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/json-ld/storyblok-context.jsonld
tags:
- CMS
- Content Delivery
- Content Management
- Headless CMS
- Image Optimization
- REST API
- Visual Editor
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---

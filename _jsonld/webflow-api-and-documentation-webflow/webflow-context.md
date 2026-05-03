---
api_specs:
- filename: webflow-data-api-openapi.yml
  format: yaml
  label: Webflow Data API
  slug: data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-data-api-openapi.yml
- filename: webflow-sites-openapi.yml
  format: yaml
  label: Webflow Sites API
  slug: sites-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-sites-openapi.yml
- filename: webflow-collections-openapi.yml
  format: yaml
  label: Webflow Collections API
  slug: collections-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-collections-openapi.yml
- filename: webflow-items-openapi.yml
  format: yaml
  label: Webflow CMS Items API
  slug: items-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-items-openapi.yml
- filename: webflow-webhooks-openapi.yml
  format: yaml
  label: Webflow Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-webhooks-openapi.yml
class_count: 18
classes:
- Site
- Collection
- CollectionItem
- Page
- Product
- Order
- Asset
- displayName
- shortName
- title
- name
- slug
- description
- isDraft
- orderId
- status
- fileSize
- mimeType
context_file: json-ld/webflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/json-ld/webflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Webflow from Webflow API and Documentation.
layout: jsonld
name: Webflow Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: webflow
  uri: https://api.webflow.com/ns#
properties:
- container: ''
  name: createdOn
  type: dateTime
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: lastPublished
  type: dateTime
- container: ''
  name: previewUrl
  type: reference
- container: ''
  name: isArchived
  type: boolean
- container: ''
  name: acceptedOn
  type: dateTime
- container: ''
  name: url
  type: reference
property_count: 7
provider_name: Webflow API and Documentation
provider_slug: webflow-api-and-documentation-webflow
slug: webflow-context
source_filename: webflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"webflow\": \"https://api.webflow.com/ns#\",\n\n    \"Site\": \"schema:WebSite\",\n    \"Collection\": \"schema:DataCatalog\",\n    \"CollectionItem\": \"schema:CreativeWork\",\n    \"Page\": \"schema:WebPage\",\n    \"Product\": \"schema:Product\",\n    \"Order\": \"schema:Order\",\n    \"Asset\": \"schema:MediaObject\",\n\n    \"displayName\": \"schema:name\",\n    \"shortName\": \"schema:alternateName\",\n    \"title\": \"schema:name\",\n    \"name\": \"schema:name\",\n    \"slug\": \"schema:identifier\",\n    \"description\": \"schema:description\",\n\n    \"createdOn\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastPublished\": {\n      \"@id\": \"schema:datePublished\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"previewUrl\": {\n      \"@id\": \"schema:thumbnailUrl\",\n      \"@type\": \"@id\"\n    },\n\n    \"isDraft\": \"schema:creativeWorkStatus\",\n    \"isArchived\": {\n      \"@id\": \"schema:archivedAt\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"orderId\": \"schema:orderNumber\",\n    \"status\": \"schema:orderStatus\",\n    \"acceptedOn\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"url\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"fileSize\": \"schema:contentSize\",\n    \"mimeType\": \"schema:encodingFormat\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/json-ld/webflow-context.jsonld
tags:
- CMS
- Content Management
- Ecommerce
- No-Code
- Publishing
- Web Development
- JSON-LD
- Linked Data
- Semantic Web
---

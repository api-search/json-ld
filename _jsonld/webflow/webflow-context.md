---
api_specs:
- filename: webflow-data-api-openapi.yml
  format: yaml
  label: Webflow Data API
  slug: data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-data-api-openapi.yml
- filename: webflow-meta-openapi.yml
  format: yaml
  label: Webflow Meta API
  slug: meta-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-meta-openapi.yml
- filename: webflow-sites-openapi.yml
  format: yaml
  label: Webflow Sites API
  slug: sites-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-sites-openapi.yml
- filename: webflow-pages-openapi.yml
  format: yaml
  label: Webflow Pages API
  slug: pages-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-pages-openapi.yml
- filename: webflow-collections-openapi.yml
  format: yaml
  label: Webflow Collections API
  slug: collections-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-collections-openapi.yml
- filename: webflow-items-openapi.yml
  format: yaml
  label: Webflow CMS Items API
  slug: items-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-items-openapi.yml
- filename: webflow-components-openapi.yml
  format: yaml
  label: Webflow Components API
  slug: components-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-components-openapi.yml
- filename: webflow-assets-openapi.yml
  format: yaml
  label: Webflow Assets API
  slug: assets-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-assets-openapi.yml
- filename: webflow-forms-openapi.yml
  format: yaml
  label: Webflow Forms API
  slug: forms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-forms-openapi.yml
- filename: webflow-products-openapi.yml
  format: yaml
  label: Webflow Products and SKUs API
  slug: products-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-products-openapi.yml
- filename: webflow-orders-openapi.yml
  format: yaml
  label: Webflow Orders API
  slug: orders-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-orders-openapi.yml
- filename: webflow-inventory-openapi.yml
  format: yaml
  label: Webflow Inventory API
  slug: inventory-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-inventory-openapi.yml
- filename: webflow-ecommerce-settings-openapi.yml
  format: yaml
  label: Webflow Ecommerce Settings API
  slug: ecommerce-settings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-ecommerce-settings-openapi.yml
- filename: webflow-webhooks-openapi.yml
  format: yaml
  label: Webflow Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-webhooks-openapi.yml
- filename: webflow-custom-code-openapi.yml
  format: yaml
  label: Webflow Custom Code API
  slug: custom-code-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-custom-code-openapi.yml
- filename: webflow-comments-openapi.yml
  format: yaml
  label: Webflow Comments API
  slug: comments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/openapi/webflow-comments-openapi.yml
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
context_url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/json-ld/webflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Webflow from Webflow.
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
provider_name: Webflow
provider_slug: webflow
slug: webflow-context
source_filename: webflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"webflow\": \"https://api.webflow.com/ns#\",\n\n    \"Site\": \"schema:WebSite\",\n    \"Collection\": \"schema:DataCatalog\",\n    \"CollectionItem\": \"schema:CreativeWork\",\n    \"Page\": \"schema:WebPage\",\n    \"Product\": \"schema:Product\",\n    \"Order\": \"schema:Order\",\n    \"Asset\": \"schema:MediaObject\",\n\n    \"displayName\": \"schema:name\",\n    \"shortName\": \"schema:alternateName\",\n    \"title\": \"schema:name\",\n    \"name\": \"schema:name\",\n    \"slug\": \"schema:identifier\",\n    \"description\": \"schema:description\",\n\n    \"createdOn\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastPublished\": {\n      \"@id\": \"schema:datePublished\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"previewUrl\": {\n      \"@id\": \"schema:thumbnailUrl\",\n      \"@type\": \"@id\"\n    },\n\n    \"isDraft\": \"schema:creativeWorkStatus\",\n    \"isArchived\": {\n      \"@id\": \"schema:archivedAt\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"orderId\": \"schema:orderNumber\",\n    \"status\": \"schema:orderStatus\",\n    \"acceptedOn\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"url\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"fileSize\": \"schema:contentSize\",\n    \"mimeType\": \"schema:encodingFormat\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/webflow/refs/heads/main/json-ld/webflow-context.jsonld
tags:
- CMS
- Ecommerce
- No-Code
- Web Development
- JSON-LD
- Linked Data
- Semantic Web
---

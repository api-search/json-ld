---
api_specs:
- filename: woocommerce-rest-api-openapi.yml
  format: yaml
  label: WooCommerce REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/openapi/woocommerce-rest-api-openapi.yml
- filename: woocommerce-store-api-openapi.yml
  format: yaml
  label: WooCommerce Store API
  slug: store-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/openapi/woocommerce-store-api-openapi.yml
- filename: woocommerce-webhooks-asyncapi.yml
  format: yaml
  label: WooCommerce Webhook Events
  slug: webhook-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/asyncapi/woocommerce-webhooks-asyncapi.yml
class_count: 3
classes:
- SystemStatus
- name
- version
context_file: json-ld/woocommerce-rest-api-system-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-system-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Woocommerce Rest Api System from WooCommerce.
layout: jsonld
name: Woocommerce Rest Api System Context
namespaces:
- prefix: woo
  uri: https://woocommerce.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: environment
  type: reference
- container: ''
  name: homeUrl
  type: reference
- container: ''
  name: siteUrl
  type: reference
- container: ''
  name: wcVersion
  type: string
- container: ''
  name: wpVersion
  type: string
- container: ''
  name: phpVersion
  type: string
- container: ''
  name: phpMemoryLimit
  type: string
- container: ''
  name: phpMaxUploadSize
  type: string
- container: ''
  name: mysqlVersion
  type: string
- container: ''
  name: logDirectoryWritable
  type: boolean
- container: set
  name: activePlugins
  type: ''
- container: ''
  name: theme
  type: reference
- container: ''
  name: authorUrl
  type: reference
- container: ''
  name: isChildTheme
  type: boolean
property_count: 14
provider_name: WooCommerce
provider_slug: woocommerce
slug: woocommerce-rest-api-system-context
source_filename: woocommerce-rest-api-system-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"woo\": \"https://woocommerce.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SystemStatus\": \"woo:SystemStatus\",\n    \"environment\": {\n      \"@id\": \"woo:environment\",\n      \"@type\": \"@id\"\n    },\n    \"homeUrl\": {\n      \"@id\": \"woo:home_url\",\n      \"@type\": \"@id\"\n    },\n    \"siteUrl\": {\n      \"@id\": \"woo:site_url\",\n      \"@type\": \"@id\"\n    },\n    \"wcVersion\": {\n      \"@id\": \"woo:wc_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wpVersion\": {\n      \"@id\": \"woo:wp_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phpVersion\": {\n      \"@id\": \"woo:php_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phpMemoryLimit\": {\n      \"@id\": \"woo:php_memory_limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phpMaxUploadSize\"\
  : {\n      \"@id\": \"woo:php_max_upload_size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mysqlVersion\": {\n      \"@id\": \"woo:mysql_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logDirectoryWritable\": {\n      \"@id\": \"woo:log_directory_writable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"activePlugins\": {\n      \"@id\": \"woo:active_plugins\",\n      \"@container\": \"@set\"\n    },\n    \"theme\": {\n      \"@id\": \"woo:theme\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"version\": \"schema:version\",\n    \"authorUrl\": {\n      \"@id\": \"woo:author_url\",\n      \"@type\": \"@id\"\n    },\n    \"isChildTheme\": {\n      \"@id\": \"woo:is_child_theme\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/woocommerce/refs/heads/main/json-ld/woocommerce-rest-api-system-context.jsonld
tags:
- eCommerce
- Open Source
- Orders
- Products
- WordPress
- JSON-LD
- Linked Data
- Semantic Web
---

---
api_specs:
- filename: toast-orders-openapi.yaml
  format: yaml
  label: Toast Orders API
  slug: toast-orders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-orders-openapi.yaml
- filename: toast-menus-openapi.yaml
  format: yaml
  label: Toast Menus API
  slug: toast-menus
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-menus-openapi.yaml
- filename: toast-labor-openapi.yaml
  format: yaml
  label: Toast Labor API
  slug: toast-labor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-labor-openapi.yaml
- filename: toast-restaurants-openapi.yaml
  format: yaml
  label: Toast Restaurants API
  slug: toast-restaurants
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-restaurants-openapi.yaml
- filename: toast-stock-openapi.yaml
  format: yaml
  label: Toast Stock API
  slug: toast-stock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-stock-openapi.yaml
- filename: toast-partners-openapi.yaml
  format: yaml
  label: Toast Partners API
  slug: toast-partners
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-partners-openapi.yaml
- filename: toast-authentication-openapi.yaml
  format: yaml
  label: Toast Authentication API
  slug: toast-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-authentication-openapi.yaml
class_count: 2
classes:
- InventorySearchRequest
- MenuItemInventory
context_file: json-ld/toast-stock-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-stock-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toast Stock from Toast.
layout: jsonld
name: Toast Stock Context
namespaces:
- prefix: toast
  uri: https://developer.toasttab.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: guid
  type: string
- container: set
  name: guids
  type: string
- container: ''
  name: itemGuidValidity
  type: string
- container: ''
  name: multiLocationId
  type: string
- container: set
  name: multiLocationIds
  type: string
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: versionId
  type: string
- container: set
  name: versionIds
  type: string
property_count: 9
provider_name: Toast
provider_slug: toast
slug: toast-stock-context
source_filename: toast-stock-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toast\": \"https://developer.toasttab.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InventorySearchRequest\": \"toast:InventorySearchRequest\",\n    \"MenuItemInventory\": \"toast:MenuItemInventory\",\n    \"guid\": {\n      \"@id\": \"toast:guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guids\": {\n      \"@id\": \"toast:guids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemGuidValidity\": {\n      \"@id\": \"toast:itemGuidValidity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multiLocationId\": {\n      \"@id\": \"toast:multiLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multiLocationIds\": {\n      \"@id\": \"toast:multiLocationIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n    \
  \  \"@id\": \"toast:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"status\": {\n      \"@id\": \"toast:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionId\": {\n      \"@id\": \"toast:versionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionIds\": {\n      \"@id\": \"toast:versionIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-stock-context.jsonld
tags:
- Food Service
- Point of Sale
- Restaurants
- Hospitality
- JSON-LD
- Linked Data
- Semantic Web
---

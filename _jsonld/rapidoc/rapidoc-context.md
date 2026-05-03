---
api_specs:
- filename: rapidoc-rapidoc-openapi.yml
  format: yaml
  label: RapiDoc
  slug: rapidoc
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidoc/refs/heads/main/openapi/rapidoc-rapidoc-openapi.yml
class_count: 0
classes: []
context_file: json-ld/rapidoc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rapidoc/refs/heads/main/json-ld/rapidoc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rapidoc from RapiDoc.
layout: jsonld
name: Rapidoc Context
namespaces:
- prefix: rapidoc
  uri: https://rapidocweb.com/api.html#
properties:
- container: ''
  name: RapiDocComponent
  type: ''
- container: ''
  name: Configuration
  type: ''
- container: ''
  name: Authentication
  type: ''
- container: ''
  name: Schema
  type: ''
- container: ''
  name: Slots
  type: ''
- container: ''
  name: Events
  type: ''
property_count: 6
provider_name: RapiDoc
provider_slug: rapidoc
slug: rapidoc-context
source_filename: rapidoc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"rapidoc\": \"https://rapidocweb.com/api.html#\",\n    \"RapiDocComponent\": {\n      \"@id\": \"rapidoc:rapi-doc\",\n      \"@context\": {\n        \"spec-url\": \"https://schema.org/url\",\n        \"heading-text\": \"https://schema.org/name\",\n        \"theme\": \"https://schema.org/cssSelector\",\n        \"render-style\": \"https://schema.org/encodingFormat\",\n        \"layout\": \"https://schema.org/encodingFormat\",\n        \"primary-color\": \"https://schema.org/color\",\n        \"bg-color\": \"https://schema.org/color\",\n        \"text-color\": \"https://schema.org/color\",\n        \"header-color\": \"https://schema.org/color\",\n        \"nav-bg-color\": \"https://schema.org/color\",\n        \"nav-text-color\": \"https://schema.org/color\",\n        \"regular-font\": \"https://schema.org/fontFamily\",\n        \"mono-font\": \"https://schema.org/fontFamily\",\n        \"font-size\": \"https://schema.org/cssSelector\"\
  ,\n        \"sort-tags\": \"https://schema.org/orderQuantity\",\n        \"sort-endpoints-by\": \"https://schema.org/orderQuantity\"\n      }\n    },\n    \"Configuration\": {\n      \"@id\": \"rapidoc:attributes\",\n      \"@context\": {\n        \"show-info\": \"https://schema.org/actionOption\",\n        \"show-header\": \"https://schema.org/actionOption\",\n        \"show-components\": \"https://schema.org/actionOption\",\n        \"allow-try\": \"https://schema.org/actionOption\",\n        \"allow-authentication\": \"https://schema.org/actionOption\",\n        \"allow-search\": \"https://schema.org/actionOption\",\n        \"allow-server-selection\": \"https://schema.org/actionOption\",\n        \"allow-spec-url-load\": \"https://schema.org/actionOption\",\n        \"allow-spec-file-load\": \"https://schema.org/actionOption\",\n        \"allow-spec-file-download\": \"https://schema.org/actionOption\",\n        \"persist-auth\": \"https://schema.org/actionOption\",\n        \"fill-request-fields-with-example\"\
  : \"https://schema.org/actionOption\",\n        \"update-route\": \"https://schema.org/actionOption\"\n      }\n    },\n    \"Authentication\": {\n      \"@id\": \"rapidoc:authentication\",\n      \"@context\": {\n        \"api-key-name\": \"https://schema.org/identifier\",\n        \"api-key-location\": \"https://schema.org/category\",\n        \"api-key-value\": \"https://schema.org/accessCode\",\n        \"fetch-credentials\": \"https://schema.org/actionOption\"\n      }\n    },\n    \"Schema\": {\n      \"@id\": \"rapidoc:schema\",\n      \"@context\": {\n        \"schema-style\": \"https://schema.org/encodingFormat\",\n        \"schema-expand-level\": \"https://schema.org/position\",\n        \"schema-description-expanded\": \"https://schema.org/actionOption\",\n        \"default-schema-tab\": \"https://schema.org/category\",\n        \"schema-hide-read-only\": \"https://schema.org/actionOption\",\n        \"schema-hide-write-only\": \"https://schema.org/actionOption\"\n      }\n\
  \    },\n    \"Slots\": {\n      \"@id\": \"rapidoc:slots\",\n      \"@context\": {\n        \"logo\": \"https://schema.org/image\",\n        \"header\": \"https://schema.org/WPHeader\",\n        \"footer\": \"https://schema.org/WPFooter\",\n        \"nav-logo\": \"https://schema.org/image\",\n        \"overview\": \"https://schema.org/description\"\n      }\n    },\n    \"Events\": {\n      \"@id\": \"rapidoc:events\",\n      \"@context\": {\n        \"spec-loaded\": \"https://schema.org/Event\",\n        \"before-try\": \"https://schema.org/Event\",\n        \"after-try\": \"https://schema.org/Event\",\n        \"api-server-change\": \"https://schema.org/Event\",\n        \"before-render\": \"https://schema.org/Event\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rapidoc/refs/heads/main/json-ld/rapidoc-context.jsonld
tags:
- Documentation
- Platform
- Web Components
- OpenAPI
- JSON-LD
- Linked Data
- Semantic Web
---

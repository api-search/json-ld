---
api_specs:
- filename: cdn-openapi.yml
  format: yaml
  label: Google Cloud CDN API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-cdn/refs/heads/main/openapi/cdn-openapi.yml
class_count: 10
classes:
- BackendService
- UrlMap
- CacheInvalidationRule
- name
- description
- id
- selfLink
- protocol
- enableCDN
- cacheMode
context_file: json-ld/cdn-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-cdn/refs/heads/main/json-ld/cdn-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cdn from Google Cloud CDN.
layout: jsonld
name: Cdn Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gcp
  uri: https://cloud.google.com/schema#
properties:
- container: ''
  name: defaultTtl
  type: integer
- container: ''
  name: maxTtl
  type: integer
- container: ''
  name: creationTimestamp
  type: dateTime
property_count: 3
provider_name: Google Cloud CDN
provider_slug: google-cloud-cdn
slug: cdn-context
source_filename: cdn-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://cloud.google.com/cdn/schema#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gcp\": \"https://cloud.google.com/schema#\",\n    \"BackendService\": \"gcp:CDNBackendService\",\n    \"UrlMap\": \"gcp:CDNUrlMap\",\n    \"CacheInvalidationRule\": \"gcp:CDNCacheInvalidationRule\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": \"schema:identifier\",\n    \"selfLink\": \"schema:url\",\n    \"protocol\": \"gcp:protocol\",\n    \"enableCDN\": \"gcp:enableCDN\",\n    \"cacheMode\": \"gcp:cacheMode\",\n    \"defaultTtl\": {\n      \"@id\": \"gcp:defaultTtl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxTtl\": {\n      \"@id\": \"gcp:maxTtl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"creationTimestamp\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\
  \n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-cdn/refs/heads/main/json-ld/cdn-context.jsonld
tags:
- Caching
- CDN
- Content Delivery
- Google Cloud
- Networking
- JSON-LD
- Linked Data
- Semantic Web
---

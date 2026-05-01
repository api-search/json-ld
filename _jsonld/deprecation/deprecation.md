---
class_count: 0
classes: []
context_file: json-ld/deprecation.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/deprecation/refs/heads/main/json-ld/deprecation.jsonld
description: JSON-LD context defining the semantic vocabulary for Deprecation from Deprecation.
layout: jsonld
name: Deprecation Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: depr
  uri: https://raw.githubusercontent.com/api-evangelist/deprecation/main/vocabulary/deprecation-vocabulary.json#
properties: []
property_count: 0
provider_name: Deprecation
provider_slug: deprecation
slug: deprecation
source_filename: deprecation.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"schema\": \"https://schema.org/\",\n    \"depr\": \"https://raw.githubusercontent.com/api-evangelist/deprecation/main/vocabulary/deprecation-vocabulary.json#\"\n  },\n  \"@type\": \"schema:TechArticle\",\n  \"@id\": \"https://github.com/api-evangelist/deprecation\",\n  \"schema:name\": \"API Deprecation\",\n  \"schema:description\": \"API deprecation, sunset headers, end-of-life management, and API retirement tools and services.\",\n  \"schema:about\": [\n    { \"@id\": \"depr:Deprecation\" },\n    { \"@id\": \"depr:Sunset\" },\n    { \"@id\": \"depr:EndOfLife\" },\n    { \"@id\": \"depr:DeprecationHeader\" },\n    { \"@id\": \"depr:SunsetHeader\" },\n    { \"@id\": \"depr:DeprecationPolicy\" },\n    { \"@id\": \"depr:MigrationPath\" }\n  ],\n  \"schema:keywords\": [\n    \"API Retirement\",\n    \"Deprecation\",\n    \"End of Life\",\n    \"Sunset\"\n  ],\n  \"schema:citation\": [\n    {\n      \"@type\": \"schema:CreativeWork\",\n      \"schema:name\"\
  : \"RFC 8594: The Sunset HTTP Header Field\",\n      \"schema:url\": \"https://www.rfc-editor.org/rfc/rfc8594.html\"\n    }\n  ],\n  \"schema:dateCreated\": \"2026-03-29\",\n  \"schema:dateModified\": \"2026-04-28\"\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/deprecation/refs/heads/main/json-ld/deprecation.jsonld
tags:
- API Retirement
- Deprecation
- End of Life
- Sunset
- Lifecycle
- Migration
- JSON-LD
- Linked Data
- Semantic Web
---
